# 1.- Requerimients
* [Python: 3.9.x](https://www.python.org)
# 2.- Install

* Install [pre-commit](https://pre-commit.com) by executing the following command:<br>
``pip install pre-commit`` or ``py -m pip install pre-commit`` (if you don't have pip added to your PATH)

* Clone or Fork the repository

* Open a terminal in the root folder (git-flow-test)

* Install the current hooks by executing the following command:<br>
``pre-commit install``

* Move the local repo hooks to the official github folder by executing the following command:<br>
``robocopy .githooks .git/hooks``<br>
**IMPORTANT: EVERY TIME THE LOCAL HOOKS LOCATED AT ``.githooks`` FOLDER ARE UPDATED, YOU HAVE TO RUN THE ABOVE COMMAND TO SYNC IT**

* You are done, enjoy it 😊
