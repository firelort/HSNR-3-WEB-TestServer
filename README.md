# Work in Progress
Unfinished ReadMe for Windows since I haven't set it up on a Windows machine. I try to get this done asap.
## Web-Engineering at the University of Applied Since Niederrhein
This repo contains all files needed for the test set-up of the python webserver, which is needed for the interships.
## Information
### Linux
1. Since you have to use **python3.5** or higher, you have to use **python3** and not python in the command line.
2. If you haven't installed git yet, please install it with `sudo apt-get install git`

### Windows
1. Please do **not install** the test server on the **desktop**, create a folder for example in your user folder.
2. In order to use git, please install the git comamnd line from https://git-scm.com/downloads

## Software required
1. Python 3.5 or higher
    - Linux: "sudo apt-get install python3"
    - Windows: Following soon!
2. cherrpy (for webserver programming)
    - Linux: "sudo apt-get install python3-pip && pip3 install CherryPy"
    - Windows: Following soon!
3. Browser of your choice
    - Recommended by the professor is "FireFox" with the Addon "Web Developer Tool".
    - All other modern browsers should be working fine as well. Please dont use Edge or Internet Explorer
4. IDE (Development Environment)
    - WindIde Personal
        - It is available free of charge at http://www.wingide.com/downloads/wingide-personal. Please use at least Version 6.
    - PhPStorm
        - It's part of the education packet of JetBrains, which you get free as a student of our University.
        - A python plugin is also avaible.
    - Visual Studio
        - Visual Studio Code is free useable with a mircosoft account.
        - Please use the extension "Python".
5. Editor (optinal, only a short overview)
    - Linux / MacOS: Sublime, Atom 
    - Windows: notepad++, Sublime Text, Atom

## Get the files
1. Open your terminal.
    1. Linux: The standard terminal is sufficient.
    2. Windows: Please open `git bash`.
2. Head to the destination, where the test server should be installed.
3. Run `git clone git@github.com:firelort/HSNR-3-WEB-TestServer.git`.
4. Your termianl should download the files and a new folder called HSNR-3-WEB-TestServer should be thier.
5. Go to the HSNR-3-WEB-TestServer folder.
6. Run `git checkout master`.
7. All done.

## How to use
1. Open your terminal.
    1. Linux: The standard terminal is sufficient.
    2. Windows: Please open `git bash`.
1. Head to your folder, where the content and the app folder are located.
2. Run the testserver&#46;py with `python3 testserver.py` in the terminal
3. Open the brwoser of your choice.
4. Head to [127.0.0.1:8080](http://127.0,0.1:8080)
5. There you should see the following: `Stellen Sie eine Anfrage an den Testserver: Anfrage`
6. If you clicked on `Anfrage`, a new page should open where you can see the installed cherrypy version.
7. If everything has been successful so far, you can view the requests from your browser. The requests will be displayed in the terminal.
8. Shut down the web server. Press `CRTL + C` in your termainl. The webserver should be off and you can use the terminal as usual.
9. Hurray all done!

## License
Please see the License&#46;md.
