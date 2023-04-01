# SnakeGameAPI
An easy snake game you can include in your website.
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
