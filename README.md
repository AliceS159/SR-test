# How to run test html page on your local environement

The easiest way to run the test html page is to use module SimpleHTTPServer Python.

### **Install Python**

If you use Linux or Mac OS X it is already there.

To use it on Windows you can download it from Python home page:
* go to python.org
* go to “Download”, click "Latest: Python 3.xxx"
* at the bottom of the page choose Windows x86 executable installer, download and run the file
* on the first page of installer check the "Add Python 3.xxx to PATH" checkbox 
* click “Install” 
* click “Close” when installation is finished

To check the Python installation open your command line (Windows) or terminal (OS X/Linux) and write the command: `python -V`
If the system gives you correct Python version it was correctly installed.

### **Run test HTML page**
1. Use the `cd` command to go to a directory you will use
2. Add a test file into this directory and name it test.html
3. Put following code into this file
```html
<!DOCTYPE html>
<html>
<head>
<title>Example</title>
</head>
<body>
<p>This is an example of a simple HTML page with one paragraph.</p>
</body>
</html>
```
4. Write a command `python -m SimpleHTTPServer`, it will start the server in this directory
5. By default the directory contents will be launched on the local web-server on 8000 port. In your web browser you can go to this server by going to  URL-address localhost:8000. You’ll see the directory contents there.
6. Click test.html file
