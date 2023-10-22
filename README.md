# CS-305

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that provides financial plans for thier customers. these financial plans include savings, retirement, investment and insurance plans. Artemsis Financial is looking to add security to thier web application. Specifically, a file verification step to ensure secure communications and data verification incoporating a checksum.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I did a good job at researching the possible solution to these vulnerabilities and how to implement them. It is important to code securely to not only follow regulations but protect consumer trust. Software security protects company's from costs associated with liabilities associated with security breaches as well as other costs while also making the product or service more marketable due to increases consumer trust.

# What part of the vulnerability assessment was challenging or helpful to you?
The most challenging part of the vulnerability assessment was researching the vulnerabilities resulting freom the dependencies in use and how to implement a solution to each.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I added HTTPS to secure communications using a self-signed certificate. I implemented SHA-256, to protect the integrity of the data being tranferred as well.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I ensured the code and software application was functional and secure through manual and static testing both before and after refactoring to ensure i didnt add any additional vulnerabilities after addressing the original ones./

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used OWASP Dependency Check to check the maven dependencies used by the application for vulnerabilities. This will continue to be a helpful tool in the future when continuing to use maven.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show future employees my understanding of the process of conducting a vulnerability assessment and applying solutions to these vulnerabilities found. Also my ability to prodce a clean record and report of the process.
