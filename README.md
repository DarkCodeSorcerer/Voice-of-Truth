# Voice of Truth
WordPress news website project with local setup.

# Features
- Latest news homepage
- Categories: Local News, World, Sports, Entertainment
- Sidebar: Recent posts / trending
- Header & Footer
- 5 Sample news posts

## Setup Instructions

### Requirements
- XAMPP or LocalWP
- PHP & MySQL

### Steps

1️⃣ Clone the GitHub Repo to Local

Open Git Bash / Terminal and run:

cd /path/to/htdocs  # For XAMPP

git clone https://github.com/DarkCodeSorcerer/Voice-of-Truth.git


✅ This will create a folder like:

htdocs/your-repo-name/

2️⃣ Setup the Database
🔹 Using phpMyAdmin (for XAMPP):

Go to http://localhost/phpmyadmin

Click "New"

Create a new database (e.g., my_wp_site)

Import the provided .sql file (like database.sql or db.sql from the cloned repo)

📝 Don’t have a .sql file?

Ask the developer or team to export the WordPress database via phpMyAdmin:
Export → Quick → SQL → Go

3️⃣ Configure wp-config.php

Inside the cloned folder, open the wp-config.php file (or copy wp-config-sample.php and rename it to wp-config.php), then update:

define('DB_NAME', 'testing');       
define('DB_USER', 'root');             
define('DB_PASSWORD', '');             
define('DB_HOST', 'localhost');

4️⃣ Start XAMPP Services

Open XAMPP Control Panel

Start Apache and MySQL

5️⃣ Open the Site in Browser

Go to:

http://localhost/test/


🎉 You should see your WordPress site!

<img width="1917" height="972" alt="image" src="https://github.com/user-attachments/assets/99a546b7-35b1-4aea-8ae4-926e75ba2445" />

