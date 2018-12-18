# Responsive Navigation Bar Exercise

## Objective

This is an exercise for beginners learning how to use CSS flexbox and media queries.

## Pre-Requisites

Basic understanding of HTML and CSS.

### Instructions

You will be writing all of your code in `styles.css`. Don't forget to link your stylesheet to your html file!

1. Select the `container` element and add the `display` property and set it's value to `flex`.

   - This activates flexbox!

2. Select the `search` element and give the item a `flex` value of `1`.

   - This will make the search input shrink and expand, making it responsive.

3. Select the `li` elements in `container` and give the items a `flex` value of `1`.

   - This will make the rest of the elements in your nav to grow with the width of the container. _Hint: You can target the `li` elements using:_ `.container > li {...}`

4. Add a `max-width` media query that will kick in at `600px`.

   1. Inside of your media query, select the `container` element and give it a `flex-wrap` property and set its value to `wrap`.
      - By default this is set to `nowrap`, so we'll change it to `wrap` instead.
   2. Still inside of your media query, select the `li` elements in `container` and give it a `flex-basis` property and set its value to `50%`.
      - This tells flexbox to make each item take up 50% of the available width which results in two items per rows when the screen is at 600px.

5. Add another `max-width` media query that will kick in at `400px`.
   1. Inside of your media query, select the `li` elements in `container` and give it a `flex-basis` property and set its value to `100%`.
      - This changes the 50% width to 100% so that each row only fits a single item
   2. Inside of your media query, select the `search` element and give it an `order` property and set its value to `1`.
      - This places the search bar at the bottom of your navigation.

#### You're done! You should now have a responsive navigation bar.
