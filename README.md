3 Specific
Requirements...............................................................................................................................................................................................................4
3.1 External Interface
Requirements...........................................................................................................................................4
3.2 Functional Requirements.......................................................................................................................................... 4
3.3 Use Case
Model............................................................................................................................. 5
4 Other Non-functional
Requirements.............................................................................................................. 6
4.1 Performance
Requiremen................................................................................................................. 6
4.2 Safety and Security
Requirements.............................................................................................................. 6
4.3 Software Quality
Attributes...................................................................................................................... 6
5 Other
Requirements.............................................................................................................. 7

Appendix B - Group
Log.................................................................................................................................. 9
<br><br><br>

# **3 Specific Requirements**

## **3.1 External Interface Requirements**


### **3.1.1 User Interfaces**
* The website should work and be tested against Firefox and Google Chrome.
* The website should be responsive on different devices
### **3.1.2 Hardware Interfaces**
* There are no special hardware interface requirements.
### **3.1.3 Software Interfaces**
* Software requirements of the system are very nominal and no other special requirement
is there hence it is economically feasible.
## **3.2 Functional Requirements**
#### **●  Administrative access for the department head**
  The department head will have a special login page where he has special credentials to
  login which enables him to have administrative access to the entire platform. Which
includes resetting passwords of any account, direct access to the front page
announcements and administrative access to the database.
#### **● Account registration for students and staff**
Every user will use the institutional email or ID to login to the website. The website will
fetch the full name from the institutional email and use it as a username.
#### **● Announcement page of the departement**
The department will be able to announce events,seminars ,schedules or any major news
.This will solve the hurdle of information inaccessibility for the department and its staff.
#### **● Give a tour of the software department facilities**
The website will have a section where students or staff members see all the available
resources, facilities and offices available to them inside the department. Supported with
high quality photographs, users will view the labs and resources available clearly.
#### **● Provide a description of the vision and mission of the software department**
The description of the department vision and mission will be briefly mentioned.In addition
to its objectives and it’s approach to reach these objectives and it’s future position in the
university and for the students will be included.
#### **● Display the location of the department and it’s facilities**
Since AASTU is very wide, it's pretty easy to get lost. And even after years of exploring
it’s wide compound you may not know where certain buildings and offices are. So the
website will provide the locations of these important offices and facilities in a clear
manner.
#### **● Resource sharing page**
In this page ,the course materials and recommended suggestions for the entire batch will
be listed (Written source, Audio-visual aids, e-learning/technology, Objects, Events, and
People etc) that can be used to support or help Teaching and Learning.
#### **● Course plan and schedule for all batches throughout their academic years**
Most students are curious to find out what they’ll learn the semesters and years ahead.
So we’ll provide a page where all the subjects that will be taught throughout the 5 years
of software engineering. This will include the names of subjects, resources they’ll use,
credit hours and so on.
#### **● Question and Answer forum for the students with the staff**
Due to communication gaps both staff and students suffer to communicate.This page will
give a platform for the staff and students to directly be in touch thereby eliminating any
miscommunication or hurdles.
#### **● There will be a page specifically tailored to every use case(Admin, Staff, and Students)**
#### **Admin page**

* The department head is the sole user of this page. It will enable the admin to grant or
revoke access to other users.
* Capable of overseeing all activities and users within the website.
* Post announcements.
* Pin-approved schedules.
* The override option will be listed.
* Activity history will be laid out.
#### **Staff/teacher page**

* It’s only available for staff members.
* Displays teacher’s corresponding classes, students, and schedules.
* Alternative to answer Q&A will be shown.
* There will be a privilege to post course materials.
#### **Student page**

* Every student will have this page.
* They will have access to their course, schedule, and teacher’s profile.
* In addition, they can ask questions on the Q&A page and surf the website.
<br><br>
## **3.3 Use Case Model**
<br>

![usecase.png](https://imgkub.com/images/2022/03/10/usecase.png)
<br><br>
### **3.3.1 Use Case #1 (Departement head)**
<br>

#### **Purpose** - The admin will be able to gain access to all accounts in the database and will be able to
oversee all activities within the website.
#### **Requirements Traceability** – Email, employee id, password, and activity history.
#### **Priority** - High priority
#### **Preconditions** -The website must be fully functioning with an accessible database.
#### **Postconditions** - This account should be able to override and must have access to the entire structure
of the website.
#### **Actors** – It can be opened on any digital device with administrative email and password
#### **Flow of Events** -
On a sign-in page, the department head will enter an admin email and password which will then proceed to the administrative page.
<br><br>

### **3.3.2 Use Case #2(staff/teachers)**
<br>

#### **Purpose** - In this case, teachers can communicate with their students directly , have a sense of what’s
going on in the department, and post any helpful materials,
#### **Requirements Traceability** – Employee ID, Institutional email, password.
#### **Priority** - Medium priority
Preconditions - Registered staff email and password while the website is functioning.
#### **Postconditions** - Teachers will be able to access students and answer any questions on the Q&A
page. They will also be able to post learning material and class schedules. In addition, they can surf
the website
#### **Actors** – Teachers can access their account on any device provided that they have valid email and
password.
#### **Flow of Events** - Upon logging into the staff page, a staff member can use the website to post materials, check out the announcements page, or answer questions on the Q&A page.
<br><br>

### **3.3.3 Use Case #3(Students)**
<br>

#### **Purpose** - Students will use the platform to access all the resources available to enhance their
studying and learning skills. They will also use it to ask questions and get helpful feedback from the
staff and other members.
#### **Requirements Traceability** – Institutional email, password, username and ID number
#### **Priority** - High
#### **Preconditions** - Students must activate their institutional emails to be able to access this website well
#### **Post conditions** - Students will be able to search for resources, view their entire academic year
calendar. View the locations of important facilities and be able to interact with other students and
teachers in a forum like chatroom.
#### **Actors** – Students can access the website through any device with a browser as long as they have an
activated and valid institutional email
#### **Flow of Events**
#### &nbsp;&nbsp;&nbsp; **Basic Flow**
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a. Student Login which will redirect to the homepage if login is &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;authorized.
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. View homepage where announcements are posted
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. Access chatroom to ask questions
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. Academic access which leads to resources and academic &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;calendar.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
e. Access locations of basic facilities, labs and offices.
<br><br>
# **4 Other Non-functional Requirements**
## **4.1 Performance Requirements**

* The website should be hosted on a server that can respond quickly enough. Due to the
short attention spans of high school pupils, a sluggish server would be unsuitable for this
application.
## **4.2 Safety and Security Requirements**
* There are no special safety requirements
* Copyright and other security measures for college websites should be the same
as the AASTU site.
## **4.3 Software Quality Attributes**
Web design conventions should be consistent with the minimal and modern website design
principles.
<br><br>
## **Appendix B - Group Log**
***
To produce this document we formed a team of 6 members to spread out and interview key
figures in the department. This includes teachers (mainly focused on programming and
database teachers), registrar head and finally the Department head.
We then had to set up a meeting to compile and organize all the interview recordings and notes
to select out all the functional and nonfunctional requirements.
After a lengthy process of selecting and agreeing on the contents and features to be included
we headed to Google Docs and created a document to be shared with the team so everyone
can read, work and evaluate the document simultaneously.
Finally we all gathered up for the editing and finishing work and finished working on this
document.






