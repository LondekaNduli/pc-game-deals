# Game Deals 

## About the Project

Game Deals is a simple web application that displays a list of video games with their normal prices and discounted prices.

The project allows users to search for games, filter games that are on sale and see which game has the lowest price.

I built this project using HTML, CSS and JavaScript as part of a practical development exercise.

## Features

- **Game Listing:** Displays eight games with their store names and prices.
- **Search Function:** Allows users to search for a game by its title.
- **Sale Filter:** Users can select a checkbox to display discounted games only.
- **Discount Calculation:** Calculates the percentage discount for each game.
- **Cheapest Game:** Identifies the cheapest game based on its sale price.
- **Live Updates:** Search results update as the user types.
- **Responsive Layout:** The page adjusts to smaller screen sizes.

## Technologies Used

- HTML – Used to create the webpage structure.
- CSS – Used for styling and layout.
- JavaScript – Used for the search functionality, filtering and price calculations.
- Visual Studio Code – Used as the development environment.
- Live Server – Used to run and test the webpage locally.

## Project Structure

```text
Game-Deals/
│
├── index.html
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open the `index.html` file.
4. Right-click inside the file.
5. Select **Open with Live Server**.
6. The webpage will open in your default browser.

## How It Works

The game information is stored in a JavaScript array containing the game title, normal price, sale price and store.

JavaScript functions are used to:

- Check whether a game is discounted.
- Filter games that are on sale.
- Calculate the discount percentage.
- Find the cheapest game.
- Search for games using their titles.

The webpage updates automatically when the user enters a search term or changes the sale filter.

## Sample Game Information

| Game | Store | Normal Price | Sale Price |
|---|---|---:|---:|
| Hollow Knight | Steam | R14.99 | R7.49 |
| Stardew Valley | GOG | R13.99 | R13.99 |
| Celeste | Steam | R19.99 | R4.99 |
| Hades | Epic Games | R24.99 | R12.49 |
| Portal 2 | Steam | R9.99 | R0.99 |
| Terraria | GOG | R9.99 | R9.99 |
| Disco Elysium | GOG | R39.99 | R9.99 |
| Cuphead | Steam | R19.99 | R14.99 |

## Future Improvements

Some features I would like to explore in future versions include:

- Connecting to a gaming deals API to retrieve updated prices.
- Adding links to the different game stores.
- Improving the design and adding more filtering options.
- Separating HTML, CSS and JavaScript into individual files.

## Author

Developed as a personal web development project.
