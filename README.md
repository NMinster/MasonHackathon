#MasonHackathon

This code is from the first-place prize in social engineering and brute force attacks. 

Problem statement: George Mason University has a vulnerability in its username and password management for the redhat HTTP Server. 

Background: Usernames are publicly available at (ssh:https://binf.gmu.edu/). Given the usernames, passwords are dictated by the username plus the last four digits of the student or faculty ID number. 

Solution: Brute force password checks of username+4-digits provides access to the restricted folders. 

Suggestions: Require users upon account creation to set a new unique password, or link to university password. Restrict access to the root folder containing usernames. This system should be designed to block or delay repeated access attempts to prevent this kind of attack.

Warning: This script is trying to brute force the SSH login of a server by guessing passwords. Accessing a computer system without authorization is a crime in many jurisdictions, including under the United States Computer Fraud and Abuse Act (CFAA), and typically against the terms of service of any legitimate service provider. The code provided was used on my own account under the supervision of MasonHacks a group dedicated to finding vulnerabilities in and ethical manner.
