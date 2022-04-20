# Bank-Management-System
Features 
1.Create Bank Account.
2.Deposit & Withdraw Money
3.Bank Account Type Support (e.g. Current Account, Savings Account)
4.Interest calculation depending on the Bank Account type
5.Transaction report with a date range filter
6.See balance after every transaction in the Transaction Report
7.Calculate Monthly Interest Using Celery Scheduled tasks
8.More efficient and accurate interest calculation and balance update
9.Ability to add Minimum and Maximum Transaction amount restriction
10.Modern UI with Tailwind CSS

Prerequisites

Be sure you have the following installed on your development machine:

Python >= 3.7
Redis Server
Git
pip
Virtualenv (virtualenvwrapper is recommended)

Requirements

celery==4.4.7
Django==3.2
django-celery-beat==2.0.0
python-dateutil==2.8.1
redis==3.5.3

Django Installation Steps :-

Install Python 3.7 Or Higher
Install Django version 2.2.0
Install all dependencies cmd -python -m pip install –-user -r requirements.txt
Finally run cmd - python manage.py runserver
