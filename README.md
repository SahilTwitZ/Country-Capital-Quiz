# 🌍 Country-Capital Quiz

Welcome to the **Country-Capital Quiz**! This project is a fun, interactive way to test your knowledge of world capitals while I explored integrating **PostgreSQL** for database management. The quiz dynamically pulls questions from a PostgreSQL database, making each session unique and challenging. 🎯

---

## 🚀 Features

- **Interactive Gameplay:** Answer randomized country-capital questions.
- **Dynamic Data Fetching:** Questions are pulled directly from a PostgreSQL database.
- **Score Tracking:** Keep track of how many questions you get right.
- **Clean and Simple UI:** Focused on functionality and ease of use.

---

## 🛠️ Technologies Used

- **Frontend:** HTML CSS JS 
- **Backend:** NodeJS ExpressJS
- **Database:** PostgreSQL 🐘  
- **Query Language:** SQL  

---

## 📦 How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/SahilTwitZ/Country-Capital-Quiz.git
   cd Country-Capital-Quiz
   ```

2. **Set Up PostgreSQL Database:**
   - Ensure PostgreSQL is installed and running.
   - Create a new database:
     ```sql
     CREATE DATABASE quizdb;
     ```
   - Import the data (if there's a provided SQL script):
     ```bash
     psql -d quizdb -f schema.sql
     ```

3. **Configure Database Connection:**
   - Update your `.env` file (or configuration settings) with your PostgreSQL credentials:
     ```
     DB_HOST=localhost
     DB_USER=your_username
     DB_PASSWORD=your_password
     DB_NAME=quizdb
     ```

4. **Install Dependencies:**
   ```bash
   npm install
   ```

5. **Run the App:**
   ```bash
   npm start
   ```

---

## 🧠 What I Learned

- **PostgreSQL Fundamentals:** Setting up databases, writing SQL queries, and managing data.
- **Database Integration:** Connecting PostgreSQL to a backend for real-time data querying.
- **Efficient Querying:** Optimizing SQL queries for faster performance.
- **Project Structuring:** Organizing code for scalability and maintainability.

---

## 🎯 Future Improvements

- Add multiple difficulty levels or region-specific quizzes.
- Implement user authentication for personalized score tracking.
- Enhance UI/UX with animations and responsive design.
- Create a leaderboard to encourage competition.

---

## 🤝 Contributions

Feel free to fork the repo, create new features, or fix bugs! Pull requests are welcome. 🎉

---

## 📧 Contact

For any questions or feedback, reach out to me via [GitHub](https://github.com/SahilTwitZ) or email:  
📩 *sahil321nis@gmail.com*

---

Enjoy the quiz and challenge your knowledge! 🌎🧩
