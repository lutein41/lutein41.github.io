
# OCCBio System Individual Project 

**Application Designer**: Ryan Park \
**Software Developer**: Ryan Park\
**Q/A Tester**: Ryan Park\
**Programming Language**: Java(1.8) and SQL\
**Build Tool**: Maven\
**IDE**: IntelliJ Community\
**Database**: 
* Relational Database Management System: MySQL(8)
* Storage Engine: InnoDB 
 
**Testing**: 
* Unit Testing: JUnit5
* Integration Testing: video 
  
---

## INTORUDCTION

For Anatomy and Physiology(AP) students, scientific human anatomy models are essential visual studying tools. However, I noticed that students can access these tools only during their lab period, which is about one and a half hours. Although students can lend the models at the college library, the library only has a small number of AP models. It would benefit students if the Biology department lent the models to students before exams. To identify the user's goals, problems, needs, requirements, and potential stakeholders, I used observation, semi-structured interviews, and research as my need-finding activity. After the needfinding activity, I designed a relational database model based on the user's requirements for a desktop application. 

## 1. NEEDFINDING
### 1.1 Interview

I developed semi-structured interview questions for instructors, librarians, and students. My core questions were asked for all participants, but each participant was asked different probing questions.
1.	Should our department lend the models to students?

2.	Who should be responsible for lending models (for instructors only)?

3.	Which checkout system do you prefer: digitalized form or paper form?

4.	How often do you lend the models from our library? (for students only)

5.	How do you use a paper model checkout form at the library (for librarians only)?\
&nbsp;a.	Can you explain to me why we use a paper form?\
&nbsp;b.	Are you happy about using a paper form?\
&nbsp;c.	What would you do if you lost the form?\
&nbsp;d.	Can you tell me which models are popular?\

I interviewed two instructors, one librarian, and three students.
### 1.2 Research

I searched news articles about the advantages and disadvantages of paper receipts over digital receipts. After reading some articles, I concluded that using a digital system for lending models is much better than using a paper checkout form. Here are some of the advantages of using a digital system:
1.	You can avoid losing a paper checkout form.

2.	You can manage inventory and students digitally. 

3.	You can use SQL database language to store and process information in a database. You can also use SQL for data analytics. For example, a lab manager might want to know which models are popular so that the manager can order more.\

Sources of news articles :
* https://www.cnbc.com/2014/01/23/paper-or-email-pros-and-cons-of-digital-receipts.html

* https://www.usatoday.com/story/news/nation/2012/11/03/retailers-e-mail-digital-paperless-receipts/1675069/

### 1.3 Problem Statement

From the needfinding activity, First, I concluded that students want to borrow models especially for their exams. Although one instructor states that young students (early 20s) prefer to use 3D software to observe human structures, 1/3 of students in AP classes are not young and like physical models. Students also like physical models for group discussion. Second, lab staff choose a digital system over a paper checkout form. 

## 2. DATABASE
### 2.1 EER Diagram
 ![EER Diagram](../../img/OCCBio_EER_Diagram.png)
### 2.2 EER to Relational Mapping
![EER_To_Relational](../../img/EER_Relational.png)
### 2.3 Flow Chart
![EER_To_Relational](../../img/OCCBio_Flow_Chart.png)

## 3. IMPLEMENTATION
I uploaded my application source code at my Github repository : [source code]().
## 4. TESTING
### 4.1 Unit Test
I used JUnit5 for the unit test. Please see my source code.
### 4.2 Integration Test and Demonstration
{{<youtube hu9Zm7IYtVI>}}
