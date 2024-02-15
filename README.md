# DGL 113 2024WI Assignment #5

Preview the docs/index.html file with a web browser to get a
general idea about the webpage layout and its functionality,
then complete the following tasks.

Create a new file in the `docs` folder called `app.js`.

At the top of the `docs/app.js` file, add the `use strict` directive:

```javascript
'use strict';
```

Add a `<script>` element to the `index.html` file to include the `app.js` script.
Place the `<script>` element just before the closing `</body>` tag just like
the script element that is used to include the `main.js` script.

Create a JavaScript class `OrderItem` as follows:

The class should have a constructor method `constructor(quantity,size,description)`
where `quantity` is a number and `size` and `description` are strings describing
the size and which drink is being ordered.

Add getters to the class for the `quantity`, `size`, and `description`
properties.

Add setters to the class for the `quantity`, `size`, and `description`
properties.

Add a `cost()` method to the class which returns the cost of the
item based on its `quantity`, `size`, and `description` properties.

Remember that:

- Short, Tall, Grande, and Venti coffees cost 2.99, 3.19, 3.49 and 3.99 respectively, and
- Short, Tall, Grande, and Venti teas cost 2.85, 3.05, 3.25, and 3.50 respectively.

NOTE: Only modify the `docs/app.js` and `docs/index.html` files.
Do not make changes to any other files.
