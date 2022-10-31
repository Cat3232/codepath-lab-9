# codepath-lab-9

# Pen Testing Live Targets

Time spent: **6** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: Insecure Direct Object Reference

Description: website blue is vulnerable to url manipulation. If we change the (Id= ) to (Id='OR'1'='1) we are able to reveal information that was not previously available. 

<img src="Lab 9blue.gif">


## Green

Vulnerability #1: ________Username Enumeration__________

Description: website green is vulnerable to Username Enumeration. When we enter a username that isn't valid, a message pops up (Log in was unsuccessful.), but when we enter a valid username the faild login message gets bolded. This indicates that when the faild login message is bolded that we have entered a valid username. 

<img src="Lab 9green.gif">


## Red

Vulnerability #1: Insecure Direct Object Reference

Description: Website red is also vulnerable to url manipulation. If we change the (Id= ) to (Id=10) we are able to reveal information that was not previously available and is set to release septemebr 1. If we change the (Id= ) to (Id=11) we are also able to reveal information on an employee that was fired. 

<img src="Lab 9red.gif">


## Notes

Describe any challenges encountered while doing the work
