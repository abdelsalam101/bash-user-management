# 🔐 Bash User Management System

A complete interactive **user management system** written in **Bash**, designed for Linux environments. It allows system administrators to easily perform essential user-related tasks via a simple terminal menu.

---

## 📌 Features

- 🖥️ **System Information**
  - View hostname, uptime, kernel version, and disk usage.

- 👤 **User Management**
  - List users with `/bin/bash` as their shell.
  - Search for users and verify existence.
  - Add new users with validation.
  - Delete users and automatically back up their home directories.
  - View full user details (UID, GID, groups, shell, home directory).
  - Change user passwords securely.
  - Lock/unlock user accounts.

- 📂 **Backup on Deletion**
  - Automatically copies home directory to `/tmp/username_backup` before deletion.

- 🧪 **Validation**
  - Checks if user exists before any operation.
  - Friendly error messages and confirmations for each action.

---

## 📁 File Structure

ManagementSystem/
├── menu # Main script with interactive menu
├── user1 # Script with functions 1–5
├── user2 # Script with functions 6–9
├── README.md # Project documentation


---

## 🚀 How to Run

1. **Clone the repo:**


git clone https://github.com/abdelsalam101/ManagementSystem.git
cd ManagementSystem

2.    Make all scripts executable:

chmod +x menu user1 user2

3.    Run the main menu:

./menu

🧪 Example Use Cases
Feature	Description
Show system info	==> Displays system stats for quick diagnostics
List bash users	==> See which users have a login shell
Search user ==> Quickly check if a user exists
Add user ==> Add a new user with sudo and setup
Delete user ==>	Remove a user and backup home directory
User details ==>	View UID, GID, groups, shell, etc.
Change password	==> Prompt and securely reset password
Lock/Unlock	==> Temporarily disable or enable a user account

👥 Contributors

    @abdelsalam101
    @kerolosNabil247

📸 Screenshots / Demo

    Running the menu
    ![Screenshot From 2025-05-07 18-57-08](https://github.com/user-attachments/assets/c5e79c1f-8119-4595-9ffd-01ce2ee7f9ac)

    Show system Information
    ![Screenshot From 2025-05-07 19-07-57](https://github.com/user-attachments/assets/8eb4589a-8af8-40b3-a12a-a3f802c1e48a)
      
    List users with /bin/bash shell
    ![Screenshot From 2025-05-07 18-58-46](https://github.com/user-attachments/assets/6d989a80-6236-48a5-bde6-f9cc98b26b44)

    Search for user
    ![Screenshot From 2025-05-07 18-59-06](https://github.com/user-attachments/assets/c79a9d01-71ed-4d36-a0fc-70a7a48983d9)

    Add User
    ![Screenshot From 2025-05-07 19-00-19](https://github.com/user-attachments/assets/0596530c-0907-4399-a248-12c6b158eb29)

    Delete User (with home backup)
    ![Screenshot From 2025-05-07 19-00-45](https://github.com/user-attachments/assets/0a1efdf2-d6cd-450c-b310-ec4ef260c217)

    Show User details
    ![Screenshot From 2025-05-07 19-01-17](https://github.com/user-attachments/assets/80ca5016-f277-42e4-a9dd-c12ec0c80547)

    Change User Password
    ![Screenshot From 2025-05-07 19-05-52](https://github.com/user-attachments/assets/5719aad8-8a6c-4782-bebc-b1e060232e81)

    Lock User
    ![Screenshot From 2025-05-07 19-06-09](https://github.com/user-attachments/assets/a06460f0-6e0e-4ecc-b9fa-ba1339096f70)

    Unlock User
    ![Screenshot From 2025-05-07 19-06-22](https://github.com/user-attachments/assets/76c205cc-3c03-4896-bf88-5e0d3d43605d)

    Exit the Program
    ![Screenshot From 2025-05-07 19-06-37](https://github.com/user-attachments/assets/616fabcc-7c1b-4fa0-a9d2-a4374603bafc)

⚙️ Requirements

    Linux OS (tested on Ubuntu VM)
    bash, sudo, passwd, and standard Linux tools

🪪 License

MIT License — feel free to use and modify.


