# reddit_mongodb_reconstructor
Takes Reddit comments and Reddit submissions from files.pushshift.io and creates a nested collection out of it.

## Assumes the following

1) You have downloaded the RC_<year> and RS_<year> reddit archives from http://files.pushshift.io
2) You have imported the json into a mongo database with a collection for the submissions and a collection for the comments.
  
  
This ipython code with reconcile the two creating the comments as nested children of the parent submission.

![collection_relationship](https://raw.githubusercontent.com/gabefair/reddit_mongodb_reconstructor/master/1367599229236120533.jpg)
![collection_relationship](https://raw.githubusercontent.com/gabefair/reddit_mongodb_reconstructor/master/submission.png)
![collection_relationship](https://raw.githubusercontent.com/gabefair/reddit_mongodb_reconstructor/master/example_comment.png)
