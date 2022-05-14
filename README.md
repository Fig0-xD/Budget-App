# Markdown Blog App

## Description

A budget creating application made using ReactJS

## Installation

1. Clone the Repository
2. Run `npm start`
3. Open [http://localhost:3000](http://localhost:3000) on your browser

## Libraries used

-   React-Bootstrap - Used to style the components
-   Uuid - Used to provide unique ids

## Features

-   Uses local-storage of browser to store the budgets and expenses managed by the custom hook **useLocalStorage**.
-   Budget context provides the expenses and budgets alongwith their methods to all the components.
-   Also deleting a budget that contains existing expenses in it makes them move to the **Uncategorized** budget instead of deleting the respective expenses.
