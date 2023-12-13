# CS305-PROJECT 1

- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  - Artemis Financial is a consulting company specializing in individualized financial plans. They sought to modernize their operations and enhance the security of their web-based software application, which includes handling sensitive financial information. The      client's primary concerns were secure communications, international transactions, compliance with governmental restrictions, and protection against external threats.
- What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  - I did well at identifying current vulnerabilities in the code base through the use of static testing. Secure coding is important to prevent data theft and to protect the company's reputation of integrity and reliability.
- What about the process of working through the vulnerability assessment did you find challenging or helpful?
  - One challenging aspect was addressing third-party library vulnerabilities identified through static testing. However, this process provided valuable insights into potential risks associated with dependencies and highlighted the importance of keeping libraries up to date.
- How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
  - In the future, a combination of manual review, static testing, and penetration testing would provide a more comprehensive assessment.
- How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
  - It was necessary to re-run the dependency check if new dependencies were added. Otherwise, unit testing and manual code review can ensure functionality.
- What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
  - The integration of the dependency-check plug-in, manual code review practices, and the adherence to secure coding principles are valuable resources.
- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  - For future employers, I would present the vulnerability assessment report, demonstrating the ability to identify and address security vulnerabilities in both code and third-party libraries
