# UAR-Deployment

What is the purpose of User Access Reviews?
- The purpose of user access reviews are to ensure that each user within an organization have authorized access
- Your directory needs at least as many Azure AD Premium P2 Licenses as the number of employees who will be performing the following tasks:
- - Users who are assigned as reviewers
- - Users who perform a self-review
- - Users as group owners who perform an access review
- - Users as application owneres who perform an access review


How do we perform an User Access Review within Azure AD?
- Search for Identity Governanace > navgiate to Access Reviews > create an Access Review

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167303937-4cfb5951-671b-4f51-9b7e-9b73aa2b7cca.png" height="100%" width="100%" alt="UAR"/>
  
<p/>

In the screenshot below, remember, licenses are required based on the option IT admins select.
If users review their own access, each user will need a license. If the group owner performs the UAR, the group owner needs a license.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167303837-073f64b6-8029-41c1-ac40-36d7f49e0c06.png" height="45%" width="45%" alt="UAR"/>
  
<p/>

Below, IT admins can specifiy the occurence of the User Access Review.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167303901-980a46ce-a547-42d1-80d4-0c0254a0f45d.png" height="45%" width="45%" alt="UAR"/>
  
<p/>



