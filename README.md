# CS305

# Artemis Financial Secure Software Report

## Artifact Summary

This project involved working with a fictional client, **Artemis Financial**, a company that develops custom financial plans for clients. The client requested enhanced software security for their web application to ensure client data was transferred and stored securely. Specifically, they wanted a way to verify data integrity and implement secure communication protocols.

## Reflection

To meet the client’s needs, I refactored the application to include a SHA-256 checksum for file verification and implemented HTTPS using a self-signed SSL certificate. I did well in identifying where security layers were missing and applying industry-standard encryption and testing techniques. Secure coding is essential because it helps protect user data, maintain trust, and prevent potential attacks that can harm a company’s reputation and finances.

One of the more challenging but rewarding parts of the project was setting up and configuring the keystore and HTTPS — it required careful attention to file paths, configurations, and Java tooling. To add layers of security, I used SHA-256 hashing, SSL encryption, and Maven OWASP Dependency-Check scanning. In the future, I would continue using OWASP and automated testing tools to assess vulnerabilities and prioritize fixes.

To ensure functionality, I ran the application and tested the `/hash` route, confirming that the checksum was generated as expected. After refactoring, I used the OWASP plugin to verify that no new vulnerabilities had been introduced. I also used clean Maven project practices and modular code to keep things secure and readable.

The tools I used — such as Maven, OWASP Dependency-Check, and `keytool` — will be useful in future projects that involve secure development and compliance testing. If I were to show something from this project to a future employer, I’d include both the code and my secure practices report, since it demonstrates real-world security practices like HTTPS, encryption, and secure code refactoring.
