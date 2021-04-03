# ShopBridge

**Shop Bridge** is a web application that helps track the different items for sale. It is an inventory managememt system which keeps records of the items with their name, description, price, quantity, item availability and an attached image of the same.

This project is built in **React JS and ASP.NET Core(.NET Core Framework 3.1)**

[![HitCount](http://hits.dwyl.com/roshnidahake13/ShopBridge.svg)](http://hits.dwyl.com/roshnidahake13/ShopBridge)

[![Shop Bridge Image](https://github.com/harshadp111/ShopBridge/blob/main/ShopBridge_Inventory.png)]()

## 📒 Table of Contents 

- [System Requirements](#-system-requirements)
- [Setup](#-setup)
- [Run Project](#-run-project)
- [Usage](#-usage)
- [Run Tests](#-run-tests)
- [Build](#-build)
- [Time Tracking](#-time-tracking)

## ⚙ System Requirements

* IDE Framework - **Visual Studio 2019 or higher**
* Database - **SQL Server 2012 or higher**
* OS - **Windows 8 or higher**
* **IIS** should be installed.

## 🛠 Setup

1. Pull the code.
2. Open **ShopBridge_WEBAPI** file via Visual Studio.
3. Insert connectionString in the _**UnitTestController**_ file of **ShopBridge.Test** project as shown below :
```
public static string connectionString = @"Data Source=LAPTOP-O5G13I0U\SQLEXPRESS;Initial Catalog=ShopBridge;Integrated Security=True;MultipleActiveResultSets=true;";
```
4. Open **Package Manager Console** in Visual Studio _(**Tools > NuGet Package Manager > Package Manager Console**)_
5. In the Package Manager Console, select Default Project as **ShopBridge_WEBAPI**.
6. Run these commands in the console as shown below :

    > NOTE : Press Enter after writing each of these commands.
    
* `PM > enable-migrations `
* `PM > add-migration initialized`
* `PM > update-database`

7. Right-click **ShopBridge_WEBAPI** in Visual Studio.Then go to _**Properties > Web >** Copy the specified **Project Url**_.
---

* Right-click on **ShopBridge_WEBAPI** project. Click _**Set as Startup Project**_.
* Run the project by pressing **F5** in the keyboard.
---
## ✔ Usage

* User can add items in the **Inventory** section of the page.
* The added items are listed in the **List Inventory Items** section of the page.
* User can view the **item details** by clicking on **View** action button.
* Items can also be updated from the specified **Update** action button.
* Items can also be deleted from the specified **Delete** action button.

![Recordit GIF](http://g.recordit.co/333MvxfJqQ.gif)

---
## 🧪 Run Tests

* Go to _**Test > Test Explorer**_.
* Click on **Run All Test** icon.
---
## 🌐 Build

* In the Build Menu, change Configuration Manager from Debug to **Release**.
* Right-click on **ShopBridge_WEBAPI** project. Select **Publish**.
* Select **Folder** from list of Hosting options. Click **Next**.
* Choose a publishing directory. 
* Click **Finish**.
---
## 🕔 Time Tracking

* Backend Functionality - 4 hours
* Frontend Functionality - 6 hours
* Frontend Presentation - 1 hour
* Backend-Frontend Integration - 4 hours
* Unit Test Coverage - 5 hours

