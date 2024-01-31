# Pokédex Web App
This is a Pokédex web application built using ReactJS, Redux Toolkit and Axios. It allows users to search and browse Pokémon data retrieved from [PokeAPI](https://pokeapi.co/). The app includes a search page, a list page with infinite scrolling, a details page for each Pokémon, and a favorites screen.

## Live Link

[https://pokedexreactjsfr.netlify.app)

## - **Search Page:** Users can search for Pokémon by name. The app makes an API call to retrieve Pokémon data and displays loading indicators and error messages if necessary.

- **List page:** Displays a list of Pokémon retrieved from the API. The page supports infinite scrolling, loading more Pokémon as the user scrolls.

- **Details Page:** Shows detailed information about a selected Pokémon, including its abilities, types, stats, and more. Users can favorite a Pokémon and save it as a favorite on their device. Favorited Pokémon can be easily identified and removed from favorites.

- **Favorites Screen:** Allows users to see all their favorite Pokémon. The data is stored locally on the user's device and users can remove Pokémon from their favorites.

## Technologies Used

- ReactJS
- Redux Toolkit (for state management)
- Axios (for API calls)
- React Infinite Scroll component (for infinite scroll functionality)
- React Redux (to integrate Redux with React)
- React Router DOM (for routing within the application)
- React Tabs (for tabbed navigation)


## Getting Started

- Clone the repository to your local machine:
```bash
git clone https://github.com/Fahd-code/Pokedex-React-JS-Eng.git
- Go to the project directory:
```bash
cd Pokedex-en-ReactJS
- Install dependencies:
```bash
npm install
- Start the development server:
```bash
npm run development
- Open the application in your browser: http://localhost:5173/


## API Integration

This app integrates with [PokeAPI](https://pokeapi.co/) to retrieve Pokémon data. The API base URL is https://pokeapi.co/api/v2. The following endpoints are used:
- **/pokemon:** Retrieves a list of all Pokémon. (default, limit of 20)
- **/pokemon/{name}:** Retrieves detailed information about a specific Pokémon.

## Authors

- [@FahdBahjaji://github.com/Fahd-code) (Fahd Bahjaji)
