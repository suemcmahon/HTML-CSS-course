# An introduction to HTML & CSS

## Table of Contents

1. [Set up](#setup)
2. [HTML](#html)
3. [CSS](#CSS)
4. [Styles](#Styles)
5. [Resources](#Resources)

### Setup

To get started you will need access to a computer with a web browser and a text editor.

Please follow this step by step guide and you will be well on your way!

#### Create a folder

Create a new folder on your desktop and name it 'html-css-ftw'. 

We will be using this folder to save our website.

[How to create a new folder on a Windows machine](https://support.microsoft.com/en-us/office/create-a-new-folder-cbbfb6f5-59dd-4e5d-95f6-a12577952e17)

[How to Create a new folder on a Mac](https://www.wikihow.com/Create-Folders-in-Mac)

#### Download a code editor

Open your usual web browser and visit the [Visual Studio Code website](https://code.visualstudio.com/)

Follow the instructions on the website to download for your computer.

Visual Studio Code is lightweight, should run on most computers and is free to download!

You are now ready to start building your first webpage! 

### HTML

Open the Visual Studio Code editor that you downloaded in the [previous exercise](#setup).

Create a new file and save the file as 'index.html' in the html-css-ftw you [created earlier](#setup).

Enter the markup below and press enter:

`<!DOCTYPE html>`

This is known as the doctype, which is short for Document Type Definition. This doctype tells the browser that we are using the HTML5 version and to interpret the HTML and CSS code according to W3C standards. Even browsers that don’t presently support HTML5 will enter into standards mode, which means they’ll interpret the long established parts of HTML in an HTML5-compliant way, while ignoring new features of HTML5 they don’t support.  It must be the first item on a web page, appearing before any spacing or carriage returns. 

Then, enter the following:

```html
  <html lang="en">
  </html>
```

This is the HTML element with an attribute called lang. The lang attribute is used to set the document’s language - in this case en for English. The HTML element is the outermost “container” of our web page; everything else (apart from the doctype) is kept within the HTML tags. 

Inside the HTML element, enter the following:

`<head></head>`

There are two major sections inside the HTML element: the head and the body. This is the head element, this contains information about the page, but no information that will be displayed on the page itself. 

Inside the head element, enter the following:

```html
  <meta charset="utf-8">
  <title>My first web page</title>
```

In the example above, the meta tag tells the browser which character set to use - specifically, UTF-8, which includes the characters needed for web pages in just about any written language. 

The title element tells the browser what to display in its title bar.

Underneath the head closing tag, enter the following:

```html
<body>
</body>
```

Everything inside the body element is shown inside the main browser window. 

Inside the body element, enter the following:

```html
  <h1>Welcome to my first webpage!</h1>
  <p>This is a paragraph.</p>
  <p>This is another paragraph.</p>
```

Here we have added the main heading element and two paragraph elements. 

This is what the final markup should look like inside your code editor:

```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>My first web page</title>
    </head>
    <body>
      <h1>Welcome to my first webpage!</h1>
      <p>This is a paragraph.</p>
      <p>This is another paragraph.</p>
    </body>
  </html>
```

Save your changes. Right click the index.html in the html-css-ftw folder and open with a web browser, for example Google Chrome. 

You should see your first webpage. It looks very plain at the moment, we'll change this in the next step!

### CSS

In Visual Studio Code editor create a new file and save it as style.css inside the html-css-ftw folder.

Congrats! You've created your first css file, now you need to link it to the index.html file you created earlier.

Go to index.html and add the following below the title tag:

```html
<link href="style.css" rel="stylesheet">
```

Your index.html file should now look like this in the code editor:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>My first web page</title>
    <link href="style.css" rel="stylesheet">
  </head>
  <body>
    <h1>Welcome to my first webpage!</h1>
    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>
  </body>
</html>
```

Go to style.css in Visual Studio Code editor.

Type the following and save your changes:

```css
body {
  background-color: red;
}
```

We are selecting the body element of the page and using the background-color property to change the background colour of the body to red. 

Now open up index.html in your web browser. Your page should now be bright red!

Don't worry, this is just a temporary style to check that the style.css file is linked correctly to the index.html file.

Go to style.css, delete the style you just added in the step below and save your changes.

Now go back to your web browser and refresh your webpage. The page should no longer be bright red (Phew!).

Next, you'll start adding some CSS properties. 

### Styles

Go to style.css in the Visual Studio code editor.

Type the following:

```css
body {
  font-family: arial, verdana, sans-serif;
  background-color: #1c1727;
}
```

This is changing the background colour of the whole web page and setting the font of the page to the arial typeface, if the arial typeface is not available then 'verdana' will be displayed.

Open index.html in your web browser and refresh the page, your webpage should now be a different colour.

Go to style.css and add the following:

```css
h1 {
  color: #339f94;
}
```

This is selecting the h1 heading element on your webpage and setting the colour of it.

Refresh index.html in your web browser, the heading 'Welcome to my first webpage!' should now be a different colour. 

Go to style.css and add the following:

```css
p {
  color: #bb3f76;
}
```


Refresh index.html in your web browser, the paragraph elements on your webpage will also be a different colour now! 

You have created your first styled webpage!

### Resources

This was a short intro to HTML & CSS. 

There are lots of free resources out there that can help you build on what you have learnt and hopefully inspire you to build some amazing projects in the future. 

Or if you are thinking of a career in tech why not have a try and get started with the links below!

[The story of your first website](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

[freeCodeCamp](https://www.freecodecamp.org/)

[Codecademy](https://www.codecademy.com/learn/learn-html)









