NoSQLAttack
Introduction

Some attack tests are based on and extensions of follow papers

Diglossia: Detecting Code Injection Attacks with Precision and Efficiency
No SQL, No Injection?
Several thousand MongoDBs without access control on the Internet.
There are two systems for testing NoSQL injection in this project-NoSQLInjectionAttackDemo.

Background
NoSQL injection attacks, for example php array injection, javascript injection and mongo shell injection, endanger mongoDB. There are thousands of mongoDB are exposed on the internet, and hacker can download data from exposed mongoDB.

Requirements
On a Debian or Red Hat based system, NoSQLAttack's dependencies already be writen in setup.py. This project is built on Pycharm COMMUNITY 2016.1 with python 2.7.10.

Varies based on features used:

Shodan-1.5.3
httplib2-0.9
Python-2.7
pymongo-2.7.2
requests-2.5.0
ipcalc-1.1.3
MongoDB
Building
On Linux, it goes something like this:

cd NoSQLAttack
python setup.py install
Tips
If after entering "python setup.py install", terminal show error information "No module named setuptools", just install setuptools. On Ubuntu, "sudo apt-get install python-setuptools", this command is useful
Install MongoDB for MongoDB default configuration attack.
