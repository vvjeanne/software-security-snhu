# software-security-snhu
A portfolio of projects completed and progress made throughout CS305 at SNHU

<br>Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
<br>Artemis Financial is a financial services company that needed a secure, modern RESTful API to handle highly sensitive client data like investments and retirement accounts. The main issue was addressing significant security risks, like outdated dependencies, lack of encryption enforcement, and missing authentication, that could expose confidential data and compromise the system. 

<br>What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
<br>I did well in thoroughly identifying both code-level and dependency-based vulnerabilities, such as outdated libraries, hardcoded credentials, and missing input validation. Secure coding is critical because it prevents breaches and protects sensitive data, ultimately preserving customer trust and reducing financial and reputational risk for the company.

<br>Which part of the vulnerability assessment was challenging or helpful to you?
<br>One challenging aspect was interpreting the large number of vulnerabilities reported in the dependency-check scan and determining which were most critical to address first. However, this process was also helpful because it provided a clear, structured view of risks across the application and dependencies.

<br>How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
<br>I increased security layers by recommending updates to vulnerable dependencies, implementing input validation, enforcing authentication, and removing hardcoded credentials. In the future, I would use a combination of automated tools, like OWASP Dependency-Check and manual code reviews, to assess vulnerabilities and choose appropriate mitigation strategies.

<br>How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
<br>I ensured the application remained functional and secure by carefully updating dependencies and improving code practices without altering core functionality. After refactoring, I would rerun static analysis tools and perform additional testing to confirm that no new vulnerabilities were introduced.

<br>What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
<br>Key resources include OWASP Dependency-Check, CVE/NVD databases, and secure coding practices, like input validation and proper error handling. These tools and practices are valuable for consistently identifying and mitigating vulnerabilities in future projects.

<br>Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
<br>I could show the vulnerability assessment report, including the identification of the 152 vulnerabilities and the mitigation plan I developed. This demonstrates my ability to analyze security risks, use industry tools and apply secure coding practices to improve software security.
