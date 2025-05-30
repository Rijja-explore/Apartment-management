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

## Screenshots
![image](https://github.com/user-attachments/assets/d6c1063f-fd30-4c75-9839-1157f00e85f2)
![image](https://github.com/user-attachments/assets/dff81434-35eb-4d9a-8d51-dbfa23853af8)
![image](https://github.com/user-attachments/assets/d2f5cc52-0307-4a81-afdf-352f498f3cd8)
![image](https://github.com/user-attachments/assets/3ae34563-7c26-4506-bd83-1c7afef18406)
![image](https://github.com/user-attachments/assets/16d9d352-4ee5-40f0-9fb5-b6fca556ef47)
![image](https://github.com/user-attachments/assets/d06991ac-874b-4d60-9693-bd039f45f127)
![image](https://github.com/user-attachments/assets/74b6892e-ce98-4579-8c3d-a505bb9fcb7b)
![image](https://github.com/user-attachments/assets/0b625ddd-18f2-4720-9daa-d9407fa2c548)
![image](https://github.com/user-attachments/assets/bded2326-2267-49f5-8ecb-9582d1aa8532)
![image](https://github.com/user-attachments/assets/02e50057-38cd-4fd1-8e1c-bebb889c5e68)




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
---
Contributions are welcome! Here’s how to get started:
```bash
# Fork the repo and clone it
git checkout -b feature/YourFeature
git commit -m "Add your feature"
git push origin feature/YourFeature
```
Then open a pull request 🚀

📄 License
---
This project is licensed under the MIT License.
See the LICENSE file for more details.
