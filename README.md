## Lab-1_202001246
                                                                   IT-314
                                                       IT314-Software Engineering Lab-1
                                              Identifying Functional and Non-Functional Requirements
                                              

Name:Milind Patel

Student Id: 202001246

Date:03-02-2023

Library Information System (LIS)

***
**Q.1. Identify FRs and NFRs:**


- **Functional requirements:**
  
  - Login for Users: User must sign up for the LIS. There are the three types of users. Members, Librearians, and non-members

  - librarians to add,update,delete books/articles in the database and check availability of particular items. 

  - The librarian, who has administrative privileges and complete control over the system, can enter a new record into the system when a new book has been purchased,       or remove a record in case any book is taken off the shelf.
  
  - The  member can extend the date of his borrowing if no other booking for that  particular book has been made.

  - Any non-member is free to use this system to browse/search books online. However, issuing or returning books is restricted to valid users (members) of LIS only.
  
  - LIS must have information about all checked in/out books and reminders before returning.
  
  - LIS must support a multi request without issus.
  
- **Non-functional requirements:**

  - LIS system is web application and It is made with HTML5 .
  
  - Hardware Constraints :
    The system requires a database in order to store persistent data. The database should have backup capabilities. 

  - Security:
    Only librarians are allowed to enter new records and have full administrative access to the system. Data shouldn't be exposed.

  - Scalability:
    When necessary, the system need to be able to grow its user base and accommodate additional users.If there are numerous libraries, the data should be scalable and     kept in a database such that it is accessible from each library.so, data should be scalable. The system should be such that it can be trusted upon considering that it has a huge amount of data.
    
 **Q.2. Identify scope, features and non-functional aspects of the following problem.**

- **Project Scope**

  - Planning:
    creating a system that can recognise loud noises and notify the user right away.
    
  - Controlling:
    First, we offer a simple system design. The design is then put into practise to create a real working system. Depending on our results, we might or might not take     the alterations into account.
  - Closing:
    We do a detailed assessment of our final system with the one that we had planned to design.  
    
- **Functional requirements:**

  - Recognizing high volume sounds.
  - Alerting the user based on the sounds.
  - This app is optimized for Android with low-latency so that it works in real-time for use.
  - AI enabled with strong sense of recognizing the sounds of car horns etc.
  - Application should have a request and feedback section to understand more about the user.

- **Non-functional requirements:**

  - Hardware Constraints :
   The system requires a database in order to store persistent data. The database should have backup capabilities.

  - Reliability:
    The system should be dependable in terms of sending alerts to users at the appropriate time.

  - Security:
    The personal data of users should remain secure within the system.

  - Performance:
    The system should function at a high level by providing the user with precise alerts. Only when necessary, and not in response to every sound heard, the system         should notify the user.

  - Scalability:
    We must try to scale the system to each individual for their safety and security, as it has been stated that approximately 5% of the world's population suffers         from hearing loss.   
    
    
    










