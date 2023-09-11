# Pizza Menu App

This is a simple React-based web application for a fictional pizza restaurant, "Fast React Pizza Co." It demonstrates the use of React props, JSX rendering, lists, destructuring, and fragments.

## Overview
Fast React Pizza Co. displays a pizza menu, allowing users to view pizza options, check their availability, and learn about the restaurant's opening hours.

## Key Concepts
- **Props**: The `Pizza` component uses props to display pizza details such as name, ingredients, price, and availability.

- **JSX Rendering**: JSX is used to create dynamic UI elements, rendering pizza items and restaurant information.

- **Lists**: The menu dynamically renders a list of pizzas using `map` to iterate over the `pizzaData` array.

- **Destructuring**: Object destructuring is used to extract pizza properties for rendering in the `Pizza` component.

- **Fragments**: Fragments (`<>...</>`) are used to group multiple JSX elements without introducing extra nodes in the DOM.

## Components
- **App**: The main component rendering the header, menu, and footer.

- **Header**: Displays the restaurant's name.

- **Menu**: Renders the pizza menu items.

- **Pizza**: Represents an individual pizza item, accepting pizza details as props.

- **Footer**: Displays the restaurant's opening hours.

## Deployment
The application is deployed on Netlify and can be accessed [here](https://pizza-menu-by-troy.netlify.app/).

Feel free to explore the code and understand how props, rendering, lists, destructuring, and fragments are used in this simple React application.

