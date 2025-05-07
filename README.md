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
   ![Screenshot_From_2025-05-07_19-07-57](https://github.com/user-attachments/assets/70d5db9f-5f98-4953-9c94-51001b7bd8fd)
      
    List users with /bin/bash shell
  ![Screenshot_From_2025-05-07_18-58-46](https://github.com/user-attachments/assets/589d7442-c6a0-4d3f-a280-fe59f769884e)


    Search for user
   ![Screenshot_From_2025-05-07_18-59-06](https://github.com/user-attachments/assets/d3abe690-ab04-445f-91af-ed5889d7da8b)

    Add User
   ![Screenshot_From_2025-05-07_19-00-19](https://github.com/user-attachments/assets/9e0cacc4-34e6-4b94-a22d-fd5618785af3)
  
    Delete User (with home backup)
  ![Screenshot_From_2025-05-07_19-00-45](https://github.com/user-attachments/assets/74d9896d-a9cf-44f4-920c-9261db093344)

    Show User details
  ![Screenshot_From_2025-05-07_19-01-17](https://github.com/user-attachments/assets/9356744b-55c5-43c0-981a-d6a60c14362a)

    Change User Password
  ![Screenshot_From_2025-05-07_19-05-52](https://github.com/user-attachments/assets/0db8ee6a-260b-40e6-b58c-667ee5626ce5)

    Lock User
  ![Screenshot_From_2025-05-07_19-06-09](https://github.com/user-attachments/assets/362179fb-0f82-4390-82e4-98843db9bfb9)

    Unlock User
  ![Screenshot_From_2025-05-07_19-06-22](https://github.com/user-attachments/assets/deb89779-b058-426b-aac8-d011d0123663)

    Exit the Program
  ![Screenshot_From_2025-05-07_19-06-37](https://github.com/user-attachments/assets/406022cd-1c2f-4332-9663-66ed6d92482f)


⚙️ Requirements

    Linux OS (tested on Ubuntu VM)
    bash, sudo, passwd, and standard Linux tools

🪪 License

MIT License — feel free to use and modify.


