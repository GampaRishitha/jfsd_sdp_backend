
---

# **JFSD SDP Backend**  

## **Overview**  
This project is the **backend system** for the JFSD SDP application, built using **Spring Boot** and **Hibernate**. It provides RESTful APIs for managing various functionalities, including user authentication, artwork management, and payment processing via **Paytm Payment Gateway**.  

## **Key Features**  
✅ **User Authentication** – Secure login and signup.  
✅ **Artwork Management** – CRUD operations for artwork records.  
✅ **Payment Integration** – Paytm payment gateway for transactions.  
✅ **Database Management** – Uses Hibernate with **PostgreSQL**.  
✅ **REST API Implementation** – Well-structured endpoints for seamless frontend integration.  

## **Tech Stack**  
- **Spring Boot** – Backend framework  
- **Hibernate** – ORM for database interaction  
- **PostgreSQL** – Relational database  
- **Express.js & React** – Client-side interaction (if applicable)  
- **Paytm Payment Gateway** – Secure payment integration  

## **Installation & Setup**  

1️⃣ **Clone the repository:**  
```sh
git clone https://github.com/GampaRishitha/jfsd_sdp_backend.git
cd jfsd_sdp_backend
```
2️⃣ **Configure the database:**  
- Update **`application.properties`** with PostgreSQL credentials.  

3️⃣ **Build and run the project:**  
```sh
mvn clean install
mvn spring-boot:run
```

## **API Endpoints**  
### **User Authentication**  
- `POST /api/auth/signup` – Register a new user  
- `POST /api/auth/login` – User login  

### **Artwork Management**  
- `GET /api/artworks` – Fetch all artworks  
- `POST /api/artworks` – Add a new artwork  
- `PUT /api/artworks/{id}` – Update artwork details  
- `DELETE /api/artworks/{id}` – Remove an artwork  

### **Payments (Paytm Integration)**  
- `POST /api/payments/initiate` – Initiate a payment  
- `POST /api/payments/verify` – Verify payment status  

## **Repository Structure**  
📂 **jfsd_sdp_backend**  
 ├── 📁 **src/main/java** → Backend logic & controllers  
 ├── 📁 **src/main/resources** → Configuration files  
 ├── 📄 **pom.xml** → Maven dependencies  
 ├── 📄 **README.md** → Project documentation  
 ├── 📄 **application.properties** → Database & API configs  
 ├── 📄 **jfds_sdp_backend.sql** → Sample database structure  
 └── 📄 **PAYTM.md** → Paytm integration guide  

## **Contribution**  
Contributions are welcome! You can:  
✅ Optimize database queries  
✅ Enhance security features  
✅ Improve API performance  

## **License**  
This project is open-source and available under the **MIT License**.  

## **Contact**  
For queries or collaboration, reach out via **GitHub Issues** or email.  

🚀 **Happy Coding!**  

---
