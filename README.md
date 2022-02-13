# Mobile Application Development

## Exercise 6

1.	Create your db handler class extending SQLiteOpenHelper. This class will create a new database upon initialization. There is a User table, whose structure follows the User class diagram. 20 User data are generated and inserted into the table. The name, description and value of Followed are randomized, the value of id is an auto-increment primary key.

![This is an image](/images/userclass.png)

![This is an image](/images/database.png)

2.	Create a getUsers() function in your db handler. This function will return all users’ information from the database as a List. Modify your RecyclerView so that it is pre-populated with information from the database only.

3.	Create a updateUser() function in your db handler. This function will receive a User object and update the corresponding value in the database. Modify your MainActivity so that it calls this function to update the database every time the Follow/Unfollow button is clicked.

4.	If all the above have been modified successfully, changes made to the user profile will be saved persistently. Test your app to verify this behavior.

5.	Remove the intent-filter for the MainActivity from the manifest. This will allow the user to launch your app via the ListActivity only.
