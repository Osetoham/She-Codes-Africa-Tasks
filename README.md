# SCA Cloud Application School Exercise

This readme very clearly describes the test process and it's output, it also shows the instructions and documentaion used in this excercise.

**A droplet was created from ditigal ocean**


**Copying a file to the VM cloud, this command was used**

*scp -r thename-of-the-directory username@ip-address:thepath*

<img alt ='#' src='img/001.PNG'>

**Creating a user on my VM, this command was used**

*adduser the-name-of-user*

<img alt ='#' src='img/002.PNG'>

**Adding the public file of the user, an authorized_key file was created with vim and the pub key pasted in it**

<img alt ='#' src='img/003.PNG'>

**Creating a group, this command was used**

*groupadd name-of-group*
<img alt ='#' src='img/004.PNG'>

**Adding a user to the group, this command was used**

*usermod -aG name-of-group user*
<img alt ='#' src='img/005.PNG'>
<img alt ='#' src='img/006.PNG'>


**To confirm if in group, this command was used**

*cat /etc/group*
<img alt ='#' src='img/007.PNG'>
<img alt ='#' src='img/008.PNG'>

**To change group owner**

*chgrp new-group-name file-name*
<img alt ='#' src='img/009.PNG'>

**To give permission to for a group to write**

*chmod g+w name-of-file*
<img alt ='#' src='img/010.PNG'>
*Note: rwx means; read, write, execute*









