**#File_Handling
**
**1.Extension wise:-
**

We all know that to organize all files manually,It's so boring and time taking task,all the files can be organise in a manner such that which extension it contains under that extension all the files will be organise with same extension and all the category such as videos and audios all the will come under that so lets start with extension wise 

In extension wise here,We need to import the required modules,such as here we imported os and shutil module,these are inbuilt modules, so don't need to install them And you need to create a variable called path which takes input of the directory path path for the files which you want to organised in you files And then create a variable called files,Which consists of a list of lines. Now write a for loop condition,Using for loop we traverse through every file from files,Then we spilt the filename and extension of the file,We only need an extension name so we remove the dot from the extension through slicing,And then we need write an if statementfor the the extension directly already exits, then we move the file to that directory or in else statement we make a new directory and then we move the file into it so here we are done with the extension wise after we will run thids progeam we will get all the files organised in the specific extension with all the extension in one file.

**2)category wise:-
**

So now secondly it's category wise as said above, the modules here are also same as extension only ,now we will again import os it's already inbuilt,then we will create a basepath variable for the input of paths for files to organize now we create a list in which which category we want to organize, here I have organized category as vedios images and many more now we use if loop here first we check that if videos are there then its will go to videos and so on in the videos I have entered mp3 and wav and many more so if this extension exist then it will go in that category now we will define function move items for folder after the defining the function we will take the if condition for os.path.basepath is not in list and then print the move folder for the def function after that if condition will check that extension file,for every list items for music here extension here consider are the mp3,wav for the video extension file are consider mp4 ,mov,mkv or you can add other file also whichever your choice the image extension file consider are png,jpg or other image type as well then  we will take the for loop for every list and than check with if condition if the extension is not consider in list then remove it this for loop and if condition are suitable on all item in list like video,image,music,file after the for loop and if condition end my program,so here we are done with category wise also so after we run this program we will get all the files in one category such as vedios in vedios,images in images and so on.
Thank You for viewing my file

