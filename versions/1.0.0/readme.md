# SnakeGameAPI
An easy snake game you can include in your website.

We also allow you to set the ammount of rows and columns. For all customization features, [Click Me](customize.md)

MOVE WITH ARROW KEYS! WASD IN NEXT UPDATE!

DOWNLOAD NEWEST SCRIPT VERSION: [Click Me](script.js)

# Code example/tutorial (you can copy this whole code):

```
<!DOCTYPE html>
<head>
    <title>Snake Game</title> 
</head>

<div id="game-container"></div>
<script src="script.js></script> <!-- Download the script and upload it in the same folder; the script is linked at the top of this document. -->

<script>
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
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
<script src="script.js></script> <!-- Download the script and upload it in the same folder; the script is linked at the top of this document. -->
```
Then, initialize a new snake game:
```
<script>
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
})
// We also allow you to set the ammount of rows, columns, and a ton of other settings. For all customization features, click the link at the top of this page.
</script>
```
THAT'S IT!
