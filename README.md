# UAR-Deployment

What is the purpose of User Access Reviews?
- The purpose of user access reviews are to ensure that each user within an organization have authorized access
- Your directory needs at least as many Azure AD Premium P2 Licenses as the number of employees who will be performing the following tasks:
- - Users who are assigned as reviewers
- - Users who perform a self-review
- - Users as group owners who perform an access review
- - Users as application owneres who perform an access review

How do we create an User Access Review within Azure AD?

- Before creating the UAR, ensure that there is a group of users we want to perform the UAR review on. 
- Below is a group of three users, User A, User B, and User C

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167305196-c61578f9-3710-498b-85a0-253339ddecfd.png" height="100%" width="100%" alt="UAR"/>
  
<p/>

# Creating a User Access Review

- Search for Identity Governanace > navgiate to Access Reviews > create an Access Review

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167303937-4cfb5951-671b-4f51-9b7e-9b73aa2b7cca.png" height="100%" width="100%" alt="UAR"/>
  
<p/>

In the screenshot below, remember, licenses are required based on the option IT admins select.
If users review their own access, each user will need a license. If the group owner performs the UAR, the group owner needs a license.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167303837-073f64b6-8029-41c1-ac40-36d7f49e0c06.png" height="45%" width="45%" alt="UAR"/>
  
<p/>

In this case, admin A is the approver of the UAR so admin A will need just one license. <br>
Below, IT admins can specifiy the occurence of the User Access Review.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167303901-980a46ce-a547-42d1-80d4-0c0254a0f45d.png" height="45%" width="45%" alt="UAR"/>
  
<p/>



How to perform the User Access Reviews?
- Navigate to myapplications.microsoft.com and log in as the approver
- From there, select "My Access" from the drop down menu next to My Apps
- Select Access reviews 


<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167304661-eecb42a0-31df-42a0-b588-e9be205cd1b7.png" height="145%" width="145%" alt="UAR"/>
  
<p/>

Below, IT admins can approve or deny acccess

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167304680-db2a48a1-e0cd-4553-8861-e47fc51ebada.png" height="145%" width="145%" alt="UAR"/>
  
<p/>

Below, IT admins can biew the overview of the UAR that was created. Since User A and User B was approved to retain access to the group and User C was denied, once we stop the UAR and select Apply, User C will be removed from the group.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167304948-43639e19-1c5c-47a0-8f41-c1ed347c57e4.png" height="145%" width="145%" alt="UAR"/>
  
<p/>

User C, who was denied access to the group during the UAR, is removed from the group.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167305066-3a9ad560-a974-480b-a2e2-b8eea6b33d9b.png" height="145%" width="145%" alt="UAR"/>
  
<p/>








