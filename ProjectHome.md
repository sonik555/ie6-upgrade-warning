The ie6-upgrade-warning is a little script (7.9kb) that displays a warning message politely informing the user to upgrade the browser to a newer version (links to newest IE, Firefox, Opera, Safari, Chrome are provided).

The webpage is still visible behind a transparent background, but access to it is prevented. The idea is to force users to upgrade from IE6 and avoid the website from a bad reputation that website is not rendering correctly in IE6.

The script is completely translatable in any language, very easy to set-up (one line of code in webpage and one parametter configuration).

![http://ie6-upgrade-warning.googlecode.com/svn/trunk/example.png](http://ie6-upgrade-warning.googlecode.com/svn/trunk/example.png)

An example of the warning message produced


## Installation ##
Just insert the line
```
<!--[if lte IE 6]><script src="js/ie6/warning.js"></script><script>window.onload=function(){e("js/ie6/")}</script><![endif]-->
```
right after the `<body>` declaration of the webpage and change the `e("js/ie6/")` to the folder where the script's icons images are located.




More translations are available over [here](http://code.google.com/p/ie6-upgrade-warning/w/list)

_Any translations of the script's initial messages are welcomed._