Good day.

Welcome to my database instructions.

To view and manage the database using a web application, follow the steps:

1.	Open the file inside the "1. Run in Microsoft SQL Server Studio" folder in Microsoft SQL Server Studio and execute it.
	The database Digital_Matter_Devices is created. Tables are created, and links are established. The tables are also populated.
2.	Copy the project inside the "2. Open Project in Visual Studio" folder to the "repos" folder typically located at "C:\Users\xxxx\source\repos".
3.	Open the copied project in Visual Studio.
4.	Establish a connection with the Digital_Matter_Devices database. To establish the Data Connections:
		-Right-click on the data connection.
		-Select "Add Connection".
		-In the server name field, insert ".\SQLEXPRESS".
		-Make sure Windows Authentication is selected and "Trust Server Certificate" is ticked.
		-In the "Select or Enter Database" field, insert "Digital_Matter_Devices".
5. 	Check that the connectionString = "Data Source=.\\SQLEXPRESS;Initial Catalog=Digital_Matter_Devices;Integrated Security=True;TrustServerCertificate=True". To confirm 
	the connectionString :
	- Right click on the created data connection.
	- Select Properties
	- On the bottom right of the screen the Connection String should be vissible.
	- If the Connection string is not "Data Source=.\\SQLEXPRESS;Initial Catalog=Digital_Matter_Devices;Integrated Security=True;TrustServerCertificate=True" 
	(Note spaces should be removes between TrustServerCertificate) update the connectionString variable to the new Connection String in all .cs files. 
6.	Run the program using IIS Express.
7.	The web application home screen should open.

Let me know if you need any further adjustments or additional information!
adriaanvanniekerk2@gmail.com






