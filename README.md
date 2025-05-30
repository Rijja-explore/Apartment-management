# 🏢 Apartment Community Management System

A full-featured desktop application built with **Python** and **Tkinter** to help manage apartment communities efficiently. This app includes user authentication, resident management, maintenance tracking, guest viewing, and more — all backed by simple CSV-based storage.


## 📌 Features

- 🔐 **Login System** for Admins and Residents
- 🧑‍💼 **Admin Dashboard**: Add, remove, and manage residents
- 🏘️ **Resident Profile**: View personal info and maintenance dues
- 🛠️ **Maintenance Tracking & Editing**
- 📧 **Forgot Password Flow** with email notification (SMTP)
- 🧑‍🤝‍🧑 **Guest View**: Lists all currently available flats
- 🌳 **Binary Tree + Linked List** data structures used to organize and search residents

---

## ⚙️ Technologies Used

| Technology | Purpose                          |
|------------|----------------------------------|
| Python     | Core language                    |
| Tkinter    | Graphical User Interface (GUI)   |
| CSV        | Lightweight data storage         |
| SMTP       | Password reset email service     |

---

## 📝 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/apartment-community-management.git
cd apartment-community-management
```
2. Ensure Python is Installed
```bash
python --version  # Python 3.6 or above is recommended
```
3. Install Required Libraries
No external libraries needed unless modified. For email support, ensure smtplib and ssl are available (built-in with Python 3).

▶️ Run the App
```bash
python "Apartment Community Management with CSV.py"
```
Make sure the following files are in the same directory:
Magenta.csv
Turquoise.csv
Apartment.png
logo.png
logo edit.png
Contact us.png

📂 File Structure
```bash
apartment-community-management/
├── Apartment Community Management with CSV.py  # Main app file
├── Magenta.csv                                 # Magenta block residents
├── Turquoise.csv                               # Turquoise block residents
├── Apartment.png                               # Background image
├── logo.png                                    # Logo
├── logo edit.png                               # Alternate logo
├── Contact us.png                              # Guest contact UI image
├── README.md                                   # Project documentation
```

✉️ Password Reset Email Setup
To use the forgot password feature:
    Configure SMTP with a valid sender address
    Edit these variables in the script:
    ```bash 
      email_sender = 'youremail@gmail.com'
      email_password = 'your-app-password'
      email_receiver = 'admin-receiver@example.com'
      ```
Make sure 2FA and App Passwords are set up for Gmail.

🤝 Contributing
Contributions are welcome! Here’s how to get started:
```bash
# Fork the repo and clone it
git checkout -b feature/YourFeature
git commit -m "Add your feature"
git push origin feature/YourFeature
```
Then open a pull request 🚀

📄 License
This project is licensed under the MIT License.
See the LICENSE file for more details.
