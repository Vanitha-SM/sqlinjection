# sqlinjection
Exploiting SQL Injection vulnerability

# AIM:
To exploit SQL Injection vulnerability using Multidae web application in Metasploitable2

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

SQL Injection is a sort of infusion assault that makes it conceivable to execute malicious SQL statements. These statements control a database server behind a web application. Assailants can utilize SQL Injection vulnerabilities to sidestep application safety efforts. They can circumvent authentication and authorization of a page or web application and recover the content of the whole SQL database. 
Identify IP address using ifconfig in Metasploitable2

![image](https://github.com/Vanitha-SM/sqlinjection/assets/119557985/01ceab3b-0d27-4bde-b011-6c30f544a92c)


Use the above ip address to access the apache webserver of Metasploitable2 from kali linux. In Kali Linux use the ip address in a web browser.

![image](https://github.com/Vanitha-SM/sqlinjection/assets/119557985/f7e95ba5-16d9-4866-8645-e9603cab4f73)

Select Multidae from the menu listed as shown above. You will get the page as displayed below:

![image](https://github.com/Vanitha-SM/sqlinjection/assets/119557985/c6535f3b-6b87-4c12-ad64-e8a58aac7ef8)

Click on the menu Login/Register and register for an account

![image](https://github.com/Vanitha-SM/sqlinjection/assets/119557985/900dc066-8e72-4dc0-a192-55bb9f622d3c)

Click on the link “Please register here”

![image](https://github.com/Vanitha-SM/sqlinjection/assets/119557985/5ae9f17a-6d8b-4926-b59d-68be6a37c3ae)

Click on “Create Account” to display the following page:

![Screenshot 2024-05-07 090927](https://github.com/Vanitha-SM/sqlinjection/assets/119557985/aae3b30e-9e56-4814-9ba9-a10783b7d273)



## RESULT:
The SQL Injection vulnerability is successfully exploited using the Multidae web application in Metasploitable2.
