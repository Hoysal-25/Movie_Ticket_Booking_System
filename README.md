# 🎬 Movie Ticket Booking System

A **basic online movie ticket booking system** built with **Java Full Stack (Spring Boot + AngularJS)**. Customers can browse active movies, select their preferred seats, and book tickets online.

## 📌 About

This project is a simple yet functional **Movie Ticket Booking System** designed for beginners exploring **Java full-stack development**. It demonstrates **frontend + backend integration**, database connectivity, and validations to ensure smooth ticket booking operations.

## 🛠️ Technologies Used

* **Frontend:** AngularJS, HTML, CSS, Bootstrap
* **Backend:** Spring Boot (Java)
* **Database:** H2 (In-memory, configurable via `application.properties`)
* **Version Control:** Git

## ✨ Features

* 🎥 Display all **active movies** available for booking.
* 🎫 Customers can **select seats** according to preference.
* ✅ Validations ensure smooth booking and prevent invalid transactions.
* ⏱️ Real-time scheduling:

  * Shows are **auto-scheduled** for the current day.
  * Status changes dynamically:

    * **Completed** → Ticket booking not allowed.
    * **Running** → Ticket booking not allowed.
    * **Upcoming** → Ticket booking available.
    * 
## 🖼️ Preview

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/112768196/205480789-a5ff4ac0-6090-49be-b00f-d280084b7e20.png" alt="Homepage" width="250" height="150"/></td>
    <td><img src="https://user-images.githubusercontent.com/112768196/205480811-b27b0670-ed1d-4623-a5ba-250189b6498e.png" alt="Booking Page" width="250" height="150"/></td>
  </tr>
</table>  

## 🗄️ Database

* Default: **H2 Database** (in-memory, auto-configured for sample runs).
* Customization: Update **`application.properties`** file to integrate with another database (e.g., MySQL, PostgreSQL).
* **Pre-populated Data**:

  * Four movies activated across four theatres.
  * Four shows scheduled per day.
  * Show status updates dynamically based on current time (Upcoming, Running, Completed).

## 🚀 Getting Started

1. **Clone Repository**

   ```bash
   git clone https://github.com/yourusername/MovieTicketBooking.git
   cd MovieTicketBooking
   ```

2. **Run Backend (Spring Boot)**

   * Import project into IDE (IntelliJ / Eclipse).
   * Run the Spring Boot application.

3. **Run Frontend (AngularJS)**

   * Open frontend folder.
   * Serve the AngularJS app using a live server.

4. **Access Application**

   * Navigate to: `http://localhost:8080`

## 🔮 Future Enhancements

* User authentication & role-based access (Admin, Customer).
* Online payment integration.
* Email/SMS ticket confirmation.
* Multi-day movie scheduling.

## 🤝 Contribution

Contributions are welcome!

* Fork the repository
* Create a branch (`git checkout -b feature-branch`)
* Commit changes (`git commit -m "Added new feature"`)
* Push (`git push origin feature-branch`)
* Submit a Pull Request


## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
