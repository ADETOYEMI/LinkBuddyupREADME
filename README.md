# README

# LinkBuddyup

#### The website is an online platform for group of childhood friends to connect and bond for beneficial social interaction.

### **Inspiration for the project:**
The project aims to provide feasible solutions to some problems identified by a group of old students.

#### The problems include:
1. Establishing and sustaining updated database for the group to include every member who desires to easily connect and identify with many others.
2. To gather, upload and keep a library of important souvenirs and pictures, memorabilia for historic values and be made easily accessible to registered members.
3. To establish group connection to important link(s) online for resourcefulness such as "electionrunner".

## Coding build:
Python syntax was used programming the application, templates, html, css and help files. Flask is used to execute the codes and run them in the server.

## Concept title
The title "LINKUPBUDDY" for this final project, has its root in the group identification tagged "buddy". Linking buddies, translates to uniting old friends!

### Concept design
The website is designed to have a "Home" page, accessible through index.html. The index.html itself connects to layout.html to execute.
The layout.html is the template upon which other templates for the website execute. The layout.html template was a resource supplied to answer pset 9 questions. It was adopted for this project with some addition of buttons and styles.

### Layout.html
"Layout template" hosts four buttons that display links to "Member's Bio", "Load Up", "Depository" and "Transactions" pages on the website.
It also hosts the "Register", "Login" and "Logout" buttons.

### The "Member's Bio" 
This page si structured to allow every member input and submit their "name", "username" "month of birth", "day of birth", "email address", "present city" and "present country" of residence onto the database.

### "Loadup" and "download" pages
The web facilitates access to registered members for uploading and downloading files and images that everymember can access as needed. To upload, "POST" method was used in the python's application to route the codes to upload.html. For feedback, if upload of files and images is/are successful, "uploaded.html", kept in template folder along with all html file, will be rendered for display on the website. A folder(FoldM) was coded for uploading files and images. To download, "GET" request method was used to send the code with python application. Source folder is foldM in the code. On the website, "Depository" button is the access to view files in the server.

### "Offer" and "Needs" pages
"Offer" and "Needs" pages are accessible through "Transactions" button on the "Home" page. "Offer" page is for registered members to display objects, treasures or properties that others can use or acquire before they are exposed to the public.
"Needs" page is to allow registered members publish list of things they need, perhaps any member may have them.

### "Resource" page.
Resource page is also accessible through "Transactions" button. This page is to facilitate link to external resources as necessary. For demostration, it is linked with an online election portal "electionrunner". The election site, where important election(s) can be set up in seconds, is resourceful for conducting free, fair, transparent and reliable elections. Everyone from anywhere there is internet connection can vote and be voted for. Site like this can help build trust in executive members of the group.

