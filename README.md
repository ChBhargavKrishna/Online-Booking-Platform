# 🌍 Online Booking Platform Project
![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-1.jpeg)

[Online Booking Platform](https://github.com/ChBhargavKrishna/Online-Booking-System) developed using Java and Spring Boot that allows users to register, log in, book slots, and manage their bookings. The application enforces authentication so that only registered users can access booking features. This is a Full Stack web responsive project is made by using SpringBoot, Javascript, Css Jsp.This is a full-stack, responsive web application build with Spring Boot, JSP, and Oracle DB that allows users to book car, flight, and bus tickets. It features two modules — Admin and User — each with its own functionalities and access control. This project has two modules i.e Admin and User Modules. Each module has distinct responsibilities in the project. Best Services also mentioned and taking feedbacks and 24/7 contact support also available.

## Pages Include

| Login Page | Register Page | Admin Dashboard Page | User Dashboard Page |
| -------| -------| -------| -------|
| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-2.png) | ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-3.png) | ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-4.png) | ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-5.png) |

## 📌 Features
- User registration and login
- Authentication-based access to booking features
- Online booking creation
- Booking cancellation by users
- Slot availability management
- Clean layered backend architecture
- Form validation and error handling

-----------------------------------------------

## 👥 Module Features
In this two modules are present They are
1. **👨‍💼 Admin Module**
 - Login Authentication (No registration).
 - CRUD Operations For Bus, Flight and Car.
 - View Payment Details of User Total Booked count including Bus, Flight and Car.
 - Fetching all complete details of registered Users.
 - Admin has only one credentials that should be inserted into table by below command with that details only Admin can make operations of above all.
      
      | Insert Command | Description | 
      | -------| -------|
      | `INSERT INTO login VALUES('admin12@login.com', 'admin12');`| Inserts admin credentials into the database |
      | `COMMIT;`| Saves the changes (shows `Commit complete`) |

      ## 📸 Admin Module Screenshots
| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-4.png) | ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-6.png)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-7.png)| 
|--------------| --------------|   --------------|     
|  ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-8.png)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-9.png)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-10.png)|

2. **🙋 User Module**
 - Users must first register and then log in with email and password credentials and have user profile that can be edited.
 - Booking implementations for Bus, Flight and Car Based on his Requirement.
 - User can search for Bus and Flight seats Past travel dates are not allowed; only present or future dates can be selected.
 - User can add Card Details for better experience. Each user can add one card that is saved in database and it is saved card by this card payment can be done.
 - Payment Operation for booked seat (either Bus or Flight) or booked Car. Not a real payment gateway; just saves data in the database.
 - User can cancel his booking before the travel or depart date. Also for Booked cars can cancel for partial cancellation and Amount updated or Full cancellation also available.
 - User can change his/her password and View Booking History of his/her booking for Bus, Flight and Car.
 - Best Services also mentioned and taking feedbacks and 24/7 contact support also available by the help page. 
    
     ## 📸 User Module Screenshots
| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-5.png) | ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-11.jpeg)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-12.png)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-13.png)|
|--------------| --------------| --------------|  --------------|  
|  ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-14.png)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-15.png)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-16.png)| ![](https://github.com/ChBhargavKrishna/Online-Booking-System/blob/new-branch/Screenshots/Screenshot-17.png) |

## 💻 Tech Stack
- Backend: Java, Spring Boot, Spring MVC
- Database: Oracle 10g
- Frontend: JSP / HTML / CSS
- Authentication: Session-based login
- Tools: Git, Eclipse / STS
- Dependency Management: Maven.
- Server: Tomcat 10.1

## Application Flow
1. New users must register before accessing the system
2. Only registered users can log in
3. Logged-in users can:
   - Create new bookings
   - View their bookings
   - Cancel their own bookings
4. Unauthenticated users cannot access booking features

## 🧠 Backend Architecture
The application follows a layered architecture:

Controller Layer  
→ Handles HTTP requests and responses

Service Layer  
→ Contains business logic and validations

Repository Layer  
→ Manages database operations using JPA / JDBC

## 🔒 Security
- Authentication is implemented using login and registration
- Only authenticated users can perform booking operations
- Authorization is enforced at the application level

## 🚀 How to Run the Project
1. Clone the repository
2. Import the project as a **Maven Project**.
3. Configure database credentials in application.properties `application.properties` file with your Oracle DB credentials:
      | **Edit your Oracle DB details** |
      |-----------------------------|
      | `spring.datasource.url=jdbc:oracle:thin:@localhost:1521:orcl` <br> `spring.datasource.username=your_username` <br> `spring.datasource.password=your_password` |
4. Run the Spring Boot application
5. Access the application via browser

## 📚 Table of Contents

- [📝 Project Overview](#-online-booking-platform-project)
- [📄 Pages Include](#pages-include)
- [📌 Features](#-features)
- [⚙️ Module Features](#-module-features)
- [📸 Screenshots](#-admin-module-screenshots)
- [💻 Tech Stack](#-tech-stack)
- [✍️ Application Flow](#application-flow)
- [🧠 Backend Architecture](#-backend-architecture)
- [🔒 Security](#-security)
- [🚀 to Run Project](#-how-to-run-the-project)
- [👤 Author](#-author)
- [🔗 Connect Me](-connect-with-me)
- [📜 License](#-license)

## 👤 Author

**Chiruvolu Bhargav Krishna**  
Java Backend / Full Stack Developer  

- 💻 Skilled in **Java, Spring Boot, JSP, SQL, Oracle DB**
- 🧩 Strong understanding of **MVC architecture & RESTful design**
- 🚀 Passionate about building **scalable, real-world applications**
- 📚 Actively improving **DSA & problem-solving skills**

### 🔗 Connect with Me

[![GitHub](https://img.shields.io/badge/GitHub-BhargavKrishna-black?style=for-the-badge&logo=github)](https://github.com/BhargavKrishna)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/chiruvolubhargavkrishna/)
[![LeetCode](https://img.shields.io/badge/LeetCode-BhargavKrishna-orange?style=for-the-badge&logo=leetcode)](https://leetcode.com/u/kbhargav285/)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Thank You
![Thank You](https://img.shields.io/badge/Thank%20You-🙏-green?style=for-the-badge)

We appreciate your time and interest in this project.

If you found it helpful, feel free to ⭐ the repository or contribute!
