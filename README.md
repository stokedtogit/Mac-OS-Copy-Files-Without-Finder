Downloading: Click on the Photo.Copy.zip in the list above then click the 3 dots on the far right. Click Download. 

After you unzip the file, you will need to tell Mac OS to no quarantine it. To do this, open terminal and enter "xattr -d com.apple.quarantine " and then drag the unzipped file into the terminal window. Hit enter and you will be able to run the file. 

Q: Why do I need to do this? 
A: Mac OS requires apps to be signed in order to be considered authentic or safe. Because this was built as a shell script, there's no signing included. Running the command above ensures it can run. 
