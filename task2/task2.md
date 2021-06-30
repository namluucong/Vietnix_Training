# **Report Vietnix Linux Basic**

#           PART 02: 
1. <a href='#1'> SSL
1. <a href='#2'> Domain
1. <a href='#3'> DNS
1. <a href='#4'> Hosting, VPS, Server
1. <a href='#5'> Reverse Proxy
1. <a href='#6'> Compare Nginx and Apache
1. <a href='#7'> Demo

<div id='1'></div>

***

# 1. SSL 
## What is SSL? 
- **SSL** stands for Secure Sockets Layer and, in short, it's the standard technology for keeping an internet connection secure and safeguarding any sensitive data that is being sent between two systems, preventing criminals from reading and modifying any information transferred, including potential personal details. **SSL** is the predecessor to the modern TLS encryption used today.
- A website that implements **SSL/TLS** has `HTTPS` in its URL instead of `HTTP`.

![](src/01_ssl.png)

## How does SSL work ?

- In order to provide a high degree of privacy, **SSL** encrypts data that is transmitted across the web. This means that anyone who tries to intercept this data will only see a garbled mix of characters that is nearly impossible to decrypt.
- **SSL** initiates an authentication process called a handshake between two communicating devices to ensure that both devices are really who they claim to be.
- **SSL** also digitally signs data in order to provide data integrity, verifying that the data is not tampered with before reaching its intended recipient.

![](src/01_ssl_work.png)

## Types of SSL
#### Extended Validation (EV SSL) Certificates
- **EV SSL** checks the right of the applicant to use a specific domain name plus, it conducts a thorough vetting of the organization.

#### Organization Validated (OV SSL) Certificates
- **OV SSL** checks the right of the applicant to use a specific domain name PLUS it conducts some vetting of the organization.


#### Domain Validated (DV SSL) Certificates
- **DV SSL** checks the right of the applicant to use a specific domain name.

![](src/01_types_ssl.png)

#### Subject Alternative Names (SANs SSL)
- **SANs SSL** allow you to secure a primary domain and then add additional domains to the Subject Alternative Name field of the certificate. 
#### Unified Communications Certificates (UCC)
- **UCC SSL** are also considered Multi-Domain SSL Certificates and have the same benefits.
#### Wildcard SSL Certificates
- **Wildcard SSL** are available as both OV and DV, and are used to secure a base domain and unlimited subdomains.

![](src/01_sans_wild_ssl.png)

<div id='2'></div>

# 2. Domain