## Some key GitHub terms

__Note:__ Projects on GitHub can use two types of collaborative development models called _fork and pull_ and _shared repository_. Here I focus more on the _fork and pull_ model.

---

_fork and pull_
- The fork & pull model lets anyone fork an existing repository and push changes to their personal fork without requiring access be granted to the source repository. 
- The changes must then be pulled into the source repository by the project maintainer. 
- This model reduces the amount of friction for new contributors and is popular with open source projects because it allows people to work independently without upfront coordination.

_branch_
- Branching is a core concept in Git, and the entire GitHub Flow is based upon it. 
- There is always one "master" branch and then zero or more other branches. 
- The master should always be viewed as, well, the master! Anything in the master branch is always deployable.

_commit_
- Each commit is considered a separate unit of change and full history is persisted.
- Commit messages are important, especially since Git tracks your changes and then displays them as commits once they're pushed to the server. By writing clear commit messages, you can make it easier for other people to follow along and provide feedback.

_pull request_
- This is how people contribute their changes back to the master (or to another specified branch). 
- When a pull request is received, the owner can review the changes, provide feedback comments, etc. and decide to merge in the changes, if desired.

_merge_
- The process of taking submitted changes from other branches and contributing them into the master branch.
