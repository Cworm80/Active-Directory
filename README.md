# Active-Directory
-In this project i will show you how to create a Active Directory this will allow you to manage users and groups in your organization.

First you will need to get a copy of 2019 Server, you can either buy it  or download on the Microsoft Website
I will be using a VM, you also need download Virtual Box and download the extension https://www.virtualbox.org/
Once installed you will login with your account that you created during the setup.


<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/c290a065-522d-4042-8de5-e93bd2ed873a" width="700" height="500" >
<br>
<br>

This is where you can manage your server and add other roles which can be installed by going to, <b> Manage > Add Roles and Features, pick Role-based or features-based installation</b>

<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/95d1523c-226f-4886-b4f7-ad86a4182d07" width="700" height="500">
<br>
<br>


Then click next you will see this menu pop up, you see that its already been install on my computer, the one that is highlighted in blue and also install DNS server. 

<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/07cd8826-3c93-4a3d-9679-57ed40c1dd3d" width="400" height="400">

<br>
<br>

<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/989f2a19-c8f2-40a8-b5d6-0fd89286d87d">


<br>
<br>
<br>

Once finished the installation then you would want to to click the “Flag Promote this server to domain controller”.
Then next you would see a menu pop up <b>"Deployment Configuration"</b>
Add a new forest then type name of your domain Ex “mynamedomain.com”, then you would need to set a username and password for your domain.

<br>
<br>
<br>
<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/f14a8203-4779-469f-9664-a9c0ca4b5f6d" width="500" height="500">

<br>
<br>
<br>

<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/9bf740f8-a707-439e-aa3b-d7f6bdef4674" width="500" height="600">


<br>
<br>
<br>

Once finished click <b> Windows logo > Windows Administrator Tools >
Active Directory User and Computers.</b> 

<br>
<br>
<br>

Left side panel is where you manage your groups in an organization on the domain, from here you can add user to a group,
<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/4cf6f32d-c6e1-4792-b228-22791a318275" width="600" height="600"> <br>
<br>
You can create users and add them. <b>To do this right click on domain name > new > and choose option you want.</b>

<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/aad02b16-284a-4674-903b-edfc9c4f731d" width="700" height="400">

<br>
<br>
<br>

This is the user property, this shows all the information that we can fill out about the user, click account” settings click here this will show how to manage the user password options, you can set whatever options you want.

<img src="https://github.com/Cworm80/Active-Directory/assets/161678144/69756e5d-f3e8-4915-bdaf-138397cd2d09" width="300" height="400">

This is how you setup an Active Directory on a Virtual Machine.
