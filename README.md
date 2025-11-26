# 🏨 Hotel Sambrano – E-Commerce Web Application

Hotel Sambrano is a complete e-commerce web application built using Java, JSP, Bootstrap, and PostgreSQL.  
The project simulates an online hotel platform where users can explore rooms, services, make purchases, manage their account, and administrators can manage the system through a control panel.

---

## 🚀 Technologies Used

### **Frontend**
- HTML5  
- CSS3  
- Bootstrap 5  
- JavaScript  
- JSP (JavaServer Pages)

### **Backend**
- Java  
- JDBC  
- PostgreSQL  
- MVC-structured package organization  
- Dynamic menu system based on user roles

### **Server**
- Apache Tomcat 9

---

## 🌟 Features

### **Public Features**
- Home page with hotel information  
- Room catalog  
- Services page  
- Image carousel showcasing hotel features  
- Google Maps integration showing location  

### **User Features**
- User registration  
- User login  
- Password recovery (JavaScript validation)  
- Shopping cart functionality  
- Product and category browsing  

### **Admin Features**
- User management  
- Product (room) management  
- Category management  
- Activity log (bitácora)  
- Dynamic admin menu  

---

## 📁 Project Structure

src/main/java/com/productos/
├── datos/ → Database connection (Conexion, TestConexion)
├── productos/ → Product, Category, Cart models
└── seguridad/ → User, Page, Bitacora (audit log)

src/main/webapp/
├── css/ → Modular CSS files
├── js/ → JavaScript utilities
├── images/ → UI assets and hotel pictures
├── images3d/ → .glb 3D models
├── head&foot/ → Header, footer, menu components
└── *.jsp → Main website pages (index, login, rooms, admin, etc.)


---

## 🗺 Google Maps
The homepage includes a Google Maps embed showing the hotel's (or student’s) location.

---

## 🎠 Image Carousel
Bootstrap carousel displaying hotel rooms, services, and promotional images.

---

## 🧩 3D Models
Integration of `.glb` models such as:
- WiFi  
- Tours  
- Room service  
- Mascot  

These can be displayed using 3D viewers.

---

## 👨‍💻 Developers
Include your LinkedIn links here:

- [Developer 1](https://www.linkedin.com/)
- [Developer 2](https://www.linkedin.com/)

---

## 📸 Screenshots

### **Home Page**
_Add your screenshot here._

---

## 🔗 GitHub Repository Link
_Add your GitHub repo link here once uploaded._

---

## 📦 Deployment Instructions

1. Install **Apache Tomcat 9**  
2. Install **PostgreSQL** and import the database  
3. Configure DB credentials inside `Conexion.java`  
4. Deploy the project inside the Tomcat `webapps` folder  
5. Start Tomcat and visit:

http://localhost:8080/hotelSambrano


---

## 📜 License
This is an academic project and is distributed without a commercial license.
