# One Pager Tutorial

This is a tutorial on how to build a simple one pager website using vanilla html css and javascript.

1. Setup a new repository - remote and local

2. Open in VS Code

3. Connect the remote and the local version typing git remote add my-github https:/github.com/my-user-name/one-pager.git

4. Push Master branch and set it up as an upstream git push -u my-github master

5. create a new branch called setup and check it out

6. Create a file structure which can look like this: /index.html /style.css /README.md /LICENSE

- add the boilerplate to index.html
- create links to your css file
- choose a license from choosealicense.com and insert to LICENSE file

7. HTML Structure

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

8. Then foucs on the sections within

```
<section id="banner">
  <div class="section-inner-container">
    <div class="banner">
      This is where the content for the section will go
    </div>
  </div>
</section>
```

9. Create a banner, about, elements, showcare, and contact section
10. Create div classes for each section
