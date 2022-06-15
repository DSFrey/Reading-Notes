# CSS

CSS is the language used for styling the structure that html provides.

## Syntax

Each rule follows the basic form:

    selector {property: value}

- The selector identifies which html element is being modified.
- The property identifies what type of modification is being made.
- The value gives the specific outcome of the property. When the value has a unit assigned, there should be no space between the number and the unit, e.g. `20px`.

## Adding CSS

CSS can be added in three different ways.

- **External:** A separate stylesheet that can affect the whole site.
- **Internal:** Included in the html and affects only that page.
- **Inline:** Included in and affecting only a single element.

The latter two options should be used sparingly, as the first is optimal for consistency and readability. If a property has been defined multiple times, the value from the most recently read stylesheet will be used.
