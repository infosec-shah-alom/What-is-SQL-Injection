# What-is-SQL-Injection

A SQL injection attack consists of the insertion or “injection” of a SQL query via the input data from the client to the application. A successful SQL injection exploit can read sensitive data from the database, modify database data (Insert/Update/Delete), execute administration operations on the database (such as shutdown the DBMS), recover the content of a given file present on the DBMS file system and in some cases issue commands to the operating system. SQL injection attacks are a type of injection attack, in which SQL commands are injected into data-plane input to affect the execution of predefined SQL commands.
SQL injection usually occurs when we ask a user for input, like their username/userid, and instead of a name/id, the user gives us an SQL statement that we will unknowingly run on our database.
Before we go into the basic SQL injection and how it occurs we have to know first what is the vulnerability of a website mean
A website vulnerability is a weakness or misconfiguration in a website or web application code that allows an attacker to gain some level of control of the site, and possibly the hosting server.
If the vulnerability of a website is quite large or if it has a low or high-level venerability then there is a possibility for the bad guys or the attackers to attack that website.
So to find a kind of website which has vulnerability we need the help of google dork. So what is google dork?
Google dork: 
Google Dorking, is a computer hacking technique that uses Google Search and other Google applications to find security holes in the configuration and computer code that websites use.
By using google dork we can find all those websites which contain vulnerabilities for this first we need to search in google using google dork. Here is the list of some
inurl:index.php?id=
inurl:trainers.php?id=
There are different ways to attack and get access to a website in this part we have learned about basic SQL.
User: 1 'or' 1 '=' 1....
Pass: 1 'or' 1 '=' 1....
We will need the above user and password to get access to the website.
Every website has a database in that database if we put a wrong username and false the query then will suddenly alert us.
But if we put the above query in the username and password field then the database will consider it as true and give the attacker unauthorized access.
The website won't understand the false query and the hacker will easily get access with the 1=1 query.
Example:
We can use the below link as an example:
https://www.*example.comm/adminIndex.php
#sqlinjection #bugbountytips #BugBountyHunter #bugbounty #CybersecurityExpert #pentester #cybersecurity #informationsecurity #vulnerabilityassessment #pentesting #RedTeam #BlueTeam #ethicalhacking #cybersecurityanalyst #vulnerability #websecuritytips #websitesecurity
