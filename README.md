# PantryPal
Your Unique Grocery Hub

# Table of Contents
1. Description of the app
2. Features
3. Explanation of the files
4. Installation
5. Usage
6. Extra information
7. Credits
   
# Description of the app
As university students who have found ourselves living alone for the first time, we quickly realized the importance and difficulty in carrying out effective grocery shopping. Essentially, we want to save moeny and time on this activity which we carry out on a nearly daily basis. Motivated by these factors, we developed the fundamentals of an easy-to-use platform that can serve as a hub for this essential aspect of our lives and aid us by facilitating carrying out of this task while at the same time helping us reducing our food waste to become more sustainable and healthier people.  
As users enter the app, the system will display the following areas, waiting for the user to choose where they want to be directed:
- My fridge
- Receipt Reader or Update Groceries Manually
- Past Groceries
  
Here, they will be able to manage their groceries and waste management through multiple functionalities: 
In the My fridge area, users will be to view each item they currently have in their fridge in order of expiration date from most to least perishable item. What allows the app the content of the products present in their fridges is the Receipt Reader feature of the app. This feature allows users to input a picture of their grocery receipt so that each item the My fridge area is updated with the new purchases, which are also saved into the Groceries area of the app as users can see their past grcoery purchases when making new grocery lists.
As if this wasn't enough, PantryPal will also send users notifications reminding them when one of the items present in their fridge are about to expire. This way, students will be able to proberly improve their Waste Management and lead more sustainable lives.

# Features


# Installation
To be able to run the program, the user must have the following things installed:
- Python programming language: the program will work in all versions between 3.6 and 3.8.
- Libraries: the user must use 4 libraries when using the code: datetime, getpass, json, os. Moreover, the code explains the neccesity of a library for OCR, but it didn't specify which one. To download a library, the user must execute the following command: **pip install "name of library"**

Once the user has one of the possible versions of Python and the required libraries set up, he has to open the file called "Code" and run the program.

# Usage
After a users enters our platform and log in, they will be asked about their intentions:
- Accesing to my Fridge (which includes the current groceries on different colors based on their expiration date and the nutritional value of this grocery)
- Updating the fridge with new products (by taking a photo to the receipt or writing them manually)
- Accesing to past groceries (which includes past grocery receipts and their nutritional values)

After the user has pressed the button of his decision, it will be conducted to the respective section:
1. Accesing to my Fridge: the current groceries will appear sorted and colour by expiration dates, being the priority products first and on reed, continued by the yellow and the green ones respectively. The user will be able to see a photo of each product and its expiration date, and when pressing the product, also its nutritional values.
2. Updating the fridge with new options: on this section, the user can update its product in two different ways:
   - If he press the upload picture button, he will be directed to its camera and would we asked to take a photo to its grocery receipt. After that, questions regarding expiration dates and possible confusions when implementing OCR will be asked, and the products will be uploaded to my Fridge (with their respective colors and their expiration date and photo, and occupating their respective position).
   - If he press the insert manually insert button, he will be asked about the name of the product and products attributes such as expiration date, the quantity bought, etc). Once the app has this information, the new products will be uploaded to my Fridge (with their respective colors and their expiration date and photo, and occupating their respective position).
3. Accesing Past Groceries: in this section, 3 actions can be performed:
   - They can search the name or date of a food that is on the past groceries
   - They can see a list with all their grocery receipts. Moreover, if they press a concrete receipt, they will be able to see it with more details
   - They can access to the nutritional values of the past groceries by pressing the nutritional values button
  
Moreover, in the 3 sections, below there is are 3 buttons: 1 that indicates the current section, and 2 that refers to the other 2 sections (so that the user can go directly to the section he want without having to return to the main page).

# Extra Information
In the development of this project, we faced multiple challenges. From the coding to the workload management, we oftentimes found ourselves struggling with our tasks; yet, through commitment and hard work we maanged to overcome these and output our best possible work with our current skill levels. We are especially proud of the Artificial Intelligence implementation within the Receipt Reader area of the platfrom which we believe makes us stand out from other projects. In order to stand out to an even greater extent, we had come up with a variety of ideas and features which we concluded to be unfeasible for our current skill-level. One feature that we had believed could add enormous value to the app was a mapping platform that essentially provided the optimal route to do one's groceries within supermarkets, based on the users' shopping lists. This could be conceptualized as a Google Maps for supermarkets, inputting shopping lists and outputting the locations of these items as well as the most time-efficient route for users from when they entered the store to when they exited it. Even though this functionality would have perfectly linked with our apps' core functions, we deemed it as unfeasible since it would have required making agreements with supermarkets to have their workers constantly update the position of items within their stores. Also, what might have seemed as a logical extension of our app was a delivery service that brought users the products within their grocery lists. However, we believed this to be too much of a liability for the initial stage of our app, and decided not to pursue it.

Even though we ended up not pursuing these features, we are still proud of our output and are grateful for what we learned in regard to how apps are actually developed in a professional work-environment. 

# Credits
This project was created for our Algorithms and Data Structures course at IE University. The proyect was created by: 

Project Lead: Alejandra Gómez and Niccolò Pragliola

UX Researcher: Mariano Delpree

Research Analyst: Paula Evangelista

Testing Moderator 1: Deniz Meten

Testing Moderator 2: Bernarda Andrade











