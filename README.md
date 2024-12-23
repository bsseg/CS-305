# CS-305


Artemis Financial provides financial services, including insurance products, investments, retirement, and savings. In order to enhance their defenses against vulnerabilities, they desired to implement security enhancements to their RESTful web application. I was assigned the responsibility of enhancing the security of Global Rain's application as a client. They were justified in their desire to enhance the security of their financial data.


I acquired proficiency in the execution of dependency tests and the extrapolation of data from these reports to ascertain the areas of the code that require refactoring or upgrading. Additionally, I was able to suppress false positives in order to reduce the number of legitimate vulnerabilities that required attention. Coding securely is essential from the outset of the development process, as it is significantly simpler and safer to address vulnerabilities during the coding process than to revisit the product after it has been constructed and is in use. The program may have been compromised at that time. Hackers are increasingly motivated to attempt to access confidential information as we become more dependent on technology (Jena, 2022). In order to reduce the risk of unauthorized access and unnecessary loss of financials and public opinion, companies must implement effective security practices if they value their data and information.


Initially, I encountered difficulty in establishing a locally hosted server to evaluate the application. Another student in the course also encountered this issue. Before I could execute a Java application, I would need to execute a Maven build. However, this was not a problem when I transitioned to a different system for subsequent assignments. It is possible that there is a configuration on my original computer that needs to be examined to ensure that no further issues arise in the future. Initially, I also encountered difficulty in determining which of the VAPFD were to be the security aspects that were applicable to specific collections of code. I had previously believed that all aspects of the VAPFD were significant for all categories of code. However, as time progressed and I received feedback from my instructor, I was able to more accurately identify the specific security aspects that were pertinent to the situation.



In order to establish a more secure server environment, we implemented dependency checks, cryptography, and certificate authentication during this course. We were able to identify existing vulnerabilities that required attention through the use of OWASP. In lieu of employing plain text, we implemented SHA-256 messaged digest encryption to enhance the security of potential user input. SSL and HTTPS were implemented to authenticate connections between the server and consumers through certificate generation and authentication. I found the OWASP Dependency Check plug-in to be quite enjoyable and will likely continue to employ it in the future due to its comprehensive reporting and open source nature.


To guarantee the successful refactoring of the code, the program required the importation of Message Digest and Big Integer as additional tools. I was greatly assisted by the Errors panel, as it provided me with a clear indication of which lines of code required further examination. Eclipse has been exceedingly advantageous for this function, as it facilitates the development of functional code prior to any construction. In order to ascertain the total number of vulnerabilities, I employed the OWASP Dependency check both before and after refactoring and launching the application. I then compared the pre-factor report to the post-factor report. My refactor did not introduce new vulnerabilities if both had the same number of vulnerabilities and the same vulnerabilities enumerated.



As previously stated, the utilization of OWASP will prove advantageous in the future. Including the dependency check in the POM.xml file will be extremely beneficial for future code vulnerability checks. It will be beneficial to acquire the ability to generate self-signed certificates in order to test secure server applications. Without a doubt, the ability to implement the SHA-256 message digest cipher will serve to safeguard sensitive information that future users may input, as opposed to endeavoring to compare plain text values for validation.


In addition to sharing the knowledge acquired from this course verbally, I believe that the majority of companies prefer to administer a brief coding test to demonstrate one's abilities. They will request that you develop a brief program to showcase your proficiency in a specific subject or general skills. I believe that incorporating encryption and secure client/server properties into any form of code is likely to impress employers and demonstrate my commitment to security at all levels, regardless of whether it is tailored to software security or not. The ability to code securely from the beginning of the development process is a significant indicator of computer programming expertise and knowledge.


