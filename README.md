
![img](https://upload.wikimedia.org/wikipedia/commons/0/01/CanvaScript.png "a tite")
# Welcome to CanvaScript
CanvaScipt is a library for Java.it enabling Java as a sever-side langange.it's lighter JSP(if you are wondering)if you have issues please go to
https://github.com/CleanCode-backup/CanvaScript/issues
and make a new issue.also if you can  do a pull request please do that.that will make my day 😊!you can go to
https://github.com/CleanCode-backup/CanvaScript/pulls for that.
# Tutorials - Learn More 
Welcome to the To Tutorials,for full documentation go to the <a href="Docs.md">Docs</a>
in order to use the libary use th <code>import cavnascript</code>
## Creating a HTML page
first Let's Create a HTML page that Java can use. 
 
<code>
import canvascript.doc.htmldoc;
 class examlpe001{
 htmldoc page = new htmldoc();
 <b>htmldoc.CreateHTML(pagePath,pageName,pageTitle,);</b>
 htmldoc.CloseHTML();
 }
</code>
the <code><b>htmldoc.CreateHTML();</b></code>it takes a few string parameters. pagePath is the folder of the page. next pagePath is the name of the page. then pagePath is the text in the <code>&lt;title&lt;</code>. now Metatags. you only need put <code>&lt;meta charset="UTF-8" /&lt;</code>. the function creates the page but not fully,enable other functions to add code.this is when <code>htmldoc.CloseHTML();</code> come in. it close the file.
