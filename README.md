
Go in every file, and change these lines:

"<link rel="stylesheet" type="text/css" href="senasationroleplay bla bla" />"
"<img alt="header_249e0529" src="senasationroleplay bla bla" />"

to:


"<link rel="stylesheet" type="text/css" href="http://therewillbeyoursite/css/static/style.css" />"
"<img alt="header_249e0529" src="http://therewillbeyoursite/img/header/oldbanner.jpg" />"


And for the Roleplay Quiz, you will need to do the following:

Excepting the normal database of the IBPRP, import in your mySQL DB the file from register/part-3 called 'rpquiz.sql'.
Then go to /register/part-3/ and change things in config.php according to your SQL Database. (make that thing for /confirm folder too)
