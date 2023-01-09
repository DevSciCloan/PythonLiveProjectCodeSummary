# Python Live Project Code Summary
---

**Introduction**
------------
>
>[![An old rock in the desert](https://raw.githubusercontent.com/DevSciCloan/PythonLiveProjectCodeSummary/main/images/Introduction.PNG "Home page with basic description.")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/Introduction.PNG)

***

**CRUD Functionality**
------------------

>[![Create function](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/GenericCreate.PNG?raw=true "Generic Create Function Code Snippet.")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/GenericCreate.PNG)  
[![Update function](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/Update.PNG?raw=true "Generic Update Function Code Snippet.")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/Update.PNG)  
[![Delete function](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/Delete.gif?raw=true "Delete Function gif.")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/Delete.gif)  
***

**Create**
------
>[Story 2: Create your model]  
I created two models. One model contains all the Secret Santa groups that users can join. The second model contains information on each user profile that is created. The Person, i.e. user model, also contains a forgeign key to the Group model.
***
**Read**
----
>[Story 3: Display all items from database]  
To display all the items from the database I decided to make a page where a user can see a list of all the members of their group. This is done by using Django tags to filter all users in the Person table from the database that have the same group ForeignKey.  

>[Story 4: Details page]  
My details page is found by clicking on the gear icon next to a user's name on the page that displays all members of a group.

***
**Update**
-----------------
>[Story 5: Edit and Delete Functions]  
[![Delete User](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/Delete.gif?raw=true "Delete User example gif.")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/Delete.gif)  
[![Change Groups](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/ChangeGroups.gif?raw=true "Change Groups example gif.")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/ChangeGroups.gif)  
***
**Web Scraping**
------------
>[Stories 6 & 7: Beautiful Soup]  
I use BeautifulSoup to scrape images from a wishlist on [Amazon](https://amazon.com). Users can submit their share links for their Amazon Wishlist from their profile page.  
[![User profile wishlist link entry form](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/WishlistProfile.PNG?raw=true "User profile wishlist link form png")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/WishlistProfile.PNG)  

>[Story 9: Save Scraped results]  
[![Saved Scrape Results](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/UserWishlistSaveData.PNG?raw=true "Saved scraped results png")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/UserWishlistSaveData.PNG)
***
**Front End Development**
---------------------
>[Story 8: Front End Improvements]  
I utilized Django tags to set active CSS styling to the navigation bar tabs.  
[![HTML Django tags for front end improvements](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/NavBarHTML.PNG?raw=true "HTML Django tags for front end improvements png")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/NavBarHTML.PNG)  
I used CSS to add some animation to google material symbols on the homepage and the gears to link to the details page. This helps the user identify where they can or should click.  
[![HTML Django tags for front end improvements](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/NavBarHTML.PNG?raw=true "HTML Django tags for front end improvements png")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/NavBarHTML.PNG)  
***
**Choose Your Own Adventure**
---------------------
>[Story 10: Choose Your Own Adventure]  
I added a function to assign Secret Santas to each user of their group.  
[![Assign Secret Santa gif](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/AssignSanta.gif?raw=true "Assign Secret Santa gif")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/AssignSanta.gif)  
A group must contain an even number of users to make sure each person can be assigned a Secret Santa.  
[![Assign Secret Santa Error gif](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/EnsureSanta.gif?raw=true "Assign Secret Santa Error gif")](https://github.com/DevSciCloan/PythonLiveProjectCodeSummary/blob/main/images/EnsureSanta.gif)  
***
