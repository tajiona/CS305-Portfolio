## 1. Client and Software Requirements

Artemis Financial was the client, and the company provides individualized financial plans for customers. The company wanted to modernize its web application and improve its security, especially for protecting client and financial information. The main issues I addressed were software vulnerabilities, secure communications, data integrity, and dependency security.

## 2. Software Security

I did well at identifying security concerns by reviewing the application's code and using security testing tools such as OWASP Dependency-Check. Coding securely is important because vulnerabilities can expose sensitive information or allow attackers to interfere with an application. Strong software security also helps protect a company's customers, reputation, and overall operations.

## 3. Challenging or Helpful Part

The vulnerability assessment was challenging because there were multiple dependencies and security issues to review. The most helpful part was learning how to use Dependency-Check to identify known vulnerabilities and understanding that not every reported issue can necessarily be fixed immediately. This helped me better understand how security testing fits into the development process.

## 4. Increasing Layers of Security

I increased the application's security by adding SHA-256 checksum verification, using a self-signed certificate, and configuring HTTPS for secure communication. I also used dependency scanning as another layer of testing. In the future, I would use vulnerability scanners, manual code reviews, and secure coding standards to identify vulnerabilities and determine the best mitigation techniques.

## 5. Functionality and Security Testing

I made sure the application remained functional by compiling and running the refactored code and testing the /hash endpoint through HTTPS. I verified that the application generated the SHA-256 checksum correctly and that the secure connection worked. After refactoring, I used OWASP Dependency-Check to review the application's dependencies and check for security vulnerabilities.

## 6. Resources, Tools, and Coding Practices

I used Java, Spring Boot, Java Keytool, SHA-256, HTTPS, Maven, Eclipse, and OWASP Dependency-Check during this project. I also practiced secure coding techniques such as using modern cryptographic algorithms, protecting communications with HTTPS, and testing dependencies for known vulnerabilities. These tools and practices can be useful in future programming and security assignments.

## 7. Portfolio and Future Employers

For a future employer, I would show my Artemis Financial Practices for Secure Software Report because it demonstrates both my technical work and my ability to document security improvements. I could also show the refactored Java application and explain how I implemented SHA-256 checksum verification, HTTPS, certificates, and security testing. This project would demonstrate my ability to apply software security concepts to a real-world application.
