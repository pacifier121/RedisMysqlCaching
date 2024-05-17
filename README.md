How to:<br>
> Install redis and make sure it's working<br>
> Install mysql:<br>
> add 'dbuser' with pass 'dbpass'<br>
> add DB 'mydb'<br>
> add table 'keyValue' inside 'mydb' with following schema<br>
+-----------+--------------+------+-----+---------+-------+<br>
| Field     | Type         | Null | Key | Default | Extra |<br>
+-----------+--------------+------+-----+---------+-------+<br>
| somekey   | varchar(200) | NO   | PRI | NULL    |       |<br>
| somevalue | longtext     | YES  |     | NULL    |       |<br>
+-----------+--------------+------+-----+---------+-------+<br>
> run `npm install`