# Python 8-bit Snake Game

<img src="https://github.com/colin-lag/8-bit-Snake/blob/master/Screenshots/menu.png" alt="Menu Screenshot" width="60%">

## Description 

Created by Colin Laganier and Thomas Le Menestrel.

Inspired by the famous "Snake" game. In this version, the user controls the snake with the directional arrows in a window. The snake can eat two different versions of fruits of different value, as well as bombs that reverse the controls. The snake grows in length every time it eats. When the snake hits the walls or itself, the user looses and can add their highscore to the highscore table.

Coded in Python 3.6 with MySQL database for highscore. 

## Libraries

-Python v3.6.4<br>
-Pygame v1.9.3 <br>
-Time v15.3<br>
-Random v9.6<br>
-Mysql-connector v2.2.9

## Installation 

To import the highscore database, simply create a new database in your MySQL server and use the following command: 

```shell
$ mysql -u username -p new_database < highscore.sql
```

Then add your username and password to the Python file:

````python
    cnx = mysql.connector.connect(
        user='username', password='password', host='localhost',
        database='highscore')
````

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

-Snake Head : CC BY 3.0, https://piq.codeus.net/picture/293531/Snake-head <br>
-Snake Body : Modified from Shake Head (authorized by license)<br>
-Apple : CC BY ND, https://www.newgrounds.com/art/view/thexxxreaper/pixel-apple<br>
-Sound collision : CC BY 3.0, https://freesound.org/people/ProjectsU012/sounds/333785/


