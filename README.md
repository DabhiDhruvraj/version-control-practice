# Hotel-Website
It is a website where client can book table online , order food online,book a room and give feedback and admin can manage status of room, table and can view feedbacks.
Technology used:

+ Frontend:
  + HTML
  + CSS
  + Bootstrap
+ Backend:
  + NodeJs
  + Express
  + Mongo DB
 
___
## Installation
+ ### Install NodeJs
    + Go to https://nodejs.org/en/ and install latest version of Nodejs.

+ ### Install MongoDB
    + Go to https://www.mongodb.com/docs/manual/installation/ and install the suiltable version for your OS.
    + For steps of installation, refer [this](https://www.mongodb.com/docs/manual/installation/#mongodb-installation-tutorials) document.
    + For queries regarding installation refer [here](https://www.mongodb.com/docs/drivers/node/current/#:~:text=For%20answers).
 
+ ### Clone this Repository
  + Go to your command terminal and cd to the folder you want to clone this repo to.
  + You can Clone using https, ssh or github cli.
   + For more information on how to clone visit [this](https://github.com/git-guides/git-clone) document.

+ ### Install Dependencies
    + Once you have cloned the project it should be visible in the directory that you have cloned.
    + Go to that folder and type `npm install` command to install all the dependencies.
    
+ ### Run mongoDB in background
    + Go to the mongoDB directory and run mondoDb.exe
    
+ ### Start nodeJs Server
    + Run the command `node server.js` in the terminal.
    + It should output "App listining on the port 3000"
    + Open any Browser and type localhost:3000 in the search bar.
    + The home page of the website should be visible.
    + If there is any error in starting the server, make sure that the missing dependencies are installed.
___
+ ### Website Contents Link
1. [About](#about)
2. [Client View](#guest)
3. [Manager/Admin View](#manager)

<a name="about"></a>
### About
Allows customers to book a room, reserve a table at the hotel's restaurant, and give feedback and can also order food online. Allows managers/admin to view room availability, current guests, checkin and checkout guests, and restaurant table reservations.

![about](https://user-images.githubusercontent.com/125547030/220850104-01792ed4-8358-4f98-9852-b2d7f515d187.jpeg)
---
<a name="guest"></a>
### Client View
Clients can reserve tables and book rooms. They can also order the food from the table and provide feedback.

![table](https://user-images.githubusercontent.com/125547030/220865394-b7d23e8d-3618-4bcf-88c2-205d554adb82.jpeg)

![book room](https://user-images.githubusercontent.com/125547030/220865406-e0e197c4-7bb7-41e7-9258-1281fdb57e97.jpeg)

---
<a name="manager"></a>
### Admin View
Admin and hotel management can view the reservations and booking. They can view feedback and manage the customers.

![managermenu](https://user-images.githubusercontent.com/125547030/220865522-e47b1967-1e54-42b8-b4c9-9a7198ac8a1e.jpeg)
![roomstatus](https://user-images.githubusercontent.com/125547030/220865779-47c1f96c-c39b-45aa-bcd1-3ecd827e8d82.jpeg)

---
