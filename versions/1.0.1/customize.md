## If you haven't setup snake yet...
[Click here for instructions on setting up snake!](../../README.md)


## Skip to where you need to be...
- [Color Changes](#color-changes)
  - [PlayerColor](#playercolor)
  - [FoodColor](#foodcolor)
  - [Background Color](#background-color)
- [Game Changes](#game-changes)
  - [Rows](#rows)
  - [Columns](#columns)
  - [Block Size](#block-size)

## Color Changes

### PlayerColor (Default is white):
```
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
    rows: 20,
    playerColor: "red" // Default is white
})
```
### FoodColor (Default is cornflowerblue):
```
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
    cols: 10,
    foodColor: "blue" // Default is cornflowerblue
})
```
### Background Color (Default is gray):
```
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
    blockSize: 30,
    backgroundColor: "black" // Default is gray
})
```
## Game Changes

### Rows (Default is 20):
```
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
    rows: 10,
})
```
### Columns (Default is 20):
```
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
    cols: 10,
})
```
### Block Size (Default is 25):
```
const snakegame = new snakeGame({
    divElementId: "game-container",
    url: "ENTER YOUR URL OR SITE NAME",
    blockSize: 30,
})
```
