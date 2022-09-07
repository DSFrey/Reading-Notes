# HTML Lists, CSS Boxes, JS Control Flow

## HTML: Ordered and Unordered Lists

1. Unordered lists should be used to group a collection of items for which order does not matter.

2. The bullet style can be changed using the css property `list-style`.

3. Ordered lists should be used to group a collection of items for which order does matter, e.g. rankings or directions.

4. The `type` attribute can change the numbering from numerals to letters or Roman numerals. The `reversed` attribute can make the numbers count down instead of up.

## CSS: The Box Model

1. The margin is the military man, keeping other nations away. The padding is the police man, keeping his nation contained.

2. The parts of the css box model are

    1. **Content Box:** The area where the content is displayed.

    2. **Padding Box:** The space between the content and the border.

    3. **Border Box:** Marks the outside of the box.

    4. **Margin Box:** The space between the border and any other elements.

## JS: Arrays, Operators, Expressions, Conditionals, Loops

1. You can store any type of data in an array, including numbers, strings, objects, or [arrays.](https://i.kym-cdn.com/photos/images/newsfeed/000/000/177/800px-Sup_dawg.jpg)

2. It is valid, and values are accessed by chaining indexes; for example the value `'accountant'` is accessed by `people[2][3]`.

3. In the last, note that it does not assign if x is not truthy, short-circuiting the evaluation.

    |Name|Shorthand Operator|Description|
    |---|---|---|
    |Addition assignment|`x += y`|`x = x + y`|
    |Division assignment|`x /= y`|`x = x / y`|
    |Remainder (modulus) assignment|`x %= y`|`x = x % y`|
    |Exponentiation assignment|`x **= y`|`x = x ** y`|
    |AND assignment|`x &&= y`|`x && (x = y)`|

4. Adding a false boolean to a number is just adding 0, so `10 + false` is `10`. Adding anything to a string concatenates it to the string, so the whole expression `(10 + false) + 'dog'` evaluates to `'10dog'`.

5. When the browser loads a page, could check whether the user has dark mode turned on. If they do, then the page would load a dark color scheme; otherwise, it would load a light color scheme.

6. A loop would be needed if you want to use a function to process each item in an array.

## Things I want to know more about

I am a bit confused by objects right now, but seeing as we've not really done anything with them yet and I've only seen reference to them in passing, I am just going to have patience for the time being.
