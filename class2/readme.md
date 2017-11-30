# Class 2 Notes

## Agenda

1. Build a Site from Scratch.
  1. HTML - Write an entire HTML document with a header, banner, content area and footer.
  2. There will be pages Home, About and Contact.
2. CSS - Write all of the necessary CSS to make the site look awesome.
3. Learn about commenting
4. We are going to learn more about nesting in HTML.
5. We are going to learn a lot of things in css, including

## Itinerary

1. Make a file structure.  Files and folders should include:

```
Class2
|   |--images/
|   |--css/
|       |--styles.css
|   |--index.html

```
Launch the Index file in your web browser.

2. index.html

It should look something like this.

Try on your own based on googling and what we did last week to:
* add the DOCTYPE
* <html> then nest:
  * make a <head> with a <meta charset="utf-8">, a <title>, and a <link> to your stylesheet which is in the css file.
  * <body>

Here is what the final should look like.

```html
<!DOCTYPE html>
<html>

<head>

  <meta charset="utf-8">
  <title>My test page</title>
  <link rel="stylesheet" type="text/css" href="css/styles.css">

</head>

<body>
  <div class="wrapper">
    <header>
        <h1 class="header-logo"> <a href="#"> Title </a></h1>
      <nav>
        <ul class="header-navigation">
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
        </ul>
      </nav>
    </header>
    <div class="banner">
      <img src="images/chinle.jpg" alt="A sunset over Chinle">
    </div>
    <div class="content">
      <div class="first-section">
        <div class="column">
          <h2>Header</h2>
          <<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
        </div>
        <div class="column">
          <h2>Header</h2>
          <<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
        </div>
        <div class="column">
          <h2>Header</h2>
          <<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
        </div>
      </div>
      <div class="second-section">
        <h2>This is a header</h2>
        <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus</p>
        <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus</p>
        <h3>Header 3</h3>
        <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus</p>
        <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis. Ut felis. Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus</p>
        <img src="" alt="">
      </div>

    </div>
    <footer>
      <div class="left">
        <h1>Hellow</h1>
      </div>
      <div class="right">
        <img src="" alt="">
      </div>

    </footer>

  </div> <!--.wrapper-->

</body>

</html>

```
