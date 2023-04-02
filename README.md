# SnakeGameAPI
An easy snake game you can include in your website.
We also allow you to set the ammount of rows and columns. For all customization features, [Click Me](customization/readme.md)

DOWNLOAD NEWEST SCRIPT VERSION: [Click Me](versions/1.0.0/script.js)

# How to install:
Entire code example (below will explain each of the parts of code): 
```
<head>
    <title>Snake Game</title> 
</head>

<div id="game-container"></div>
<script src="script.js"></script> <!-- Download the script, and link it in the html. -->

<script>
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "gamesforus.com",
})
// We also allow you to set the ammount of rows, columns, and a ton of other settings. For all customization features, click the link at the top of this page.
</script>
```
# The Code Explained (above is the entire code)
Include our script:
```
<head>
    <title>Snake Game</title> 
</head>
```
Make sure that the divElementId that you initialized with the script actually exists on the page:
```
<div id="game-container"></div>
<script src="script.js"></script> <!-- Download the script, and link it in the html. -->
```
Then, initialize a new snake game:
```
<script>
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "gamesforus.com",
})
// We also allow you to set the ammount of rows, columns, and a ton of other settings. For all customization features, click the link at the top of this page.
</script>
```
THATS IT!
