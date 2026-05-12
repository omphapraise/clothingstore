====================================
PASTIMES — LOGIN CREDENTIALS
====================================

SETUP:
1. Open XAMPP → Start Apache and MySQL
2. Visit: localhost/ClothingStore/loadClothingStore.php
3. This builds the database automatically

------------------------------------
ADMIN LOGIN
------------------------------------
URL:      localhost/ClothingStore/adminLogin.php
Email:    admin@clothingstore.com
Password: password

------------------------------------
USER LOGINS (all pre-approved)
------------------------------------
URL: localhost/ClothingStore/login.php

Username: johndoe
Email:    john@email.com
Password: password123

Username: janesmith
Email:    jane@email.com
Password: pass456

Username: lebo_m
Email:    lebo@email.com
Password: lebo789

Username: aishap
Email:    aisha@email.com
Password: aisha999

------------------------------------
PENDING USER (needs admin approval)
------------------------------------
Username: thabonkosi
Email:    thabo@email.com
Password: thabo321
Note:     Login as admin first and
          approve this account to
          demonstrate the approval flow

------------------------------------
REGISTER NEW USER
------------------------------------
URL:  localhost/ClothingStore/register.php
Note: New users default to pending
      Admin must approve before login

------------------------------------
FILE STRUCTURE
------------------------------------
/images/  → 5 product PNG files
/data/    → 4 .txt data files
DBConn.php
loadClothingStore.php
createTable.php
myClothingStore.sql
register.php
login.php
adminLogin.php
adminDashboard.php
userDashboard.php
viewCart.php
cart.php
logout.php
style.css
README.txt
====================================
