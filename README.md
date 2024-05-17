How to:
> Install redis and make sure it's working
> Install mysql:
> add 'dbuser' with pass 'dbpass'
> add DB 'mydb'
> add table 'keyValue' inside 'mydb' with following schema
+-----------+--------------+------+-----+---------+-------+
| Field     | Type         | Null | Key | Default | Extra |
+-----------+--------------+------+-----+---------+-------+
| somekey   | varchar(200) | NO   | PRI | NULL    |       |
| somevalue | longtext     | YES  |     | NULL    |       |
+-----------+--------------+------+-----+---------+-------+
> run `npm install`