python-password-manager_2.0
Password Manager_2.0

System Requirements Python 3.9 or higher installed on your machine. Ensure the following Python libraries are installed: tkinter (comes with Python standard library) sqlite3 (comes with Python standard library) bcrypt pandas Pillow cryptography smtplib Install any missing libraries using pip: bash Copy Edit pip install bcrypt pandas pillow cryptography

Prepare the Files Ensure you have the following files: The Python script (password_manager.py). Icon files (safe_icon.ico and/or safe_icon.png). Place all files in the same directory.

Setup the Database The script will automatically create a database file (password_manager.db) and the necessary tables when it runs for the first time. Ensure you have write permissions in the directory for the script to create the database.

Run the Application Open a terminal or command prompt. Navigate to the directory containing password_manager.py. Run the script: bash Copy Edit python password_manager.py

Initial Setup Sender Email Setup: Enter your Gmail or SMTP-compatible email and its app password. If you need help generating an app password, click the provided link for instructions. Admin Setup: Create an admin ID and password for secure access to the application.

Using the Application After setup, log in with your admin credentials. Use the GUI for: Saving, editing, deleting, and retrieving passwords. Searching passwords using the search bar. Exporting and importing data. Resolving conflicts during data imports.

Data Import Prepare your data in an Excel or CSV file with the following columns: Account ID Password Target Name Use the Upload Data option in the Maintenance menu to upload data.

Exporting Data Use the Export Data to Excel option in the Maintenance menu to save your data into a password-protected Excel file.

Logging and Error Handling The application automatically logs errors in the logs directory. Check logs if you encounter issues.

Maintenance Tasks Reset the admin or sender email credentials using the Maintenance menu. Delete logs older than 3 days if needed (automatically handled).


![image](https://github.com/user-attachments/assets/31d56a1f-eb89-410b-a50d-edb225bf5aa8)
