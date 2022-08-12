
## Stacks used

- HTML
- CSS
- Bootstarp
- Flask(python framework)
- SQLAlchemy
- Flask forms 
- ChartJS


## [Installation](#installation)
## Features

- [Create, Upadate , Read and Delete Books and Members](#book)
- [Import books from Frappe API](#Import-books-from-Frappe-API)
- [Manage Transactions](#Transaction-Records)
- [See reports of top 10 popular books and most paying customers](#Reports)

***
## Installation
- Run the command to clone the repository

  git clone https://github.com/fakhruddin7/library-mangement.git
```
- Install all requirements with

cd library-management
pip install -r requirements.txt
```
- Set your secret key in /library/\_\_init\_\_.py file
- for creating a local DB
python
>>from library import db
>>db.create_all()
```
- run commad to start the server

flask run
```
***
## book
### Read books from Database and dipslayed in the form of table
![book](/screenshot/book.PNG)


## Import books from Frappe API
![import](/screenshot/import-book.PNG)
***

***
## Transaction Records
[!transaction](/screenshot/transactions.PNG)

***

## Reports
![reports](/screenshot/report.PNG)
