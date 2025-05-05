Instructions for Running the MOCA Attendance Database


The source code has been provided with the understanding that it will be given to the University of North Florida’s IT department for them to host on their private server. It is temporarily being hosted at https://mocajaxappsvc.azurewebsites.net/

To log in on the Azure hosted app use:

Username: Master Password: MasterMOCALogin for Admin account
Username: Staff Password: staff for Staff account


This document will briefly describe how to launch and run the MOCA Attendance Database for the first time.


How to Set Up and Run the Application

1. Unzip the downloaded application files.

2. Open the project in Visual Studio (latest version recommended).

3. Enable Required NuGet packages:

(Visual Studio should prompt you to restore missing packages automatically. If not, go to Tools > NuGet Package Manager > Manage NuGet Packages for Solution and install missing packages manually.)

Required NuGet Packages (make sure these are installed):

1.	Microsoft.EntityFrameworkCore.Design

2.	Microsoft.EntityFrameworkCore.Tools

3.	Microsoft.EntityFrameworkCore.SqlServer

4.	ClosedXML

4. Apply Migrations:
Open the Package Manager Console (Tools > NuGet Package Manager > Package Manager Console) and run:

Update-Database

5. Run and Launch the application:
Press F5 or click Run in Visual Studio.

6. Login to the application:
A master account has been hard coded into the code files to enable access to the application with these credentials

	Username: Master 		Password: MasterMOCALogin
