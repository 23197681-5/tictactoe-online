#TicTacToe
# powerbuilder-front-box

Use IBM db2 connection, and use this sql:

```sql
create table JOGODAVELHA(
  X char(1) default 'F',
  O char(1) default 'F',
  TURNO varchar(10) default 'willian',
  pronto decimal(10) default '0',
  Q1 char(1) default 'F',
  Q2 char(1) default 'F',
  Q3 char(1) default 'F',
  Q4 char(1) default 'F',
  Q5 char(1) default 'F',
  Q6 char(1) default 'F',
  Q7 char(1) default 'F',
  Q8 char(1) default 'F',
  Q9 char(1) default 'F'
);
```
##Config your db2 acess
in the root folder change the file "properties" and put inside that your username and your password

##Playing
You and your opponent must have connected to the same database.
