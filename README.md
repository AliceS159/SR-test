# SR-test
The easiest way to run the test html pages is to use module SimpleHTTPServer Python.


If you use Linux or Mac OS X it is already there.

To use it on Windows you can download it from Python home page:
go to python.org
go to “Download”, click "Latest: Python 3.xxx"
at the bottom of the page choose Windows x86 executable installer, download and run the file
On the first page of installer check the "Add Python 3.xxx to PATH" checkbox 
Click “Install” 
Click “Close” when installation is finished

To check the Python installation open your command line (Windows) or terminal (OS X/Linux) and write the command: python -V
If the system gives you correct Python version you've just installed use the cd command to go to a directory you will use


Add a test file into this directory and name it test.html
Put following code into this file
<!DOCTYPE html>
<html>
<head>
<title>Example</title>
</head>
<body>
<p>This is an example of a simple HTML page with one paragraph.</p>
</body>
</html>



Write a command python -m SimpleHTTPServer, it will start the server in this directory

 

By default the directory contents will be launched on the local web-server on 8000 port. On your web browser you can go to this server by going to  URL-address localhost:8000. Here you’ll see the directory contents



Open test.html file in web browser

