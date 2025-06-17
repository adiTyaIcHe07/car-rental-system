🚗 Car Rental System – Java Console Application
Live: Not applicable (console-based project)

Car Rental System is a terminal-based application built using Java that allows users to rent and return cars. It manages car availability, customer information, and rental history with a user-friendly text-based menu.

🚀 Features
📋 Add and manage multiple cars with brand, model, price, and availability
👤 Register and store customer details dynamically
📅 Rent a car by specifying rental days and get total pricing
✅ Check car availability before rental
🔄 Return cars and update system status
📦 Store and manage rentals using in-memory data structures
📠 Console-based menu system for seamless interaction

🛠️ Tech Stack
Language: Java (JDK 8+)
Concepts Used: Object-Oriented Programming (OOP), Collections (ArrayList), Scanner Class
Classes:

Car: Stores car info and availability

Customer: Holds customer data

Rental: Represents the rental relationship

CarRentalSystem: Core logic for renting and returning

Main: Entry point of the application

🧱 Folder Structure
📁 car-rental-system
├── Car.java # Car entity with price and availability logic
├── Customer.java # Customer details holder
├── Rental.java # Associates car with customer and duration
├── CarRentalSystem.java # Main logic for rental and return flows
├── Main.java # Program entry point and CLI menu
└── README.md # Project description and usage instructions

📦 Installation & Running the App
Clone the Repository

bash
Copy
Edit
git clone https://github.com/adiTyaIcHe07/car-rental-system.git  
cd car-rental-system  
Compile and Run the Program

bash
Copy
Edit
javac Main.java  
java Main  
🎤 Sample Flow
Start App → Show Menu → Rent or Return Car → Enter Details → Get Confirmation/Status

Example:

Enter your name → Choose available car → Enter rental days → Confirm

Return by entering Car ID → System updates availability

📚 Future Enhancements
🔒 File-based storage or database support (MySQL, SQLite)
🖥️ GUI using JavaFX or Swing
📝 Receipt generation with rental summary
📊 Admin dashboard to monitor rentals and earnings
🌐 REST API version using Spring Boot for full-stack integration
