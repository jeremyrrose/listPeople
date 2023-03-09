# Challenge: Directory listing

## Objective

Your engineering team did a great job formatting "directory listings" for our list of people!

Unfortunately, we received incorrect instructions from the customer -- it turns out that a "person" with the `private` key set to `true` shouldn't be displayed _at all_.

Use `.filter()` to modify the function in `index.js` so that _only_ users without `private: true` are shown.

## Background info

A typical "person" object follows this schema:

```js
    {
        name: "Charles",
        location: "Washington Heights",
        phone: "555-999-4567"
    }
```

The directory listing for this object is the following string:

```js
"Charles, Washington Heights (555-999-4567)"
```

Some "person" objects have an additional key, `private`, with a Boolean value.

## Instructions

Modify the code inside the `listPeople` function in `index.js`.

The test case is stored in `people.js` and imported into `index.js`. The `expectedResult` is defined in `index.js`. Feel free to peek at both!

Run `node index.js` in this directory to test your function and get feedback!

## BONUS

Sort the listings in alphabetical order by name. Run `node index.js bonus` to test.

## Resources

- [MDN: `.filter()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [MDN: Template literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
- [MDN: Ternary operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)
- **BONUS** [MDN: Array.prototype.sort()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) (also... just Google this tbh. Javascript is weird!)

