# html-for-degens
Breakdown of basic coding on pages that resemble web3 projects, ending with building the programs that work on the frontend pages they've built

To operate this code you need to have VS Code or another editor on your computer, I recommend having the Open Live Server extension downloaded, a github.com account, and you'll need to Fork the repo to your computer through the cli.

VS Code: https://code.visualstudio.com/download
Open Live Server Ext: https://www.youtube.com/watch?v=2fhe0LLj3Rw
Github account: https://github.com
Fork Repo: https://www.youtube.com/watch?v=p_uOrMNXOSk

Landing Page Breakdown
•	<!DOCTYPE html> - Specifies the type of HTML document.
•	<html lang="en"> - Defines the language of the page as English.
•	<head> - Contains metadata about the page, such as the page title, icons, links to stylesheets, etc.
•	<meta charset="UTF-8"> - Specifies the character encoding for the page.
•	<meta http-equiv="X-UA-Compatible" content="IE=edge"> - Specifies the compatibility mode of the page.
•	<meta name="viewport" content="width=device-width, initial-scale=1.0"> - Specifies how the page should be rendered on different devices.
•	<title>Frontend of My First dApp</title> - Specifies the title of the page, which appears in the browser tab.
•	<link rel="icon" href="img/fire1.jpg" type="image/x-icon"> - Links to an icon file to display next to the title in the browser tab.
•	<link rel="stylesheet" href="css/main.css" type="text/css"> - Links to a CSS stylesheet to style the page.
•	<body> - Contains the content of the page.
•	<header> - Defines the header section of the page, which includes the page title, navigation bar, and an image with a caption.
•	<nav> - Defines the navigation bar, which contains a list of links to different sections of the page or to other pages.
•	<ul> - Defines an unordered list, which is used to list the navigation links.
•	<li> - Defines a list item, which is used to hold each navigation link.
•	<a href="#profile">Meet The Dev</a> - Defines a hyperlink, which allows the user to navigate to a different section of the page or to another page.
•	<figure> - Defines a figure, which is used to display an image with a caption.
•	<img src="img/fire1.jpg" alt="Mint Preview" title="FirePic" width="400" height="267"> - Displays an image with the specified source, alternate text, title, width, and height.
•	<figcaption> - Defines the caption for the figure.
•	<hr> - Draws a horizontal line.
•	<main> - Defines the main content section of the page, which includes two articles with headings and descriptions.
•	<article id="profile"> - Defines an article section, which holds the profile information. The id attribute is used to identify the section for linking.
•	<h2>Cash Munsy</h2> - Defines a second-level heading for the profile section.
•	<p> - Defines a paragraph of text.
•	<a href="https://meme-race.com/">Meme Race</a> - Defines a hyperlink to the website for Meme Race.
<footer> - Defines the footer section of the page, which includes copyright information and links to related pages.
•	<p>Cach Munsy &copy;</p> - Displays a paragraph with the copyright symbol

Mint Page Breakdown:
•	<!DOCTYPE html> declaration to specify the HTML version used in the document.
•	<html> element with a lang attribute set to "en" to specify the language of the page.
•	<head> element that contains metadata about the page, including:
•	<meta charset="UTF-8"> declaration to specify the character encoding for the page.
•	<meta http-equiv="X-UA-Compatible" content="IE=edge"> declaration to specify compatibility with Internet Explorer.
•	<meta name="viewport" content="width=device-width, initial-scale=1.0"> declaration to specify the viewport properties of the page.
•	<title> element to specify the title of the webpage tab.
•	<link rel="icon" href="img/fire1.jpg" type="image/x-icon"> declaration to specify a favicon for the page.
•	<link rel="stylesheet" href="css/main.css" type="text/css"> declaration to link a stylesheet file to the page.
•	<body> element that contains the content of the page, including:
•	header with a <h1> element displaying "My First Mint UI" and a navigation <nav> element with two navigation links in an unordered list.
•	<main> element with a <h1> element displaying "Mint Your Ghost Gang NFT Below" and an image, and a <button id="mintbtn">mint</button>.
•	<footer> element with a <p> element displaying "Cash Munsy ©".

Swap Page Breakdown:
1.	<!DOCTYPE html>: This declares the document type as HTML.
2.	<html lang="en">: This sets the language of the page to English.
3.	<head>: This element stores metadata about the page, such as the character set, the title, the icon, and stylesheets, that are not displayed on the page itself.
4.	<meta charset="UTF-8">: This sets the character set for the page to UTF-8, which is the standard character set for webpages.
5.	<meta http-equiv="X-UA-Compatible" content="IE=edge">: This sets the internet to use the best version of the page possible.
6.	<meta name="viewport" content="width=device-width, initial-scale=1.0">: This sets the internet to render the page correctly on different devices.
7.	<title>: This sets the title of the page that is displayed in the tab.
8.	<link rel="icon" href="img/fire1.jpg" type="image/x-icon">: This links an icon to the page that is displayed next to the title in the tab.
9.	<link rel="stylesheet" href="css/main.css" type="text/css">: This links the stylesheet file to the HTML page, which defines the styles for the elements on the page.
10.	<body>: This element contains the content of the page, such as the header, main content, and footer.
11.	<header>: This element defines the header section of the page, which contains the title of the page and the navigation bar.
12.	<nav>: This element defines the navigation bar, which contains the navigation links.
13.	<ul> and <li>: These elements create a list of navigation links.
14.	<a href="/">: These are hyperlinks that take the user to the specified page when clicked.
15.	<hr>: This element creates a horizontal line to separate sections of the page.
16.	<main>: This element defines the main content section of the page, which contains the image and the form for swapping tokens.
17.	<section>: This element defines a section within the main content, which contains the image or the form for swapping tokens.
18.	<img src="img/gg2.png" alt="Ghost Gang" title="Ghost Gang logo" width="150" height="150">: This element displays an image on the page and defines its attributes, such as the source, alternative text, title, and size.
19.	<form action="" method="get" class="form-example">: This element creates a form for swapping tokens and defines its attributes, such as the action it should 


