## Lab 1

In this report we will look at how to log into ones course-specific account on ieng6. 
For this tutiorial it is expected that you already have a course account.

## Step 1: Code Editor
First we will download our code editor. We will be using vs code which one can 
download [here](https://code.visualstudio.com/download). When it is downloaded
it, open the application and you should see a screen similar to this: 
![VS code open](https://github.com/awnjike/cse15l-lab-reports/blob/main/VS%20pic.png)

## Step 2: Remotely Connecting
Now that we have our text editor open we can start connecting to our computer to the our 
course account. To connect first we are going to need to open up a terminal. In order to
do so go to the top left of the window and click on **View** and then click on **terminal** 
on the drop down (you could also use the command **Ctrl+`**). After the terminal is open
type in the terminal **ssh <your username>@ieng6.ucsd.edu>**, after this it will ask
*Are you sure you want to continue connecting*, in order to connect you should type 
**yes**. After you press enter you should see a message similar to this:
![VS terminal result](https://github.com/awnjike/cse15l-lab-reports/blob/main/ScreenshotTerm.png)

## Step 3: Trying Some Commands
If you have made it to this last step *congragulations you have fully connected!* However, you now that you are connected you should test out some commands. Below we have a few comands  you could run:
*cd ~
*cd
*ls -lat
*cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
*cat /home/linux/ieng6/cs15lsp23/public/hello.txt
an Example would be using *ls -lat* which outputs as followed:

![ls -lat output](https://github.com/awnjike/cse15l-lab-reports/blob/main/lslat.png)
