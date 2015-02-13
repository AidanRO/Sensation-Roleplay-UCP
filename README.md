
You will need to go in every file (excepting index.php and updates.php) and change the following lines:

Line 12 - it's about the CSS location<br>
Line 13 and Line 14 - it's about JS's location<br>
Line 31 - it's about header's location

After that you will need to some files located in the following folders:

     * /register/part-3: config.php - there you will edit the mySQL connection info
     * /register/part-3/confirm: config.php - there you will edit the mySQL connection info
     * /register/part-4: variables.php - there you will edit the mySQL connection info
     * /ucp/index: session.php (things about selecting, and mysql connection), login.php (things about redirection after logingg on index.php from /ucp/index), variables.php(there you will edit the mySQL connection info)

And for the Roleplay Quiz, you will need to do the following:

Excepting the normal database of the IBPRP, import in your mySQL DB the file from register/part-3 called 'rpquiz.sql'.
Then go to /register/part-3/ and change things in config.php according to your SQL Database. (make the samething for /confirm folder too)
