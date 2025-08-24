AuctionPro

AuctionPro is a Java-based online auction system built with Spring Boot, MySQL, and JSP. It provides a robust platform for users to register, list items, place real-time bids, and manage auctions, with an admin dashboard for oversight.

Features





User Authentication: Secure registration and login for buyers and sellers.



Real-Time Bidding: Place bids on items with live auction timers.



Item Management: Create, update, and delete auction listings.



Admin Dashboard: Manage auctions, users, and monitor bidding activity.



Database Integration: Persistent storage of users, items, and bids using MySQL.

Tech Stack





Backend: Java, Spring Boot



Frontend: JSP, HTML, CSS



Database: MySQL



Build Tool: Maven

Prerequisites





Java 17 or later



Maven 3.6+



MySQL 8.0+



A web server (e.g., Apache Tomcat for JSP) or embedded server (via Spring Boot)

Setup Instructions





Clone the Repository:

git clone https://github.com/your-username/AuctionPro.git
cd AuctionPro



Configure MySQL:





Create a MySQL database (e.g., auctionpro_db).



Update the database configuration in src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/auctionpro_db
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.jpa.hibernate.ddl-auto=update



Install Dependencies:

mvn install



Run the Application:

mvn spring-boot:run





Access the app at http://localhost:8080 (or your configured port).



Test the Application:





Register a user account.



Create an auction item.



Place bids and monitor via the admin dashboard.

Project Structure

AuctionPro/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/auctionpro/ (Controllers, Services, Models, etc.)
│   │   ├── resources/
│   │   │   └── application.properties (Database config)
│   │   └── webapp/ (JSP files, CSS, JS)
├── pom.xml (Maven dependencies)
├── README.md
└── .gitignore

Contributing

Contributions are welcome! To contribute:





Fork the repository.



Create a feature branch: git checkout -b feature-name



Commit changes: git commit -m "Add feature-name"



Push to the branch: git push origin feature-name



Submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact

For questions or feedback, open an issue on GitHub.



Built as a portfolio project to demonstrate Java and Spring Boot expertise.
