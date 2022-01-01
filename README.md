# CS50 FINAL PROJECT README

# LinkBuddy

#### LinkBuddy is a website conceptualized as an online platform for a group or many groups of people who share old commonalities. Perhaps, childhood friends; old schoolmates or neighbourhood friends to connect and interact easily online for beneficial social interactions.

### **Inspiration for the project:**
The project aims to provide feasible solutions to some problems identified as inhibiting sustanenance of benefits associated with groups and grouping, for long time span.

#### The problems include:
1. Establishing and sustaining updated database for the group to include every member who desires to easily connect and identify with many others.
2. Gathering, uploading and keeping active library of important souvenirs, pictures, memorabilia or group treasure(s) such as prizes or trophies, for historic values and be made easily accessible.
3. Establishing group connection to important link(s) with online resourcefulness such as "electionrunner".

## Coding build:
Python was used as syntax for programming the application, templates, html, css and help files. Flask is used to execute the codes and run them in the server.

## Concept title
The title "LinkBuddy" for the project, has its root in the group identification tagged "buddy". Linking buddies, translates to uniting old friends!

### Concept design
The website is designed to have a "Home" page, accessible through index.html. The index.html itself connects to layout.html to execute.
The layout.html is the template upon which other templates for the website execute. The layout.html template was a resource supplied to answer pset 9 questions. It was adopted for this project with some addition of buttons and styles.

### Layout.html
"Layout template" hosts four buttons that display links to "Member's Bio", "Load Up", "Depository" and "Transactions" pages on the website.
It also hosts the "Register", "Login" and "Logout" buttons.

### The "Biodata" 
This page si structured to allow every member input and submit their "name", "username" "month of birth", "day of birth", "email address", "present city" and "present country" of residence onto the database.
![BiodataPage](https://user-images.githubusercontent.com/71538409/147842445-8a036ffd-c2ca-4389-bc49-2a1b22db42e0.JPG)

### "Loadup" and "Storage" pages
The web facilitates access to registered members for uploading and viewinging files and images that every member can access as needed. To upload, "POST" method was used in the python's application to route the codes to upload.html. For feedback, if upload of files and images is/are successful, "uploaded.html", kept in template folder along with all html file, will be rendered for display on the website. Static folder was provided for uploading files and images. To view, "GET" request method was used to send the code through python application. Source folder is the static in the registry. On the website, "Storage" button is the access to view the files and images in the server.

### "Offer" and "Needs" pages
"Offer" and "Needs" pages are accessible through "Transactions" button on the "Home" page. "Offer" page is for registered members to display objects, treasures or properties that others can consider acquiring before they are exposed to the public.
"Needs" page also allows registered members to publish list(s) of things they need, perhaps any member may have them.

![offer page](https://user-images.githubusercontent.com/71538409/147842451-b70dae98-7cba-478e-90ff-08465b8f10d3.JPG)

![Needs page](https://user-images.githubusercontent.com/71538409/147842455-86e3f65d-13a9-4be8-a9ae-b94e8266926f.JPG)

### "Resource" page.
"Election Resource(s) link" connects to external site pnline. It is accessible through "Transactions" button. This page facilitates link to the external resources as necessary. For demonstration, it is linked with an online election portal "electionrunner.com". The election site, where election(s) can be set up in fast, cheaply and securely, resourcefully for conducting free, fair, transparent and reliable elections. Everyone from anywhere in the world, who has access to internet connection can vote and be voted for. Site like this can help build and foster trusts, enduring politics and reign of peace amongst friends and in geograpical communities.
![image](https://user-images.githubusercontent.com/71538409/147842387-8edf07d3-6a6f-4559-abc6-046198428b83.png)


### Site design
To enhance the pages for color and attractions, "free" background images were downloaded online and renamed, from five links below, for their high resolutions advantage.
  1. https://pixabay.com/photos/stones-rocks-pebbles-colorful-167089/ - rename as "stones.jpg"
  2. https://pixabay.com/photos/stones-rocks-gray-background-4376813/ - renamed as "stonesy.jpg"
  3. http://getwallpapers.com/wallpaper/full/0/e/1/99863.jpg - renamed as "snowland.jpg"
  4. https://www.wallpaperama.com/post-images/wallpapers/plant/mushroom.jpg - renamed as "mushroom.jpg" 
  5. https://www.pcclean.io/wp-content/uploads/2020/4/fQfm2i.jpg - renamed as "treefall.jpg"
  
   ![image](https://user-images.githubusercontent.com/71538409/147842366-4852af2e-5b95-46e0-bee2-3ee18f8ce898.png)
 
