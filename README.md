# Mysql-with-python
## Key feature
### Create database
<ol>
<li>We need to create a table in <strong>python language</strong> and it will store all the values into the <strong>phpmyadmin (database).<strong></li>
<li>First step :- Create connection between <strong>python language</strong> and <strong>phpmyadmin</strong> with the help of <strong>mysql.connector.</strong></li>
<li>Now we need to fill all the details of server like :- host, username, password</li>
<li>Define object via using object() method</li>  
<li>Second step :- create database via using <strong>Mysql query.</strong> and execute this query with the help of <strong>execute()</strong> method </li>
<li>Close object and server connection.</li>
<li> <pre>    +--------------------+
    | Database           |
    +--------------------+
    | information_schema |
    | 12feb              |
    | mysql              |
    | performance_schema |
    | sys                |
    +--------------------+  </pre></li>

  
### Create Table 
<li>Now we will create the table with the help of <strong>Mysql query.</strong></li>
<li>First create connection between python and database with the help of <strong>mysql.connector</strong>. </li>
<li>Then define object via using object() method</li> 
<li>Now we will create a table in which we will define the name of column that we required in this table. </li>
<li>In this table we need one <strong>column</strong> in which we can assign <strong>AUTO_INCREMENT</strong> attribute.</li>
<li>Whenever you insert a new row into a table, MySQL automatically assigns a sequence number to the AUTO_INCREMENT column.</li>
<li>Now we can implement the table via using <strong>execute()</strong> method.</li>
<li><strong>commit()<strong> method use to enter data into the database</li>
<li>Close object and server connection.</li>
  
<li>Now insert values into the table with the help of <strong>insert query.</strong></li>
<li>Execute the insert query. </li>
<li>Insert query will insert all values into the table with the help of commit() method.</li>
<li>At the end close object and server connection.</li>
</ol>
