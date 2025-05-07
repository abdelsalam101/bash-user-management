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
    

    Show system Information
   
      
    List users with /bin/bash shell
    

    Search for user
    

    Add User
    

    Delete User (with home backup)
    

    Show User details
    

    Change User Password
    

    Lock User
    

    Unlock User
    

    Exit the Program
    

⚙️ Requirements

    Linux OS (tested on Ubuntu VM)
    bash, sudo, passwd, and standard Linux tools

🪪 License

MIT License — feel free to use and modify.


