# CS305

Summary of Artemis Financial and Its Software Requirements:

Artemis Financial is a financial services company that needed to modernize its operations by enhancing the security of its web application. The company was particularly concerned about the security of client data and financial information during data transfers. To address this, they sought to implement a file verification step using checksums to ensure secure communications. My task was to examine the existing software, identify security vulnerabilities, and refactor the code to include secure communication mechanisms, such as encryption and HTTPS protocols.

Successes in Addressing Software Security Vulnerabilities:

When identifying and addressing Artemis Financial's software security vulnerabilities, I effectively applied industry-standard best practices for secure coding. By implementing strong encryption methods and secure communication protocols, I ensured that sensitive data was protected during transmission. Coding securely is crucial because it safeguards against unauthorized access and data breaches, which can have severe consequences for both the company and its clients. Secure software adds significant value to a company’s overall well-being by protecting its reputation, ensuring compliance with industry regulations, and fostering client trust.

Challenges and Insights from the Vulnerability Assessment:

One of the more challenging aspects of the vulnerability assessment was ensuring that all potential vulnerabilities were identified and adequately mitigated without introducing new issues. However, the process was also very insightful, as it reinforced the importance of a comprehensive approach to security that includes both preventive measures (such as encryption) and regular assessments (like dependency checks). These assessments are critical in maintaining a secure software environment, especially in industries handling sensitive financial data.

Increasing Security Layers and Future Strategies:

To increase layers of security, I implemented an asymmetric encryption method for secure communications and configured the application to use HTTPS. In the future, I would continue to use tools like OWASP Dependency-Check for identifying vulnerabilities and would rely on both static and dynamic analysis tools to decide on appropriate mitigation techniques. These tools provide a comprehensive view of potential weaknesses in the code, enabling a more informed approach to security.

Ensuring Functionality and Security Post-Refactoring:

To ensure the functionality and security of the software after refactoring, I conducted thorough testing, including unit tests and integration tests, and verified that no new vulnerabilities were introduced. This involved running static code analysis and dependency checks to ensure that the changes did not compromise the system’s security. Regular code reviews and testing are essential practices that I plan to continue using to maintain secure and functional codebases.

Valuable Tools and Practices for Future Use:

During this project, I utilized several tools and coding practices that will be valuable in future assignments, such as the Java Keytool for generating self-signed certificates, Maven for managing dependencies, and the OWASP Dependency-Check plugin for identifying security vulnerabilities. These tools, along with best practices for secure coding, are critical in developing robust, secure applications.

Demonstrating Skills to Future Employers:

From this assignment, I can showcase my ability to identify and mitigate software security vulnerabilities, implement encryption algorithms, and ensure secure communications in a web application. I can demonstrate my proficiency in using industry-standard tools and practices to develop secure software, which is an essential skill for any software engineer, particularly in fields dealing with sensitive data. This project highlights my commitment to secure coding and my ability to deliver high-quality, secure software solutions.
