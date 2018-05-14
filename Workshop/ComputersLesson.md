# Computer Lesson
## Software
[Text Editor: BBEdit](https://www.barebones.com/products/bbedit/download.html)   
[Markdown Editor: Typora](https://typora.io)   
[FTP Program: Cyberduck](https://cyberduck.io)
## Markdown
[Markdown](https://daringfireball.net/projects/markdown/syntax)
[Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)   
## Exporting to HTML
## Web Servers
## FTP
You should have received access to a folder on the newschool servers from IT services. If not you will need to get that information from them. Inside this folder (also known as a directory) is another folder named *public_html*. This folder is viewable online at the address you have received.

To access this folder and upload your site:   
**Option 1:** Use Cyberduck or other FTP program.
- Download an FTP program like Cyberduck.
- Set the mode to SFTP
- Input the correct name, password, and port number.
You can now upload files and folders.

**Option 2:** Use the Terminal
- Open the application _Terminal_ on your computer.
- Navigate to the folder containing your site's folder using the *cd*** command. example: cd Documents/school/creative\ computing/mySiteFolder
- You can check the contents of this folder with *ls* (list). The folder containg your site should be in this list of files and folders.
- Next you will access the remote folder with _sftp_. Type the following into the terminal and press return.
    sftp -P 222 yourUserName@b.parsons.edu.
- After entering your password you will be in the remote server. *ls* to list the contents of a folder. *cd public_html* to move into that folder.
- Now create a folder to hold your site by typing _mkdir yourSiteFoler_
- Move into the folder you created with _cd yourSiteFoler_
- Now you can use the *put* command. *put -R mySiteFolder. Your site is now online. and available at the http://b.parsons.edu/~yourUserName/yourSiteFolderi*
## Publishing 360° photo/video with A-frame
[A-Frame](https://aframe.io)
