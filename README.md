SHOP PRODUCT FINDER

About:This is an App that shows a customer if a particular grocery shop has a particular product they want to buy. It comprises of a customer interface, admin and inventory interface. It has Frontend of HTML, Javascript, Boothstrap and Css and a Backend of Flask and mysql database. The customer registers/logs in, finds the product they wish to buy and the shops that have the product. It also shows the customer the closest shop to get the product. The admin also uses it to know which products that need restocking.

Target User Groups: The main Target group are the customers, followed by the sellers

The Problem: Many atimes we need a product but we do not know the particular shop to buy it from. We end up going to several shops and sometimes giving up before getting to the particular shop. This problem mainly arise when we do not want to order these goods online as a result of urgency or as a result of need to see, touch and examine the product from a closer perspective. E.g, I remember moving to 3 different shops looking for Peanut butter before finding it afetr 3 hours. I also asked a group of 6 students in Pfarrkirchen who said their biggest shopping challenge is knowing the shops that have what they want. The challenge of transporting themselves takes their time. Two of them said they have resorted to online ordering where the products take even more time to arrive.

Solution: This App helps a customer know the exact shop to find the product they want. It also helps them know the closest one to find it.

Market Analysis: This App will greatly replace online ordering as it saves the customer time, cost of movement and energy. Also it satisfies customer need to see, feel and examine the product. I see this App being a great success.

User Aims and Objective: (1) To find the shop that has the product they want. (2) To know the closet shop they can find the product. (3) To know the number of product they want still left in the shop. (4) To know the amount the product costs. (5) To help the customer have a closer look and feel of the product without spending much time going from shop to shop. (6) To assist the seller in inventory and restocking.

Features: Frontpage(Registration, Login, Product search and images). Backend(Database and Flask API)

How to use: Register/Login, then check the product you want.


READ ME FILE:

INSTRCUTUONS

For VS-code
1. Open xampp and start Apache and Mysql
2. Go to New
3. Create the database name 'shop_product_finder'
4. open the database
5. Go to import option and choose the 'shop_product_finder.sql' file
6. Open Folder 'Shop Product Finder' with VS-Code
7. Open New Termial in VS-Code
8. Open PowerShell as an administrator. Right-click on the PowerShell icon and select "Run as administrator."
9. Check the current execution policy by running the following command:'Get-ExecutionPolicy'
10. If the current execution policy is set to Restricted, you can change it to RemoteSigned to allow local scripts to run. Run the following command:Set-ExecutionPolicy RemoteSigned,   type [Y] from Keyboard.
11. Write 'env\Scripts\activate' [Note: You Need configure the Python enviorment in systemn and vs-code]
12. e.g. Example [(env) PS C:\Users\User\Documents\Shop Product Finder>]
13. Now install all the necessary libraries e.g.Example [(env) PS C:\Users\User\Documents\Shop Product Finder>pip install -r requirements.txt]
14. Change the port numeber as per you 'xampp' configuration here it is 3307.
15. Now Write: python app.py e.g.Example [(env) PS C:\Users\User\Documents\Shop Product Finder>python app.py]
16. Open the Link: http://127.0.0.1:5000
17. You will see the Login Page


For Pycharm
1. Open xampp and start Apache and Mysql
2. Go to New
3. Create the database name 'shop_product_finder'
4. Open the database
5. Go to import option and choose the 'shop_product_finder.sql' file
6. Open Folder 'Shop Product Finder' with Pycharm
7. Open the app.py file
7. Change the port numeber as per you 'xampp' configuration here it is 3307.
8. Run the app.py 
9. Open the Link: http://127.0.0.1:5000
