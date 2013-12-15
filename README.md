#Toggle Tests Service
####A Service for Mac OSX to toggle between Test code directory tree and Source code directory tree.

##Requirements:  
- Mac OSX (tested only on Mavericks)  
- PHP (tested only on 5.5)  
- command line tools (install through x-code)

##Installation:

1. Do either of the following:
  * Open `Toggle Tests-Source.workflow` and select `Install`  
  * Copy `Toggle Tests-Source.workflow` to `~/Library/Services`

2. Assign keyboard shortcut to service in `"System Preferences"->"Keyboard"->"Keyboard Shortcuts"->"Services"->"Files and Folders"->"Toggle Tests-Source"`.  
I suggest using `option`+`command`+`tab`

3. Run the service at least once through  
`"Finder"->"Services"->"Toggle Tests-Source"`  
(They keyboard shortcut might not work before this)

##Usage:

Organize your test files in a directory tree that mirrors that of your source directory tree.

###Usage Example:
  * All your source code files originate from the folder  
  `/Users/name/WebServer/fw/`
  * All your test files originate from the folder  
  `/Users/name/WebServer/fwTest/`
  * If you create a source code file named:  
  `/Users/name/WebServer/fw/fw_library/db/wrapper/MySQL.php`  
  the corresponding test file will be:  
  `/Users/name/WebServer/fwTest/fw_library/db/wrapper/MySQLTest.php`
  * Now in the folder
  `/Users/name/WebServer/fw/fw_library/db/wrapper`  
  you can hit `option`+`command`+`tab`, and the finder window will navigate to
  `/Users/userName/WebServer/fwTest/fw_library/db/wrapper.`  
  If you hit `option`+`command`+`tab` again, you will go back to the original folder.

I am a freelance software engineer, if this plugin is useful to you, please considder supporting me with a donation!

<a href='https://pledgie.com/campaigns/22419'><img alt='Click here to lend your support to: Support the software you use! and make a donation at www.pledgie.com !' src='https://github.com/anconaesselmann/ClassesAndTests/raw/master/images/donate.png' border='0' ></a>
