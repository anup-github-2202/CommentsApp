# CommentsApp

# In order to run the CommentApp Application please do the following steps:

# step1:
install "Angular CLI" and "VisualStudio 2022" to your local machine.


# step2:
open "CommentAppBackend.sln" solution (placed under CommentAppBackend folder) in visualStudio 2022.


# step3:
in VisualStudio click on view->"SQL Server Object Explorer".


# step4:
right click on the server "(localdb)\MSSQLLocalDB" from "SQL Server Object Explorer" and select new query.
# 	Note:
	please change local server name given in line 30 of the file "CommentsAppDBContext.cs"(placed under Models folder of "DataAccessLayer" Project)
	incase "(localdb)\MSSQLLocalDB" is not your local server name .


# step5:
Execute SQL scripts(given in the SQL_SCRIPTS.txt file) in the query window of visualstudio.

# step6:
right click on "WebServices" project and set it as startup project.

# step7:
run the application in the VisualStudio.

# step8:
open "Angular CLI" and change the root directory to the folder "CommentAppUI" by executing the "cd <folderpath>" command.

#  step9:
executing the command "ng serve -o" in Angular CLI to run the complete application.
