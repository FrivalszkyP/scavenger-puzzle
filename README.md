# Scavenger Escape Room Puzzle

## Configuration

The JS code is not in a separate file but at the bottom of the HTML code.

To change the order of the correct solution, look for this line:

```js
        /**
         * Order of the correct solution
         * TODO: CHANGE THIS TO THE CORRECT SOLUTION
         * @var {array}
         */
        const solution = [1, 2, 3, 4, 5, 6];
```

Change the value of the solution array. You can set up a different solution like this:

```js
        const solution = [3, 4, 2, 5, 1, 6];
```



## Used technology

- VueJS is the JS framework.
- Bootstrap CSS grid and utility classes are used for the layout.
- All of these are already used on scavengerescape.com. No additional dependencies are loaded.
- Fonts: Poppins (webfont) and system default Monospace font (Windows: Courier New).
- The puzzle pieces are controlled by checkbox inputs + labels. No JS is involved in displaying the on/off state of the buttons.
- A small VueJS logic handles the logic for the correct solution and counting the clicked puzzle pieces.
- There's a small fade-in effect when the solution appears. This is also controlled by VueJS + some CSS.