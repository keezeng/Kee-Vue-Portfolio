# Kee-Vue-Portfolio
    Cybersecurity
Project 1 Technical Brief


Make a copy of this document before you begin. Place your answers below 
each question. This completed document will be your deliverable for Project 1. Submit it through Canvas when you’re finished with the project at the end of the week.


Your Web Application

Enter the URL for the web application that you created:

https://keesresume.azurewebsites.net/


Paste screenshots of your website created (Be sure to include your blog posts):





Day 1 Questions

General Questions

What option did you select for your domain (Azure free domain,  GoDaddy domain)?

Azure 


What is your domain name?

https://keesresume.azurewebsites.net/


Networking Questions

What is the IP address of your webpage?


20.37.196.196




What is the location (city, state, country) of your IP address?

Sydney,  New South Wales in australia


Run a DNS lookup on your website. What does the NS record show?




Web Development Questions

When creating your web app, you selected a runtime stack.  What was it? Does it work on the front end or the back end? 

Php, backend


Inside the /var/www/html directory, there was another directory called assets. Explain what was inside that directory.

There was css and images, 




Consider your response to the above question. Does this work with the front end or back end?

Backend, css is what you use to style your page



Day 2 Questions

Cloud Questions

What is a cloud tenant?

an individual or an organization that utilizes cloud services provided by a cloud service provider


Why would an access policy be important on a key vault?

So no one can access to your keyvault


Within the key vault, what are the differences between keys, secrets, and certificates?

Key vault- keys used for encryption, decryption, or signing operations

Secret vaults- it stores pieces of data, such as passwords, connection strings, API keys, or any other confidential information

Certificate- digital documents that contain cryptographic keys like organizations identity, public key, and digital signatures




Cryptography Questions

What are the advantages of a self-signed certificate?

Most of them are free to create and use.  They are useful for testing environments.  It can be generated quickly and deployed right away.


What are the disadvantages of a self-signed certificate?

Users usually sees an unsecure website which could be risky and have threats. It could be a fake website trying to obtain your logins and password.  


What is a wildcard certificate?

A certificate use to secure multiple domains


When binding a certificate to your website, Azure only provides TLS versions 1.0, 1.1, and 1.2.  Explain why SSL 3.0 isn’t provided.

Because ssl 3.0 is insecure


After completing the Day 2 activities, view your SSL certificate and answer the following questions:

Is your browser returning an error for your SSL certificate? Why or why not?

[Enter answer here]


What is the validity of your certificate (date range)?

Issued 12/27/2022
Expired 12/22/2023


Do you have an intermediate certificate? If so, what is it?

no


Do you have a root certificate? If so, what is it?

no


Does your browser have the root certificate in its root store?

[Enter answer here]


List one other root CA in your browser’s root store.

[Enter answer here]



Day 3 Questions

Cloud Security Questions 

What are the similarities and differences between Azure Web Application Gateway and Azure Front Door?

Similarities
They both have load balancers, they both support ssl/tls to handle encrypted traffic and decrypt them from the backend
Differences
They both operate in different osi layers,  azure front door is design for a global scale vs azure web app is more for in a specified region.


A feature of the Web Application Gateway and Front Door is “SSL Offloading.” What is SSL offloading? What are its benefits?

Is the the process of decrypting SSL/TLS encrypted traffic at a network endpoint before forwarding it to the backend servers


What OSI layer does a WAF work on?
7th layer
Select one of the WAF managed rules (e.g., directory traversal, SQL injection, etc.), and define it.

Waf sql injection is when attackers manipulates the apps input to execute malicious sqls


Consider the rule that you selected. Could your website (as it is currently designed) be impacted by this vulnerability if Front Door wasn’t enabled? Why or why not?

It still can, but it should be detected before reaching the backend


Hypothetically, say that you create a custom WAF rule to block all traffic from Canada. Does that mean that anyone who resides in Canada would not be able to access your website? Why or why not? 

No, anyone who has a canada ip would be block


Include screenshots below to demonstrate that your web app has the following:

Azure Front Door enabled




A WAF custom rule





Disclaimer on Future Charges 

Please type “YES” after one of the following options:

Maintaining website after project conclusion: I am aware that I am responsible for any charges that I incur by maintaining my website. I have reviewed the guidance for minimizing costs and monitoring Azure charges.

Disabling website after project conclusion: I am aware that I am responsible for deleting all of my project resources as soon as I have gathered all of my web application screen shots and completed this document.



© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

