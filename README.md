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
├── menu       # Main script with interactive menu
├── user1      # Script with functions 1–5
├── user2      # Script with functions 6–9
├── README.md  # Project documentation

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
| Feature           | Description                                          |
| ----------------- | ---------------------------------------------------- |
| Show System Info  | Displays system stats (hostname, uptime, disk, etc.) |
| List Bash Users   | Lists users with `/bin/bash` shell                   |
| Search User       | Check if a user exists                               |
| Add User          | Adds a new user with sudo and validation             |
| Delete User       | Deletes a user with a home directory backup          |
| Show User Details | Shows UID, GID, groups, home, and shell info         |
| Change Password   | Securely resets a user password                      |
| Lock/Unlock User  | Enables or disables account access                   |
| Exit Program      | Safely exits the script                              |


👥 Contributors

    @abdelsalam101
    @kerolosNabil247

📸 Screenshots / Demo

    Running the menu
  ![Screenshot_From_2025-05-07_18-57-08](https://github.com/user-attachments/assets/e3be8a0c-dcaf-4ff6-979b-42837341b4aa)



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


