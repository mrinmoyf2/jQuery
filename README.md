# [jQuery]()JavaScript Library

## About jQuery

1. jQuery is a JavaScript framework.
2. jQuery greatly simplifies JavaScript programming.
3. jQuery is easy to learn.
4. jQuery is a fast, small, and feature-rich JavaScript library.

## How jQuery Works

This is a basic tutorial, designed to help you get started using jQuery. If you don't have a test page setup yet, start by creating the following HTML page:



```html
<!doctype html>
<html>
<head>
    <meta charset="utf-8">
    <title>Demo</title>
</head>
<body>
    <a href="http://jquery.com/">jQuery</a>
    <script src="jquery.js"></script>
    <script>
 
    // Your code goes here.
 
    </script>
</body>
</html>

```



The `src` attribute in the `<script>` element must point to a copy of jQuery. Download a copy of jQuery from the [Downloading jQuery](http://jquery.com/download/) page and store the `jquery.js` file in the same directory as your HTML file.

```note
NOTE: When you download jQuery, the file name may contain a version number, e.g., jquery-x.y.z.js. Make sure to either rename this file to jquery.js or update the src attribute of the <script> element to match the file name.
```



## [Downloading jQuery](https://jquery.com/download/#downloading-jquery)

## Build from Git

```note
NOTE: To just use the latest work-in-progress version of jQuery, please try the jQuery Pre-Release Build described above.
```

All source code is kept under Git revision control, which you can browse online. The repository's [README](https://github.com/jquery/jquery/blob/master/README.md) has more information on building and testing your own jQuery, as well as instructions on creating a custom build that excludes some APIs to reduce file size.

If you have access to Git, you can connect to the repository here:

```bash
1. git clone git://github.com/jquery/jquery.git
```

You can also check out and build a specific version of jQuery from GitHub:

```bash
1. git clone git://github.com/jquery/jquery.git
2. git checkout 1.2.6
```

The README file for a specific version will have instructions for building that version, as the process has changed over time.



## Other Ways

You can also use the slim build, which excludes the [ajax](https://api.jquery.com/category/ajax/) and [effects](https://api.jquery.com/category/effects/) modules:

1. [Download the compressed, production jQuery 3.4.1 slim build](https://code.jquery.com/jquery-3.4.1.slim.min.js)

* source - [jQuery download](https://jquery.com/download/)

1.

 ![Process_1](imgs\jQuery_download_1.png)



2. Save the file in your working folder.

 ![Process_2](imgs\jQuery_download_2.png)



* This Repo is just for jQuery .[ #100DaysOfCodes](https://www.100daysofcode.com/) 

