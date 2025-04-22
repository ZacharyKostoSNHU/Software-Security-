CS 305 Portfolio Reflection – Project Artifact Submission

For this portfolio submission, I have chosen to include my completed Artemis Financial
Practices for Secure Software Report from Project Two. This artifact demonstrates my
ability to write secure code, integrate encryption and SSL for secure communication, and
use tools like the Maven OWASP Dependency-Check plug-in to identify and mitigate
vulnerabilities.

Client Summary:
Artemis Financial is a fictional financial services company that required a secure backend
server to protect sensitive client data. The primary software requirement was to secure
communications through HTTPS, implement a cryptographic hash function for data
integrity, and detect any existing security vulnerabilities in their Java-based system.

Reflection:
While working on this project, I did a great job identifying insecure dependencies and
replacing or documenting them using the OWASP Dependency-Check tool. I also
implemented SHA-256 to ensure message integrity and integrated HTTPS using a keystore
and certificate to secure communication. Secure coding is essential because it helps protect
customer data, prevents financial loss, and maintains a company's reputation. Building in
security early reduces the cost of fixing vulnerabilities later.
The most helpful part of the vulnerability assessment was learning how to run automated
scans and interpret the results. It helped me understand how real-world software is audited
and improved. I also found creating and managing the keystore and certificate a little tricky
at first, but it gave me valuable hands-on experience with SSL.
To increase security layers, I used HTTPS for secure transport and SHA-256 hashing for
data integrity. If I were to continue this work, I would consider adding input validation,
role-based access controls, and using automated SAST tools for deeper scans.
To ensure the application was secure and still functional, I ran tests after every refactor and
checked the console and browser for successful HTTPS connections. I also re-ran the
dependency check report to confirm that I hadn’t introduced new vulnerabilities after
making changes.

Some tools I used and will definitely use again include Maven, OWASP Dependency-Check,
and Java keystore management via the `keytool` command. These are valuable in any
security-focused development environment.
For a future employer, I’d highlight this assignment as an example of my ability to
implement secure communication, run vulnerability assessments, and follow secure coding
practices. It demonstrates both technical implementation and the documentation skills
needed for real-world software development.
