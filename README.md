# Python package: py_mysql_connector
MySQL database connector written in Python

# Dependencies
This project depends on next packages:

    mysql-connector-python

# Use
Install the package:

    $>  {pip | pip3} install py_mysql_connector
    
Create a connection object:

    $> from py_mysql_connector.DBConnection import DBConnection
    
    $> connection = DBConnection('db_username', 'db_password', 'db_machine', 'db_name')
    
Execute a query:

    $> query_result = connection.execute_query('YOUR_QUERY_HERE', {})
    
Disconnect:

    $> connection.disconnect()
    
# Future improvements:

    - Enable DBConnection support to other ports different than 3306 (default port)