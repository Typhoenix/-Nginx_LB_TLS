## Load Balancer Solution With Nginx and SSL/TLS
It's critical we secure our client-server communcation with a more secured protocol such as HTTPS. This is to prevent security threats one of which is called Man-In-The-Middle (MIMT) attack.

SSL and its newer version, TSL - is a security technology that protects connection from MITM attacks by creating an encrypted session between browser and Web server..

SSL/TLS uses digital certificates to identify and validate a Website. A browser reads the certificate issued by a Certificate Authority (CA) to make sure that the website is registered in the CA so it can be trusted to establish a secured connection.

Task
In this project we'll register our website using LetsEnrcypt Certificate Authority, to automate certificate issuance we'll use a shell client recommended by LetsEncrypt - cetrbot.

Configure Nginx as a Load Balancer
Register a new domain name and configure secured connection using SSL/TLS certificates
Your target architecture will look like this:

