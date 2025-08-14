# SpringBoot Social Network Project

This is a full-featured social networking platform developed using **Spring Boot** and related technologies. It provides core social features like user profiles, friend management, private messaging, and admin controls, along with scalable deployment setups using Docker and CI/CD pipelines. The application is designed with a modular architecture and is production-ready for deployment on Heroku or similar platforms.

The project was developed to demonstrate expertise in **Java (Spring Boot)**, **full-stack development**, **database integration**, **security**, and **real-time application features**.

---

## Core Features

- **Authentication & Profiles:** Login, Logout, User Registration, Profile viewing (self and others), Profile editing, Password change, Profile image upload (drag & drop).  
- **Social Features:** Add/Remove friends, Accept/Decline friend requests, View friends list, Search for users, View last messages.  
- **Messaging:** Send and receive private messages.  
- **Internationalization:** Supports English and Russian languages.  
- **Admin Controls:** Promote a user to admin, Block users (super admin accounts cannot be blocked).  

---

## Technologies Used

- **Languages & Backend:** Java 11, Spring Boot, Spring MVC, Spring Data JPA, Spring Security, Spring DevTools, Spring Actuator  
- **Frontend:** Thymeleaf, JavaScript, jQuery, HTML, CSS, Bootstrap  
- **Databases:** H2 (dev), MySQL (qa/prod), ClearDB (Heroku)  
- **Build & Tools:** Maven, Docker, Heroku (CD), CircleCI (CI)  
- **Testing:** JUnit, Mockito  

---

## Deployment & Profiles

- **dev** – Development with embedded H2 database  
- **qa** – QA testing with MySQL (local or Docker container)  
- **prod** – Production on Heroku using ClearDB MySQL  
- **docker** – MySQL + Spring Boot app containerized and linked  

---

## Setup Instructions

1. Install **Java 11** and **Maven**.  
2. Clone the repository:  
   ```bash
   git clone https://github.com/SurajeeKumar22aib47/SpringBoot-SocialNetworkWebApp.git
mvn clean package -DskipTests=true
cd web.social.network/target
java -jar -Dspring.profiles.active=dev social-network.jar

**Conclusion**

This project demonstrates expertise in Java development, full-stack application design, and deployment. It showcases the ability to deliver scalable, secure, and feature-rich applications ready for real-world use.
