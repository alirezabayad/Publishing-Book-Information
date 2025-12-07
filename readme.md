## Publishing Book Information

When you run this code in Navicat(as a SQLite code), it makes many table, such as:
- ```Books```\
  The ```Books``` table created by:
  - ```Title```
  - ```Price```
  - ```ESRB_Rating_id```(that ```id``` is for interface tables)
  - ```Publisher_id```(that ```id``` is for interface tables)
  - ```Edition```
  - ```ISBN```
  - ```Pages```
  - ```Print_Run```\
  The output will be a table like this:
    | Id | Title | Price | Esrb Rating_Id | Publisher_Id | Edition | ISBN | Pages | Print Run | 
    |:--:|:-----:|:-----:|:--------------:|:------------:|:-------:|:----:|:-----:|:---------:|
    | 1 | Sinohe | 200000 | 5(Because of the existance of interface tables, we have to use id(s) instead of tex) | 5(Because of the existance of interface tables, we have to use id(s) instead of tex) | 38812779 | 16674228 | 1000 | 5000 |
- ```Editors```\
The ```Editors``` table created by:
  - ```Name```
  - ```Family```
  - ```National_Number```
  - ```Nationality```
  - ```Date_Of_Birth```\
  The output will be a table like this:
    | Id | Name | Falmily | National_Number | Nationality | Date_Of_Birth |
    |:--:|:----:|:-------:|:---------------:|:-----------:|:-------------:|
    | 1 | Ali | Rezaei | 6300256897 | Iran | 5/12/2000 |
- ```Languages```\
The ```Languages``` table created by:
  - ```Name```
  The output will be a table like this:
    | Id | Name |
    |:--:|:----:|
    | 1 | EN |
- ```Authors```\
The ```Authors``` table created by:
  - ```Name```
  - ```Family```
  - ```National_Number```
  - ```Nationality```
  - ```Date_Of_Birth```
  The output will be a table like this:
    | Id | Name | Falmily | National_Number | Nationality | Date_Of_Birth |
    |:--:|:----:|:-------:|:---------------:|:-----------:|:-------------:|
    | 1 | Peyman | Ghasem Khani | 6300876312 | Iran | 1/25/2007 |
- ```Publishers```\
The ```Publishers``` table created by:
  - ```Address```
  - ```Name```
  - ```Phone_Number```
- ```Translators```
  The output will be a table like this:
    | Id | Address | Name | Phone_Number |
    |:--:|:-------:|:----:|:------------:|
    | 1 | Tehran | Fardaei Behtar | 013........ |
The ```Translators``` table created by:
  - ```Name```
  - ```Family```
  - ```National_Number```
  - ```Nationality```
  - ```Date_Of_Birth```
  The output will be a table like this:
    | Id | Name | Falmily | National_Number | Nationality | Date_Of_Birth |
    |:--:|:----:|:-------:|:---------------:|:-----------:|:-------------:|
    | 1 | Kian | Rezaei | 6300278456 | Iran | 8/7/1997 |
- ```ESRB Rating```\
The ```ESRB Rating``` table created by:
  - ```Name```
  The output will be a table like this:
    | Id | Name |
    |:--:|:----:|
    | 1 | Mature |
- ```Resources```\
The ```Resources``` table created by:
  - ```Title```
  The output will be a table like this:
    | Id | Title |
    |:--:|:-----:|
    | 1 | ChatGPT |
- ```and interface tables(The relationships between the tables are established through IDs, and the relationships between the book and the author, editor, translator, etc are entirely fictitious and have no basis in reality.)```
  As an example, I will use the ```Book_Author``` table:
    | Id | Book_Id | Author_Id |
    |:--:|:-------:|:---------:|
    | 1 | 4 (The 4th book's id) | 8 (The 8th author's id) |
```This means that a book with ID 4 was written by an author with ID 8.```\
And the other tables follow the same pattern.
### Instructions
1. First of all you most install Navicat app.
2. Than you have to create a ```new conection```.
3. Later on, you must create a ```new query``` and paste the code.
4. Afrter all these problems you can run the code and enjoy that. 
\
\
\
\
Created with ❤️ in Iran
