# Exp3-webdev
# Weblayout using flexbox
## Aim:
To create a weblayout using flexbox.
## Algorithm:
1. Code all the necessary Css elements.
2. And connect it with the HTML page.
3. Then execute it.
4. Display the results.
## Code:
```
<!doctype html>
<title>Example</title>
<style>
  * {
    box-sizing: border-box; 
  }
  body {
    display: flex;
    min-height: 100vh;
    flex-direction: column;
    margin: 0;
  }
  #main {
    display: flex;
    flex: 1;
  }
  #main > article {
    flex: 1;
    order: 1;
  }
  #main > nav, 
  #main > aside {
    flex: 0 0 20vw;
  }
  #main > nav {
    background: #5633c7;
    order: 3;
  }
  #main > aside {
    background: rgb(73, 155, 180);
    order: 2;
  }
  header, footer {
    background: rgb(60, 125, 168);
    height: 20vh;
  }
  header, footer, article, nav, aside {
    padding: 1em;
  }
</style>
<body>
  <header>Header</header>
  <div id="main">
    <article>Article</article>
    <nav>Nav</nav>
    <aside>Aside</aside>
  </div>
  <footer>Footer</footer>
</body>
```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp3-webdev/assets/93427594/1e207bab-4007-43ac-97bf-337a4575ad80)
## Result:
Thus the code has been implemented successfully.
