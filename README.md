# Software-Security

![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) | Developer: Justin Starr

# Hello, and welcome to the Software Security Repository of my Academic Projects🖐️

Developed secure code that complies with security testing protocols and learned encryption technologies and techniques for communicating securely. Assessed security vulnerabilities and mitigation strategies.

# 📖 Table of Contents

Project One: M3 Directory <br>
Project Two: M7 Directory <br><br>

> 📌 M2/ Dependency checking and mitigation reporting 👉 [Link 🔗](https://www.github.com/JustinStarrSNHU/Software-Security/tree/main/M2)<br>
📌 M3/ Project One: Vulnerability Assessment Report 👉 [Link 🔗](https://www.github.com/JustinStarrSNHU/Software-Security/tree/main/M3)<br>
📌 M4/ Algorithm Ciphers 👉 [Link 🔗](https://www.github.com/JustinStarrSNHU/Software-Security/tree/main/M4)<br>
📌 M5/ Checksum Verification and Certificate Generation  👉 [Link 🔗](https://www.github.com/JustinStarrSNHU/Software-Security/tree/main/M5)<br>
📌 M6/ Modifying Vulnerability Reporting and Suppressing false positives 👉 [Link 🔗](https://www.github.com/JustinStarrSNHU/Software-Security/tree/main/M6)<br>
📌 M7/ Project Two and application files 👉 [Link 🔗](https://www.github.com/JustinStarrSNHU/Software-Security/tree/main/M7)<br>

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company that develops individualized financial plans for its customers, which include savings, retirement, investments, and insurance plans. Artemis Financial wants to modernize its operations. As a part of the success of their custom software, Artemis Financial wants to use the most current and effective software security. Artemis Financial makes use of a public web interface and seeks expertise about how to protect its client data and financial information. Specifically, Artimus Financial wanted to add a file verification step to their web application to ensure secure communication. When the web application is used to transfer data, they needed a data verification step in the form of a checksum. Secure communication mechanisms were implemented to meet their software security requirements and a production-quality integrated application that includes secure coding protocols was delivered.

# What did you do very well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

What was done well is that I was able to run dependency-check reports to identify what vulnerabilities existed in their application's code base. Based on the findings from the dependency-check report, I was able to implement corrective actions to ensure the delivered application was secure. The reason why it is important to code securely is that we do not want to expose sensitive data or critical information for both Artimus Financial and its customers. There do exist many ways attackers will attempt to gain access to or expose such sensitive data and by implementing secure coding practices and industry best standards, these types of attacks can be protected against. Not protecting this type of information can lead to significant costs to Artimus Financial. Secure communications are of extreme value. Artemis Financial handles sensitive information for its clients. Because of the handling of sensitive information, Artemis Financial must treat security and its associated risks with high regard. Implementing secure communication measures, such as the use of a RESTful API, is paramount for ensuring secure and reliable client/server connections and transfers of information.

# What part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the vulnerability assessment was ensuring that I had addressed all of the appropriate areas of security that needed to be reviewed in the Artemis Financials application. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

One way that layers of security were increased was by generating a keystore and certificate that could be used to validate that the data did in fact come from Artimus Financial. Additionally, I made sure to make use of the Secured Hyper Text transport protocol which helps to ensure secure communication. Also, a RESTful API was used to establish secure communication and ensure secure transmission of data.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I was able to ensure the software application was functional by testing the application on the localhost to ensure the code generated a checksum. Additionally, when implementing SpringBoot into the application, a JUnit test was created that tested both the SpringBoot application and its rest controller. Updating SpringBoot to a newer version ensured that the application was secure and less susceptible to known vulnerabilities. To ensure my code did not introduce any new vulnerabilities, I utilized an OWASP plugin where I was able to run a dependency-check report to determine the number of vulnerabilities the software had before I introduced the new code. Then, after introducing the new code, I could run a secondary dependency-check that would then show me if I had added any new vulnerabilities to the report. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

One tool that was used that will certainly be helpful in future tasks is the keytool. Additionally, resources provided by Oracle Corporation were utilized to help determine an appropriate algorithm cipher. Also, in the future, it will be beneficial to continue implementing SpringBoot and rest controllers to ensure secure client/server communication and transmission of data.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would likely want to show that I was able to successfully use the keytool to implement a certificate for the web application. Also, I would want to show that I was able to write code that made use of an appropriate algorithm cipher and that my code was able to generate its associated checksum and display it in the web browser. I would also want to show that I was able to establish a secure connection that made use of the HTTPS protocol. It is essential that I am able to identify areas of security as it concerns any application I develop and address any vulnerabilities that are identified throughout its development.