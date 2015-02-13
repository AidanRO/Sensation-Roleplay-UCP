
Go in every file, and change these lines:

"<link rel="stylesheet" type="text/css" href="http://sensation-rp.com/css/static/style.css" />"
"<img alt="header_249e0529" src="http://sensation-rp.com/img/header/oldbanner.jpg" />"

to:


"<link rel="stylesheet" type="text/css" href="http://yoursite.yoursitetld/css/static/style.css" />"
"<img alt="header_249e0529" src="http://yoursite.yoursitetld/img/header/oldbanner.jpg" />"


And for the Roleplay Quiz, you will need to do the following:

Excepting the normal database of the IBPRP, import in your mySQL DB the file from register/part-3 called 'rpquiz.sql'.
Then go to /register/part-3/ and change things in config.php according to your SQL Database. (make that thing for /confirm folder too)
