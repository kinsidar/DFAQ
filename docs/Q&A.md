# Q & A == Questions and Answers

#### Q: Why is gh-pages not pushed to VSTS?
#### A: gh-pages is a branch created for github pages to use its content to generate the hosted site. The branch is only needed on github repository for github pages to host the site.

#### Also, gh-pages only contains statically generated webpage which is generated from the docs folder in the master branch. Therefore the site format and content is still being tracked by git. 