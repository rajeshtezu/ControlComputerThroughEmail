# ControlComputerThroughEmail

This program is only for one specific task which is downloading movie through email.  
The program does the following:  
* It checks your email every 10 minutes 
* Find a mail with a password in subject of mail and torrent link as mail body
* Launches qBitTorrent with the given torrent link and starts downloading the given movie link
* Delete the mail so it won't download the same movie again
* Post completion of downloading it sends a success email to the sender

Make sure to set your qBitTorrent to automatically close after completion of downloading.  
I recommend to create a separate gmail account for this and don't forget to make this account less secure.


### Clone this project:
```
git clone https://github.com/rajeshtezu90/ControlComputerThroughEmail.git
```
### Install the requirements
```
pip3 install -r requirements.txt 
```
### Running the code
```
python3 emailMovieDownloader.py
```

Now you can send mail to your specified Email and this code will download movies for you.

Feel free to modify and make this code to automate other work.



