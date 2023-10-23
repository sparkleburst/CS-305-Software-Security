# CS-305-Software-Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was this client? What issue did they want you to address?

Artemis Financial is a consulting company specializing in individualized financial plans. This could mean any combination of savings, insurance, retirement, and investments. Artemis Financial wants Global Rain to enhance the security of its web application. They need secure communications and the transference of client data.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

It was easy to implement the Maven Dependency Check into the POM file. Running the dependency checks is crucial for correcting coding that may be susceptible to attacks and has already been identified. Coding securely is important to preserve the integrity and intended usage of your application. When a company's application is secure, customers should never have to hear that their data has been compromised. Average users most likely do not seek out why a site is secure, they tend to assume data is handled honestly. Because of this, a company typically suffers once users are alerted to a security breach.

What part of the vulnerability assessment was challenging or helpful to you?

The Maven check was useful and worked with no issues. Interpreting the CVE codes was the challenging part. Determining false positives would lead to new CVEs appearing.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Layers of security were increased by following best practices for coding using Maven. Encryption and HTTPS were also added to ensure sites were secure and cross-site scripting and other forms of attacks would be practically impossible. I used the Maven Dependency checks to find vulnerable dependencies and followed each link to find mitigation methods.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

The code was functional when it ran without errors. The code was found to be secure by checksum testing for encryption efforts and verifying a secure connection by way of a lock symbol in the address bar. This lets you know you know you are connected via HTTPS and there is a valid certificate. If the code needs to be refactored then after refactoring the code, running a new dependency check will find any new vulnerabilities.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The Springboot application is something that I am sure I will be using in the future. I am sure I will use plug-ins, such as Maven, as this is a powerful tool that quickly shows problems that may occur from using third-party libraries.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would say I have a fair understanding of software security based on certificate authorities, encryption software, vulnerability assessments, and more. I am able to show that I can implement Maven and scan for vulnerabilities. I know how to create certificates and keys, and can see how they interact to provide secure communications. 
