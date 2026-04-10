# TRAVEL INQUIRY SYSTEM

**Extensive README Documentation**

---

# 1. Project Title

**Travel Inquiry System using HTML Frames, CSS and JavaScript**

---

# 2. Project Description

The Travel Inquiry System is a simple front-end website developed using basic HTML, CSS, and JavaScript. The system allows users to explore travel destinations, plan trips, submit booking inquiries, and log into the system.

The project is designed using **HTML Frameset layout** with a **header**, **navigation menu**, and **content area**. The website demonstrates the use of fundamental web development concepts such as forms, tables, lists, images, and basic JavaScript interactions.

This project is suitable for **college mini project**, **lab practical**, or **basic front-end demonstration**.

---

# 3. Technologies Used

### HTML Concepts Used

* Frames and Frameset
* Div layout
* Tables
* Lists
* Images
* Links
* Forms

### CSS Used

* External CSS file
* Colors
* Fonts
* Borders
* Margins
* Padding
* Text alignment

### JavaScript Used

* alert()
* confirm()
* prompt()
* onclick
* document.getElementById()
* document.write()

---

# 4. Project Layout

The website uses **Frameset Layout**

```
 ---------------------------------
|            HEADER               |
 ---------------------------------
|     MENU      |     CONTENT     |
|               |                 |
|               |                 |
 ---------------------------------
```

Top Frame → header.html
Left Frame → menu.html
Right Frame → All content pages

---

# 5. Folder Structure

```
TravelInquiry/
│
index.html
header.html
menu.html
home.html
login.html
destinations.html
planner.html
booking.html
about.html
style.css
script.js
```

---

# 6. File Description

### index.html

Main frameset page that divides the screen into:

* Top Header
* Left Navigation Menu
* Right Content Area

Uses:

```
frameset rows="20%,*"
frameset cols="25%,*"
```

---

### header.html

Displays the project title:

TRAVEL INQUIRY SYSTEM

Uses:

* h1
* center
* background color

---

### menu.html

Navigation menu with links:

* Home
* Destinations
* Travel Planner
* Booking
* Login
* About

Uses:

* unordered list
* hyperlinks
* target frame

---

### home.html

Displays:

* Welcome message
* Rajasthan images
* Intro text

Uses:

* images
* paragraph
* headings

---

### login.html

Login form with:

Username → textbox
Password → password field

Buttons:

Login
Reset

JavaScript validation:

Username: admin
Password: 123

Shows:

Login successful
Invalid login

---

### destinations.html

Displays travel destinations using table:

Columns:

Destination
Price
Days
Book

Destinations:

Goa
Manali
Jaipur (Rajasthan)
West Bengal
Odisha

Book button triggers:

confirm("Book this trip?")

---

### planner.html

Travel planning form includes:

Name → textbox
Destination → radio buttons
Budget → checkbox
Days → textbox

Submit button triggers:

prompt("Confirm planning?")
alert("Trip planned successfully")

---

### booking.html

Booking form includes:

Name
Email
Destination
Date

Submit button triggers:

confirm("Confirm booking?")

Shows:

Booking confirmed
Booking cancelled

---

### about.html

Contains:

Project description
Ordered list
Image

Explains services of Travel Inquiry System.

---

### style.css

External CSS file for styling:

* header styling
* menu styling
* table styling
* form styling
* button styling
* colors
* fonts

---

### script.js

Contains JavaScript functions:

login()
bookTrip()
planTrip()
confirmBooking()

Functions use:

alert()
confirm()
prompt()
getElementById()

---

# 7. Features

✔ Frameset Layout
✔ Navigation Menu
✔ Travel Destinations Table
✔ Travel Planner Form
✔ Booking Form
✔ Login System
✔ Password Validation
✔ Radio Buttons
✔ Checkbox Inputs
✔ Submit Button
✔ Reset Button
✔ JavaScript Alerts
✔ Confirm Dialog Box
✔ Prompt Dialog Box
✔ External CSS Styling
✔ Rajasthan Travel Images
✔ West Bengal & Odisha Destinations

---

# 8. Login Credentials

Username: admin
Password: 123

---

# 9. How To Run Project

Step 1
Create a folder named:

TravelInquiry

Step 2
Create all HTML files inside folder

Step 3
Create:

style.css
script.js

Step 4
Open:

index.html

in browser

---

# 10. System Requirements

Web Browser:

* Chrome
* Edge
* Firefox

No server required.

---

# 11. Learning Outcomes

This project demonstrates:

* HTML Frameset
* Form creation
* Table design
* Navigation menu
* Basic JavaScript validation
* External CSS styling
* Website layout design
* User interaction using JS dialogs

---

# 12. Future Enhancements

The system can be improved by adding:

* Database connectivity
* User registration
* Payment gateway
* Real booking system
* Dynamic destinations
* Responsive design
* Search feature

---

# 13. Conclusion

The Travel Inquiry System is a basic front-end web application created using HTML, CSS, and JavaScript. It provides users with the ability to explore destinations, plan trips, and submit travel inquiries. The project successfully demonstrates the use of frames, forms, tables, and JavaScript dialog boxes.

This project is suitable for academic submission and helps understand basic web development concepts.

---
