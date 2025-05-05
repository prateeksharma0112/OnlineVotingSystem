# 🗳️ Online Voting System

An online voting platform designed to facilitate secure and efficient elections. This system enables administrators to manage elections and allows voters to cast their votes remotely, ensuring accessibility and integrity in the voting process.

---

## 📌 Features

- ✅ User Authentication for admins and voters
- 🗂️ Election and Candidate Management
- 🗳️ Secure Voting Mechanism (One vote per user)
- 📊 Real-time Result Compilation
- 🔐 Basic Data Security Handling

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

---

## 📁 Project Structure
```bash
OnlineVotingSystem/
├── api/ # Backend API endpoints
├── db_file/ # Database schema and related files
├── resources/ # Static assets like images and stylesheets
├── routes/ # Application routing logic
├── uploads/ # Directory for uploaded files
├── admin.php # Admin dashboard interface
├── index.php # Main landing page
├── .gitattributes # Git configuration attributes
```

---

## 🚀 Getting Started

### Prerequisites

- **Web Server** (e.g., XAMPP, Apache)
- **PHP** >= 7.0
- **MySQL** >= 5.7
- Modern web browser (e.g., Chrome, Firefox)


### Installation

Follow these steps to set up and run the Online Voting System locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/prateeksharma0112/OnlineVotingSystem.git
   ```

2. **Set up the database:**

   Open phpMyAdmin or your preferred MySQL client.

   Create a new database (e.g., online_voting_db).

   Import the SQL file located in the db_file/ directory into this database.

3. **Configure your server:**

   Move the cloned project folder into your web server's root directory (e.g., htdocs if using XAMPP).

   Update database configuration inside the project (if needed) to match your local DB credentials.

4. **Start services:**

   Make sure your Apache and MySQL services are running (use XAMPP or your server stack).

5. **Run the application:**

   Open your browser and visit:
   
   ```bash
   http://localhost/OnlineVotingSystem/index.php
   ```

   You're now ready to use the Online Voting System locally!


## 👤 User Roles
### 🛠️ Administrator
   
  - Manage elections
  
  - Add or remove candidates

  - View election results

### 🧑‍💻 Voter
 - Register and log in

 - Cast vote for available elections (only once per election)

   
## 🤝 Contributing

Contributions are welcome!

Feel free to fork the repository, raise issues, or submit pull requests.

For major changes, please open an issue first to discuss what you'd like to change.

## 📬 Contact

Developer: Prateek Kumar Sharma

📧 **Email:** [prateeksharma0112@gmail.com](mailto:prateeksharma0112@gmail.com)  
🌐 **GitHub:** [@prateeksharma0112](https://github.com/prateeksharma0112)

---

## 🙌 Final Words

Whether you're a developer looking to build on this project or someone exploring how online voting systems work — you're welcome here! 🎉

This project is more than just code — it's a step toward making democratic processes more accessible, secure, and efficient in the digital age. Feel free to explore, contribute, or use it as inspiration for your next big idea.

Thanks for stopping by — and happy coding! 💻✨

