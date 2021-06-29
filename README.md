# 1.- Requerimients
* [Python: 3.9.x](https://www.python.org)
# 2.- Install

* Install [pre-commit](https://pre-commit.com) by executing the following command:
``pip install pre-commit``

* Clone or Fork the repository

* Install the current hooks by executing the following command:
``pre-commit install``

* Open a terminal in the root folder (git-flow-test)

* Move the local repo hooks to the official github folder by executing the following command:
``robocopy .githooks .git/hooks``
**IMPORTANT: EVERY TIME THE LOCAL HOOKS LOCATED AT ``.githooks`` FOLDER ARE UPDATED, YOU HAVE TO RUN THE ABOVE COMMAND TO SYNC IT**

* You are done, enjoy it 😊