# React Greengrocers

You're going to recreate the [javascript greengrocers exercise](./images/greengrocer-exercise.gif) but this time, using React!

![](images/greengrocer-exercise.gif)

> Reusing an exercise that you already know will help you deepen your understanding of the fundamentals of React by removing the requirement to get familiar with a new domain and context.

## Setup

1. Fork this repository
2. Clone the forked repository onto your local machines
3. In the root directory, type `npm ci`, which installs dependencies for the project
4. Finally, type `npm run dev`, which starts a development server that runs your website in the browser. That server 
   will reload your website whenever you make any changes to source files

## User Stories

- A user can view a selection of items in the store
- From the store, a user can add an item to their cart
- From the cart, a user can view and adjust the number of items in their cart
    - If an item's quantity equals zero it is removed from the cart
- A user can view the current total in their cart

## Core Requirements

- Create a diagram of your component hierarchy before starting to code. Add this diagram to the root directory
- Annotate your diagram by adding what state each component needs to manage - React State or React Props
- Create all the components you need, using the HTML templates as a reference
- Create all the pieces of the state you need
- Add all the event listeners you need to make the page reactive

## Extension 1

- Add filters to the store i.e. filter by item type; when a user clicks a filter they will only see items of that type
- Add sorting to the store i.e. sort by price or sort alphabetically; when a user clicks sort they will see a sorted 
  list of items

## Extension 2

- Add a new detail component for each of the items, and render it conditionally after clicking on an item. Only one detail component should be rendered at a time; clicking a second item should remove the previous item's details.
