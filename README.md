
# Control Your Inventory

As the name implies, the Control Your Inventory application allows businesses to take control of their inventory by tracking their product. The application is designed with a minimal approach, so anyone can pick up and start using it. The intended use of the application is for startups or small businesses that do not have an inventory tracking system already in place. The application requires authentication upon entering the device with a user setup username and password. Once signed into the application, users can add, modify, or remove items from the database. This application utilizes SQLite as its database engine solution for storing data on the local device. The users in settings can enable SMS notification, and they will get an SMS message that informs them about their on-hands and low counts. 
## Motivation

As its final project, this application was developed for the Southern New Hampshire University, SNHU, course CS360: Mobile Architecture & Development. The scenario of this project is as follows:
“As the newest developer for the mobile application development team for Mobile2App, you are assigned to create an Inventory app for one of your clients. The inventory application will keep track of items in a warehouse. 

The requirements for the application are:

•	Create a database using at least two tables, the first for storing inventory items and the second to store users’ usernames and passwords.

•	Upon launching the application, the users must authenticate themselves by logging in with a username and password or creating a unique username and password if they are brand new.

•	The inventory needs to be displayed as a grid. That will allow users to add or remove items from the database.

•	A mechanism must be created to allow users to adjust an item on hand counts.

•	A mechanism needs to be created that will allow users to receive an SMS message about inventory low on hands

As the lead developer for this assignment, you will conceptualize the user’s goals, use cases, the UI design, and code design for this application.”

## Requirements
•	Android Studio or your IDE of choice

•	If you're intending on running the application on a Android device it needs to be running Android 9.0 (Pie) or newer

•	Designed primarily for android phones, should scale properly for android tablets. 

•	Approximately 100MB of storage. Could be less or more depending on size of database created.

## Getting Started

To get started, you will first need to clone this repository to a place of your choosing on your local device. 

Once you have the projected saved on your local device, upload the project to your IDE of choice for Android development. Next will be to build and run the application. 

## Usage

There are three main pages to this application:

•	The login menu
•	Inventory Directory
•	Update on hand counts


Login Menu:

When first running the application, the user is greeted with a login menu and must log into their account or set up a new account if there is a new user. 

It’s required for the user every time they enter the application to authenticate themselves

If the user is new to the application, they can register and add to the database by selecting the register button.
 


Inventory Directory:

After logging in, the user is greeted with the main homepage of the application. The main homepage consists of a grid layout of all the merchandise that has been added to the database.

The user can use the Floating Action Button, or FAB for short, to create and add a new product to the database. However, the user will need to add essential information before successfully adding a product to a database, such as the product name, the product type, which refers to its status, and the current on-hand counts. 

The users can also select the delete button on the right side of each product in the database, and it will remove the item from the database.


![image](https://user-images.githubusercontent.com/89234922/184546001-62ec65fe-d279-4d83-b23e-9ff017273435.png)
![image](https://user-images.githubusercontent.com/89234922/184546052-dd7ad4c6-d19e-42cd-bd65-f249071d31f3.png)


Update Quantity:

If the on-hand count for a product needs to be adjusted, they can select the product by tapping on its name, which will take them to a new page asking for user input on the new hand counts. 


![image](https://user-images.githubusercontent.com/89234922/184546027-42512826-efad-4ecf-8c98-7fe5aa8e092f.png)


Settings:

When selecting the menu bar in the top left of the application, the user can access settings or sign out of the application. 

When the user selects the sign-out option, it will sign the user out and take them back to the login screen they were greeted when first opening the application. When the user selects settings, the user is taken to the settings page. From this page, the user can enable SMS notifications about hand counts of the merchandise in the database. In addition, the user can select the Delete Item Data button, which will purge the entire database of its data.


![image](https://user-images.githubusercontent.com/89234922/184546013-465f438d-3f6f-4add-a883-83d4460d4132.png)
![image](https://user-images.githubusercontent.com/89234922/184546020-00423fe3-da58-4ad1-b5cc-b6fe195ac087.png)


## Roadmap

This inventory tracking application meets the basic requirements of what makes an inventory tracking system. 

Here are the current future iterations for Control Your Inventory:

    1.	Expand the database: Additional information is needed for each merchandise, such as item number and UPC.

    2.	Barcode Scanning: Add the ability to scan barcodes with the user’s device camera or a Bluetooth scanner.

    3.	Product image: Allow users to upload or take a photo of a product displayed with the product.

    4.	Change update item page to item information page: In the home directory tapping on an item will provide additional information rather than a simple update on on-hand counts. The item information page provides the product name, item number, UPC, and picture of the item. Users can then select the option to delete or edit the item.

    5.	Create a new main homepage: The new homepage will provide four search features; search by item number, UPC, scan barcode, and merchandise directory. The FAB will still be available in the bottom right corner of the homepage for quick access to adding new products to the database.
