# Object-Oriented Programming and HTML Tables

## Domain Modeling

1. Domain modeling is needed to fully understand the problem that is being worked on.

## HTML Table Basics

1. Tables should not be used to change a pages layout in lieu of CSS for three major reasons

    1. Acessibilty software will interpret it incorrectly.

    2. It is much harder to read and maintain the code if the tags are not clear what their function is.

    3. Tables will not automatically adjust to different screen sizes from device to device.

2. Semantic tags for tables:

    1. `table` is the outer tag, denoting the entirety of the table.

    2. `tr` denotes a table row.

    3. `td` denotes a single cell in a row.

    4. `th` denotes table headers, to be used at the beginning of a row or column.

## Introducing Constructors

1. A constructor is a type of function that builds an object to a pattern it defines; this is done by calling the function with the `new` keyword. This allows you to make a bunch of similar objects without having to repeat the same code over and over.

2. In an object literal, `this` refers to the object it is contained in. In a constructor, `this` refers to the new object that it has created.

## Object Prototypes Using A Constructor

1. One of my duties at a previous job was doing foil embossing on leather books. Other employees were able to get all the information needed (name, color, position, etc.), but would pass the actual embossing to me. This is like storing properties in a child object and then referring back to the prototype (me) to run the method, since the child object does not have the method stored.
