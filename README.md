# Google_drive_project

Automation Script which downloads file from Google Drive using API's , Python .


Basically the project contains Automation scripts which can be used to download files from Google drive.
Before starting with API , need few configurations like Creating Project , enabling API , Generating Client ID , Client Secret key , Access Key .

So one can refer :``` https://www.youtube.com/watch?v=kFR-O8BHIH4&t=235s``` Tutorial for basic setup on Google Cloud Platform which enables us to access all the details using API.

Once Everything is generated , can refer few documents from : ```https://developers.google.com/drive/api/v2/reference``` for API details which has all the details about File Operations Under Files section.

#Pre-requisites :


In order to run the automation script Python2.7 and pip should be pre-installed and below libraries should be installed using :

 ```pip install -r requirements.txt```


IDE: PyCharm, Visual Studio Terminal(MacOS) & Command Prompt(Windows)

Steps to run the Automation Script

1.Cloning the repo from GitHub
 ```https://github.com/rajeevpatil24/Google_drive_Project```.

2. Go to the path where above repo has been cloned, open the repo in an IDE Open terminal in IDE / on Terminal of your Mac / Command Prompt in your windows  and run below command :

	: ```python Test_Suites/File_downloader.py profile_pic.jpg abc.docx```   (Python Scriptname Filename (Mutiple Filenames))

Files will be downloaded under root directory (in this case it's Gdrive_Python path) then updated / latest files with changes applied will be stored under Updated directory.
