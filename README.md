# RESORT-BOOKING

#### Video Demo:  https://drive.google.com/drive/folders/1QZJaXyKdlwpYmT-2MBxhU2cA4iHU5dj1?usp=share_link

#### Description:
**DIGITAL booking**
it helps to book the resort through online 

**INDIVIDUALS/ORGANIZATIONAL**
Stand-alone pilots who use or wanted to use services for themselves only. And Pilot eLogbook provides them a full-featured platform without any cost.
Those Aviation institutes willing to move their pilot logbooks from physical to the next level on virtualization want a web system for their instructors, students, and administration pilots. Our system hosts its services for them and at a minimal cost.

**FEATURES & SERVICES**
*Common features:*
- A professionally designed physical book-like interface.
- Log filter capability, based on dates.
- Single page log insertion panel.
- Fast and flexible data retrieval.
- Automated embed time calculator.
- Inserted log modification panel.
- Total flight hour summary.
- Plane flight summary of each month.
- Security verification sheild.

*More on Organization:*
- Admin contol panel.
- Create/Drop administrator rules over other pilots.
- Complete control over under-company pilots.
- Strong security handling.
- Private controls and features.

**WHY TO BE DIGITAL**
*TOP 5 REASONS*
Here are 5 reasons using an electronic logbook.

1) Save Time:
Flying is a challenging and tired but dreamed career, with such tiredness, filling in line after line of a logbook by hand, checking and rechecking math was a hated and not part of the dream phase! With a digital logbook, no more pen, calculator, and the instructor is required to fill up those fields. You need to grab your smart device, open Pilot eLogbook, and write an hour, enjoy the rest of the day.


2) Keep Secure Backups:
Every pilot needs a backup of a provided logbook. One of the biggest reasons to choose a digital logbook is its ability to keep log data secure, private, and for easy retrieval or as a backup. Many disasters could occur with a physical logbook like fire, drop, stolen, and more. If pilot's flight time is only recorded in a paper logbook, they are putting themselves at risk of losing the entire record of their career.

3) Easy Organize and Filter Records:
The thing which the world majority, even Pilots hate is mathematics, and calculations. There are maximum chances that you(Pilot) may fail to perform a correct calculation in hour count before writing it on a hard logbook. That is the primary reason why electronic or Pilot eLogbook is here to do all those irritating calculations accurately and quickly. Furthermore, you(Pilot) can filter monthly flight summaries in an organized way through search.

4) Accuracy, Legality, and Safety:
Keeping track of flight hours is so important, but the more important thing is to keep data accurate, organized, and private from third parties. Electronic logbooks keep track of these points to make their system a better platform for its users.

5) Soft Professional Reports:
The Pilot eLogbook system is automated to generate monthly reports for users(Pilots). The system generates reports based on monthly flight summary, aircraft flown, day rating, night rating, single-engine rating, multi-engine rating, and more and allows them to download the professionally generated report.


#### Files & Folder Description:
**web24access.php:**
This file contained database access credentials and connection code to link with phpmyadmin to gain and provide permission to database use for other files and website codes.

**index.html:**
Is a responsive and attractive page for users to interact. It's a homepage for this web application which provides full description about the site like what, who, and why Digital Logbook is important and benificial. It also vae multiple buttons to lead users to a login page named (page2.php) in this project.

**licensce.html:**
Is a navbar item file which contains information regarding the license description and requirements that suits best with the Pilot e-logbook uses.

**project.html:**
This file has all required description about this project, including a server required to host this.

**term&cond.html:**
All terms and conditions of the website uses for staffs and users are written here.

**script_one.js:**
Contains all the javascript functionalities and methods to check inputs, validate fields, and feedbacks. Functions with names started with word *__method__* followed by number words like (*one, two, three, ..., five*) indicates its field position whose functionality this method performs. For example 1st field in the registration is **Username** then its funtion in *js* will be **methodOne**, and similarly for all other fields and functions.

**/css (folder):**
Contains all the required styling and designing text code to make website attractive and responsive for the users.

**page2.php:**
Is a login/Sign in page for a user, it contains two (2) fields username and password to validate user input from a database and grant access to it's panel in this application. It also contains couple of URLs for *forget password* and to *sign up* for a new or returned user.

**data1.php:**
Is a registration handling file page which takes all required information from a user to establish his/her logbook panel in an application. Fields this file contained/handes are Username, FirstName, LastName, FullName, Email, Password, ConfirmPassword, and Serial. Serial is a special 25 character key only provided by an administration to make a new or existed user a new admin. Field data insertion query also ran from code this file has. Just after successful query data insertion this page passes email address to a file named "buffer.php".
 
**buffer.php:**
Is a file which contained a useful code required to send an email to a registring user to confirm his/her identity before proceeding any further. It has only *php* code all call to next proceeding links. And if an email sent successfully then code calls the *rgCheck.html* file, else just prints an error message along recommendation to try again later.

**rgCheck.php:**
Cotains a field requied to be filled correcty by a registring user using a valid 5-digit code sent on his/her email for a validation of an account. If code doesn't match user need to enter again or try to resend whereas if its correct then this page leeds to a next file "data3.html" where a **congratulation** message prompted for a user. This file is also checks the required query when a registred i=user attempt to *forget password*.

**reset_pass.php:**
It a singular field queried web page that takes a user email address to verify it from a database and then allow user to edit his old/forgotted passward.

**reset.php:**
Is a file which contains fields just like a registration page but here those fields are duly filled and has some editable input filed to edit information like *password, full name, & serial*.  It has a php code which executes a UPDATE query to update fields modified by a user.

**dashboard.php:**
Every normal (Student/Not Admin) user is proceeded to this page where they get all information about their flights, hours, total hours, location, time, day, and more. It's a core file which contains a hihly important queried php code, a lots of querries are written here to check user table in a database, to count their total number of hours they flown, and more and more from a database. But if a logged in user is of type admin then query will be executed to identify its exista=ence in a database and after a correct validation an additional clickable bar with a text *Admin Panel* start appearing at the top. 

**admin_panel.php:**
Is a page where an admin/s can only get access where they can grant or revoked privilliges to and from other users. They can block users, can make admins, or revoke admin access of other users. Additionally, they can also view everyone uploaded logs of all time **but** are not allowed to modify those fields. 

**profile.php:**
It a simple page which prompts a logged in user details to a user to check either they are correct or not.

**loginsertion.php:**
This page is also a highly php coded page which takes about 20+ inputs from a user regarding their log information they are uploading and apply query on that data to insert them in a correct table successfully.

**modify.php:**
Is a file where user validated before for his/her DELETE log action. It's important to keep log data secure that's why application is designed in a way that if someone even an actua user request to delete inserted log he/she need to veify their account using a password befor this ammendment takes place.
 
**modify2.php:**
Is a page presented to a user where a user edits already entered logs to make corrections if happened.

#### Conclusion
Pilot eLogbook is a cloud project designed to serve as an online logbook service to aviation pilots. It helps the Pilots to log their flight information, including arrival, departure, date, time, destination, and more. Our cloud server will hold their data and keep it safe and secure from online threats and attacks. The AWS cloud server services will use highly skilled programming techniques to make this server system a secure place for data and its use. An application service that will provide will available for all types of platforms. So, everyone (pilots) can access and use it from any place at any time. Moreover, This system feels like a spreadsheet but serves as an online application like myflightbook, or flylog. However, this application allows the pilots individually and companies to log flights here in addition to these types of existing services. The cloud server will allocate the database access to them to log their flight information. Company pilots can access the service by paying an instructor(admin) and the second as a student. In contrast, individual pilots can access server services by themselves and free of cost to insert, update, delete, and check their logs.

<------------------------------------END------------------------------------>