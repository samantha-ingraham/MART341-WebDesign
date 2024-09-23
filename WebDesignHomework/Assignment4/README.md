Explain how web browsers function. How do web browsers really work behind the scenes?

Web browsers function through a lot of different pieces. They communicate with servers, use interpreters, rendering engines, and data storage to make it possible for the user to interact with a website efficiently. Javascript is used to privide the user with functionality and interactability on the website, while HTML and CSS are used to animate, style, and structure our content on the webpage. The browser engine controls all of this and allows the user to have some functionality even outside the website they are viewing (such as the refresh buttons and back button). Cookies and local storage are used to help a browser and website keep your history on a given site, such as keeping the items you have in your cart **in** your cart when you refresh.

What is the DOM (Document Object Model), and how does it power your web pages? 

The Dom is a sort of tree-like structure that treats each *thing* in your html as it's own object that can then be modified or interacted with. It updates your html automatically, and you don't neccesarily interact with it directly. It powers webpages by providing them with a sort of elasticity, allowing them to change as the user uses the website. This dynamic content keeps our websites from needing to be static, which makes them more interesting and more useful in some cases. It also allows for interactivity through javascript, which can load new content/change content based off of say, a click of a button.

HTML, XML, XHTML—what sets them apart?

**The main difference** as far as I can see, between the three, is ease of use and ease of rendering. While HTML may be a very easy language to learn and use, it may not work across browsers the same way, and has particular trouble with mobile applications. XML, doesn't render anything, rather it is used to supplement info into html. XHTML is more complex, and more time consuming to use, but takes the best from xml and html to handle more varied situations, such as mobile applications.

What are the four essential elements every HTML page needs?

1) The <!DOCTYPE> declaration. - instructs the web browser on the html page's version is
2) The root element. - sort of anchors where the html is. situated outside all other content and tells the browser where all the html content is located.
3) The head element. -contains high level info for the website not usually visible to users. Title is a required element of head.
4) The body element. -container for all ~~your junk~~ your content and data.

What’s the purpose of the index.html page, and where should it be placed?

It should be placed in the root directory. It's the page a website automatically looks for when you type it's name in, and without it you will likely not be able to access a site.

Review: What are the top naming practices for clean and organized code?

**From the linked Video in mod 4**
1) Keep all files relevant to your website in the same folder.
2) Have a root folder containing the elements you'll upload to the web. Anything that is not directly related can still go in the parent folder, but wesbite elements only go in the root folder.
3) Your index page should go in your root folder by itself. it must always be named index.html
4) Do not include spaces or funky characters in your names for files, folders, etc. 
5) you can use camel casing for names that have more than one word, or underscores or dashes. i prefer underscores.
6) dont start file names with numbers. won't break anything just bad practice.
7) always include extension for file names
8) Sub pages should be placed in the pages folder. Images should be in the images folder, css and scripts should have their own folder, etc. all folders should be in the root folder.

**From what I found online for coding specifically**
1) Choose descriptive names
2) Use similar names for similar things. **doMath() doAddition() doBlahBlahBLah()** vs ~~doMath() completeAddition() finishBlahBLahBLah()~~
3) use pronouncable names **doMath()** vs ~~dmth()~~
4) use search friendly names **int sum = 0** vs ~~int s = 0~~

That is all the commonalities I was able to find online for code specifically, with people's opinion varying on things that **absolutely must be done** from there onward. 