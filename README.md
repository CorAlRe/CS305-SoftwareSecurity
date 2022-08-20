# CS305-SoftwareSecurity
CS-305 Software Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

For the project, a fictional client named Artemis Financial wanted a security assessment of their REST API.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I think I did very well with the code analysis over the Views, Models, Controllers, Data Access, and APIs. 
Secure coding is important as a protection against loss, both from regulatory fines, legal action against the client, and protecting the client's reputation with customers.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

The hardest part was identifying the appropriate compliance standards, the specific textual requirements, and how that applies to the client. The client was a financial investment company, and there are various requirements for protecting customer accounts from many different agencies.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

I approached security layers but identifying every step along the path between the client and the customer; securing the communication with encryption, returning minimal sensitive information, protecting access to information by authentication and authorization, not trusting data input, protecting data models, scrutinizing API dependencies, and protecting downstream systems like databases. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

After code reviews, I refactored the code to ensure it met standards, then I made sure it was functional through testing. I made sure the REST endpoint returned the required information and nothing else. I also implemented unit tests to ensure that changes to the REST controller continued to perform as expected.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The Java Dependency Check static analysis was very helpful in determining if the included code libraries were free of known vulnerabilities. In the future I would look for an equivalent analysis tool for other languages and projects.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would showcase the legal analysis as it translate into which areas of security that need to be covered. I feel that my analysis could be given to a lawyer for confirmation which would inform the client that the recommended security protections are are necessary cost.
