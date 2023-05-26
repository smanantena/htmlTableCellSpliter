# htmlTableCellSpliter

This project is my personal work for the "html table cell splite" on codingame

Test n°1 :

- Number of row = 2
- Cell config :
    1,1 1,2
    1,1
- Cell to split = n° 2 and split to column

Result for Test n°1 :

- Number of row = 2
- Cell config :
    2,1 1,2
    1,1 1,1
- Cell to split = n° 2 and split to column

_____________________________________________________________

Test n°2 :

- Number of row = 3
- Cell config :
    1,3 3,1
    1,2 1,1 1,1
    1,1
- Cell to split = n° 4 and split to column

Result for Test n°2 :

- Number of row = 3
- Cell config :
    1,3 4,1
    1,2 1,1 1,1 1,1
    1,1 2,1
- Cell to split = n° 4 and split to column

_____________________________________________________________

Test n°3 :

- Number of row = 4
- Cell config :
    2,1 1,3
    1,3 1,1
    1,1
    2,1
- Cell to split = n° 3 and split to column

Result for Test n°3 :

- Number of row = 4
- Cell config :
    3,1 1,3
    1,3 1,1 1,1
    2,1
    3,1
- Cell to split = n° 3 and split to column

_____________________________________________________________

Test n°4 :

- Number of row = 3
- Cell config :
    1,1 1,2
    1,2
    1,1
- Cell to split = n° 3 and split to column

Result for Test n°4 :

- Number of row = 3
- Cell config :
    1,1 2,2
    1,2
    1,1 1,1
- Cell to split = n° 3 and split to column

_____________________________________________________________

Test n°5 :

- Number of row = 3
- Cell config :
    1,3 3,1
    1,2 1,1 1,1
    1,1 1,1
- Cell to split = n° 3 and split to row

Result for Test n°5 :

- Number of row = 4
- Cell config :
    1,4 3,1
    1,3 1,1 1,2
    1,1
    1,1 1,1
- Cell to split = n° 3 and split to row

_____________________________________________________________

Test n°6 :

- Number of row = 5
- Cell config :
    1,1 1,2 1,1 2,1
    1,3 1,2 2,1
    1,1 1,1 1,3
    3,2
    1,1
- Cell to split = n° 5 and split to column

Result for Test n°6 :

- Number of row = 5
- Cell config :
    1,1 1,2 2,1 2,1
    1,3 1,2 1,2 2,1
    1,1 1,1 1,3
    4,2
    1,1
- Cell to split = n° 5 and split to column

_____________________________________________________________

Test n°7 :

- Number of row = 5
- Cell config :
    2,1 1,1 1,3 1,1
    1,3 2,1 1,4
    2,1
    3,2
    1,1
- Cell to split = n° 5 and split to row

Result for Test n°7 :

- Number of row = 6
- Cell config :
    2,1 1,1 1,4 1,1
    1,4 2,1 1,5
    2,1
    2,1
    3,2
    1,1
- Cell to split = n° 5 and split to column
