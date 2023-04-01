# SnakeGameAPI
An easy snake game you can include in your website.
We also allow you to set the ammount of rows and columns. For all customization features, [Click Me](customization/readme.md)
# How to install:
Include our script:
```
<head>
    <title>Snake Game</title>
    <script src="script.js"></script>
</head>
```
Then, initialize a new snake game:
```
<script>
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "gamesforus.com",
})
</script>
```
Make sure that the divElementId that you initialized with the script actually exists on the page:
```
<div id="game-container"></div>
```
THATS IT!
