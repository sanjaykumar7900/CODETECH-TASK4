Name: Sanjay Kumar
Company: CODETECH IT SOLUTIONS 
ID:
Domain: SQL 
Duration: Dec2024- Feb2025
Mentor: Neela Santhu


### **Movie Rental System Database Project Overview**

---

## **1. Project Objective**  
The goal of this project is to design and implement a **Movie Rental System Database** to efficiently manage movie rentals, customer information, and movie returns. The system will handle operations such as renting movies, tracking rental durations, managing returns, and calculating late fees.

---

## **2. Core Functionalities**

### **a. Customer Management:**  
- Add new customers.  
- Store customer details (name, contact information, registration date).  
- Ensure unique email addresses.

### **b. Movie Management:**  
- Add new movies to the database.  
- Track movie details (title, genre, release year, rental price, and stock availability).  
- Update movie stock when rented or returned.

### **c. Rental Management:**  
- Allow customers to rent available movies.  
- Track rental dates, due dates, and return status.  
- Prevent renting movies that are out of stock.

### **d. Return Management:**  
- Record movie return dates.  
- Calculate and apply late fees if the movie is returned after the due date.  
- Update movie stock on return.

### **e. Reporting and Queries:**  
- View active rentals.  
- Track overdue movies and calculate late fees.  
- Generate customer rental history reports.  
- Display movie availability.

---

## **3. Database Structure**

### **Tables:**
1. **Customers**: Stores customer information.  
2. **Movies**: Stores movie details and stock information.  
3. **Rentals**: Tracks rental transactions (rental date, due date, return status).  
4. **Returns**: Tracks return details and calculates late fees.  

### **Relationships:**
- **Customers** ↔ **Rentals**: One customer can have multiple rentals.  
- **Movies** ↔ **Rentals**: One movie can be rented multiple times.  
- **Rentals** ↔ **Returns**: Each rental corresponds to one return record.

---

## **4. Key SQL Features Implemented**
- **Primary and Foreign Keys:** Ensure referential integrity.  
- **Transactions:** Maintain data consistency during rentals and returns.  
- **Joins:** Retrieve data across multiple tables (e.g., rental history).  
- **Triggers (Optional):** Automate stock updates on rental and return.  

---

## **5. Tools and Technologies Used**
- **Database Management System (DBMS):** MySQL  
- **Interface Tool:** MySQL Workbench  
- **Local Server (Optional):** XAMPP  
- **IDE:** VS Code (SQL Extensions)  

---

## **6. Sample Operations**
- Add a new customer.  
- Add a new movie.  
- Rent a movie (update stock automatically).  
- Return a movie (calculate and apply late fees).  
- Generate reports on active rentals, overdue movies, and customer rental history.  

---

## **7. Benefits of the System**
- **Efficient Rental Management:** Simplified tracking of rentals and returns.  
- **Inventory Control:** Real-time updates to movie stock.  
- **Customer Insights:** Rental history and behavior tracking.  
- **Scalable Design:** Ability to add more features (e.g., online bookings, membership plans).  

---

## **8. Future Enhancements (Optional)**
- Add **user authentication** for system access.  
- Build a **web interface** for customers and admins.  
- Enable **email notifications** for due dates and late fees.  
- Introduce **membership tiers** with discounts.  

---

This project serves as a foundational exercise in **database design, query optimization, and transaction management**, making it an excellent learning experience for real-world database systems.  

