# pypinky
Create table ages(name varchar(128),age integer)
Delete from ages
Insert into ages(name,age)values('Nialla',15);
Insert into ages(name,age)values('Hussain',18);
Insert into ages(name,age)values('Hebe',34);
Insert into ages(name,age)values('Corbin',36);
Insert into ages(name,age)values('Aisa',21);
Insert into ages(name,age)values('Rayann',28);
Select hex(name||age)As X from ages order by X
