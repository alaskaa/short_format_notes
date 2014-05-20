---
title: Creating an HTML page
---

One of the nice things about HTML is you don't need a lot to test it out on your laptop: all you need is a text editor and a web browser.

{% exercise %}  
1. Inside your `coding_course` folder create another folder called `first_site`.  
2. Open Sublime Text.  
3. Write "Hello"  
4. Save the file as `index.html` in the `first_site` folder  
5. Open `index.html` in Chrome. Depending on your version of Chrome  
    * File > Open ...  
    * Cmd-o (Mac) or Ctrl-o (Windows)  

{% endexercise %}

### Why index.html?

In the old days of the web, navigating a website was a lot more like moving around the folder system on your laptop. You'd go to a base site and there would just be a list of the files and folders available: an index. Because of this `index.html` is still the default file that a server will serve when you navigate to a folder in the web browser. 

{% exercise %}  
1. Go back to 'index.html' in Sublime Text.  
2. Change the text to  
{% highlight html %}
<h1>Hello</h1>
{% endhighlight %}  
3. Go back to 'index.html' in Chrome and refresh the page (Cmd-R)
{% endexercise %}

This is your first real html tag. It has an open and a close. It tells it to be a heading.
