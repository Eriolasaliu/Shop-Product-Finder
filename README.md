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
