# mapping-example

**A guide to having multiple mappers work on the same map file using Open Orienteering Mapper and Github**

- [Introduction](https://github.com/henrikopersson/mapping-example/blob/main/README.md#introduction)
- [Instructions and how-to](https://github.com/henrikopersson/mapping-example/blob/main/README.md#instructions)



## Introduction
*Mapping togheter on same map file, is that possible? Yes with Github only changes to the actual map file will be saved.*



**Who has the latest version of you map?**


When making orienteering maps there is common issue, who has the latest version? 

Normally you save your mapping files in a shared storage like Google Drive, Dropbox etc and let other people access that map. That is fine when you have an actual version of the map ready for competitions or training. But when working on the map together with others or sharing to other people during the work, you don't need to care who has the latest version of the map. Github has always latest version.



**What happens if mappers draw on the same area?**

But using Github is not solving all your problems. Still there could be issues if mappers draw on the same area. So before you start let the other collaborators know which area you are supposed to map to prevent mapping issues. What issues can happen and there will be some information further down this page that you could do if someone owerwrite your mapping area.

**Using XMAP format in Open Orienteering mapper is mandatory with Github**

When making a new map or revise your current map there can be multiple collaborators working with the same map if the map file is saved in the XMAP format in Open Orienteering Mapper. If you save your file in the OMAP format, mapper compacts the file and the file that not be read with Github to merge changes to the map. Same for OCAD files. 

Since XMAP is an XML format, the file is saved in a clear text format.

![bild](https://user-images.githubusercontent.com/72732333/196690935-b5aafcdf-f917-42ca-a27e-608df78b1ef0.png)





## Instructions
- [Setting up your Github account and use Github Desktop Client](https://github.com/henrikopersson/mapping-example/blob/main/README.md#setting-up-your-github-account-and-use-github-desktop-client)
- Create a new repository
- Adding members / collaborators
- Clone repository
- Push and pull files from Github
- Creating example map and push to Github
- Q & A


## Setting up your Github account and use Github Desktop Client

### Signup for a Github account
1. Go to https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home
2. Enter your email address and continue to create an account
![bild](https://user-images.githubusercontent.com/5741093/195793640-6c245635-78fc-4e6f-9edd-be6afd486431.png)
3. When your account is created and you have verified that you can login to Github continue to setup Github Desktop Client

### Setup and run Github Desktop Client
1. Go to https://desktop.github.com/
2. And download the Github Desktop client and install it on your computer by running the GitHubDesktopSetup file
3. Upon installtion, select to signin to Github
![bild](https://user-images.githubusercontent.com/5741093/195795570-89f19c40-9c16-459f-b813-ca3e457ba48f.png)
4. In the web browser allow Github Desktop Client to allow open up access to Github signin
![bild](https://user-images.githubusercontent.com/5741093/195796075-cba42037-a44b-49a6-82b5-f698089a693e.png)
5. After succesful login the Desktop client will ask you if you want to use your current name and email address or specify one manually. After you have verified either your address is correct or entered one manully click Finish.
![bild](https://user-images.githubusercontent.com/5741093/195796498-bdc164be-296b-49ae-8555-863c6e818730.png)
6. Now you are done with installing Githu Desktop Client
![bild](https://user-images.githubusercontent.com/5741093/195796809-cf0efbb6-f996-4c76-8ef2-0425c10d15c0.png)

## Create a new repository

1. Go to your Github account in your web browser
2. Click on the link Repositories
![bild](https://user-images.githubusercontent.com/72732333/196682951-5dfd0f83-a873-4755-8006-595b16bf3725.png)
3. Click New to crate a new repository
![bild](https://user-images.githubusercontent.com/72732333/196683052-5da052bd-3c92-4856-8a17-5f6873359270.png)
4. Fill in:
Repository name: your map name or the collection of your maps or something else
Description: Some information about your repository
Public/private: For mapping I would suggest to use private since you most likely working on something that might be private
Readme file: can be useful, to write about your repository, which maps etc.
Gitignore template: none
License: none
Create repository
![bild](https://user-images.githubusercontent.com/72732333/196683937-6a83f41c-1151-4a3a-99f7-2941dc5adf00.png)

5. Repository is now created. Either jump to section how you start working with your repository or add members/collaborators

## Adding members / collaborators
Click settings on your repository
![image](https://user-images.githubusercontent.com/5741093/196257378-d7f75f4b-203d-4266-98c6-d06b7dbaddaf.png)

Click collaborators
![image](https://user-images.githubusercontent.com/5741093/196257491-deef829e-2f54-4e29-a58e-43ee5e1c9295.png)

Check who has access and invite other people
![image](https://user-images.githubusercontent.com/5741093/196257579-edb3a702-9c1c-4d63-bc4c-3d1d0dde24c1.png)

Invite other
Either add their Github user account name or an email address. An invite will be sent to that user or email address
The user must accept the invite 
![image](https://user-images.githubusercontent.com/5741093/196257764-5ba7ee63-f162-4d05-bdb4-a3955ba26229.png)


## Creating example map

A simple map 
![image](https://user-images.githubusercontent.com/5741093/196256390-a757ce10-3f73-4bdc-868d-5aea1ec48b94.png)

Save it as a XMAP file to your folder structure where you keep your Github repository
![image](https://user-images.githubusercontent.com/5741093/196256611-4d49ad0b-b8cc-4b91-bfe3-8020f39c85bc.png)

Our map file is now saved as an XML file that Github can keep track of
![image](https://user-images.githubusercontent.com/5741093/196256975-177526c9-6828-4a0d-85b1-75af62c21b2a.png)


