# One Pager Tutorial

This is a tutorial on how to build a simple one pager website using vanilla html css and javascript.
<h2>Part One</h2>
1. Setup a new repository - remote and local

2. Open in VS Code

3. Connect the remote and the local version typing git remote add my-github https:/github.com/my-user-name/one-pager.git

4. Push Master branch and set it up as an upstream git push -u my-github master

5. create a new branch called setup and check it out

6. Create a file structure which can look like this: /index.html /style.css /README.md /LICENSE

- add the boilerplate to index.html
- create links to your css file
- choose a license from choosealicense.com and insert to LICENSE file

<h2>Part 2</h2>
1. HTML Structure

- create a new branch called HTML
- introduce your html structure for each section
- like this:

```
<body>
 <header></header>
 <main></main>
 <footer></footer>
</body>
```

1. Then foucs on the sections within

```
<section id="banner">
  <div class="section-inner-container">
    <div class="banner">
      This is where the content for the section will go
    </div>
  </div>
</section>
```

1. Create a banner, about, elements, showcare, and contact section
1. Create div classes for each section

<h2>Part 3</h2>

1. Create your styling
2. Normalize overall styling
```
* {
  padding: 0;
  margin: 0;
  outline: none;
  box-shadow: none;
  box-sizing: border-box;
}
```
3. Create a color theme
```
:root {
  --theme-color-primary: #5b88b4;
  --text-color-primary: rgb(8, 8, 8);
  --text-color-medium: rgb(131, 130, 129);
  --text-color-light: rgb(250, 248, 248);
  --bg-color-light: rgb(252, 245, 245);
  --bg-color-secondary: rgb(242, 245, 246);
  --bg-color-dark: rgb(58, 56, 56);
}
```
4. Works on the body, headings, and paragraphs
5. Style your links
6. Style your buttons
7. Style your sections

<h2>Part 4</h2>
1. Work on your navigation bar

```
<nav>
  <div class="navigation-logo"><i class="fas fa-adjust"></i></div>
  <div class="navigation-menu-desktop">
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#elements">Elements</a></li>
      <li><a href="#showcase">Showcase</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </div>
</nav>
```

<h2>Part 5</h2>
1. Work on the responsive layout

```
@media (max-width: 600px) {
  h1 {
    font-size: 2.5rem;
  }
  h2 {
    font-size: 1.2rem;
  }
  h3 {
    font-size: 1.8rem;
  }
  h2 {
    font-size: 1.2rem;
  }
}
```
2. Get rid of the navigation bar at a specific width

```
@media (max-width: 600px) {
  .navigation-menu-desktop {
    display: none;
  }
}
```
3. Specify the split font-size
4. Make the footer {flex-wrap; wrap}

<h2>Part 6</h2>
