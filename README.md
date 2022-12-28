# React-Bootstrap Snippets

This extension includes 712 [React-Bootstrap](https://react-bootstrap.github.io/) snippets for VS Code.

Build apps with React-Bootstrap at your fingertips.

This extension supports:

- 🙌 All `react-bootstrap` components. The complete picture.
- 📦 `import` snippets, for quick and easy importing.
- 💁‍♀️ Example snippets from the docs for convenience.
- 🧰 [Bootstrap utility CSS class](https://getbootstrap.com/docs/5.0/utilities) snippets for even more convenience!

**Just type `rb` and press <kbd>Ctrl</kbd>+<kbd>Space</kbd> for autocompletion. VS Code will autocomplete the component you need.**

![Demo](https://raw.githubusercontent.com/justinmahar/vscode-react-bootstrap-snippets/master/images/demo.gif)

Read below for more information and gif demos.

> Loving it? **[Rate it here!](https://marketplace.visualstudio.com/items?itemName=justinmahar.react-bootstrap-snippets&ssr=false#review-details)**

## 📚 Supported languages (file extensions)
- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)

## react-boostrap Support

| Extension Version | react-bootstrap Version       |
| ----------------- | ----------------------------- |
| Latest            | `v2.0.0-rc.0` (Bootstrap 5.1) |
| `1.0.9`           | `1.64` (Bootstrap 4.6)        |

> In VS Code, press Cmd+Shift+P and run *Extension: Install Specific Version of Extension...* to install a specific version.

## 📖 Snippets

**All snippets start with `rb` for React-Bootstrap.**

There are 712 snippets available for components, imports, examples, and utility CSS classes. 

Read more on each below.

### Component Snippets

All React-Bootstrap's components are supported.

For example, `rb:alert`, `rb:badge`, `rb:breadcrumb`, etc.

Where applicable, suggestions are made for which components to use inside a given component, such as `thead` and `tbody` inside a `Table`.

### Import Snippets

Component import snippets are available for all React-Bootstrap components. 

All imports begin with `rb:import` followed by the component name. For example, `rb:import:row` will import `Row`. 

Since it's such a common use case, you can also use `rb:import:grid` to import `Container`, `Row`, and `Col` all at once.

![Imports](https://raw.githubusercontent.com/justinmahar/vscode-react-bootstrap-snippets/master/images/imports.gif)

### Example Snippets

Where applicable, examples from the docs are provided as snippets. These can be very helpful as a starting point when working with more complex components, or for use as quick placeholders.

Example snippets all end with `-example`. 

For instance, `rb:alert-example` will insert an example `Alert` to build upon.

![Examples](https://raw.githubusercontent.com/justinmahar/vscode-react-bootstrap-snippets/master/images/examples.gif)

### Alert and Modal Functions

For convenience, function snippets are included for the show/hide functions needed for modals and dismissible alerts.

![Functions](https://raw.githubusercontent.com/justinmahar/vscode-react-bootstrap-snippets/master/images/functions.gif)

Use `rb:modal-functions` for the following:

```tsx
const [showModal, setShowModal] = React.useState(false);
const handleCloseModal = () => setShowModal(false);
const handleShowModal = () => setShowModal(true);
```

And `rb:alert-dismissible-functions` for the following:

```tsx
const [showAlert, setShowAlert] = React.useState(false);
const handleCloseAlert = () => setShowAlert(false);
const handleShowAlert = () => setShowAlert(true);
```

These pair nicely with the snippets for `rb:modal` and `rb:alert-dismissible`.

### Table Utilities

This extension includes utilities for tables so you can quickly build table headers and table rows.

Use `rb:table-row-X` and `rb:table-header-row-X`, where `X` is the number of columns from 2-9, to quickly build rows in your `thead` and `tbody`.

![Tables](https://raw.githubusercontent.com/justinmahar/vscode-react-bootstrap-snippets/master/images/tables.gif)

### Bootstrap Utility CSS Class Snippets

Handy snippets are included for all [Bootstrap utility CSS classes](https://getbootstrap.com/docs/5.0/utilities).

Use the `rb:utils` prefix to quickly look up and use any of Bootstrap's utility classes while building.

![Utilities](https://raw.githubusercontent.com/justinmahar/vscode-react-bootstrap-snippets/master/images/rbutils.gif)

## A Note To You, The Developer

My goal was to make this one of the best snippets extensions available to you. As such, I spent countless hours reading the docs to make this as great as I could, and I truly hope you find it useful.

That being said, if you find a bug or see a way to improve this extension, please feel free to [open an issue](https://github.com/justinmahar/vscode-react-bootstrap-snippets/issues) or submit a [pull request to the project](https://github.com/justinmahar/vscode-react-bootstrap-snippets).

If you found this extension helpful, consider **[rating it](https://marketplace.visualstudio.com/items?itemName=justinmahar.react-bootstrap-snippets&ssr=false#review-details)** and **[give it a star](https://github.com/justinmahar/vscode-react-bootstrap-snippets)** so others can find it.

Happy coding 🖖

## Donate 

I hope this project makes your life a little easier! If it does and you'd like to show your appreciation, consider supporting the project with a coffee or sponsorship. 

Your support helps keep the project going and will earn you some serious virtual high fives. Maybe even a virtual fist bump if you're feeling extra cool.

<a href="https://github.com/sponsors/justinmahar">
  <img src="https://justinmahar.github.io/react-kindling/support/sponsor.png" alt="Sponsor via GitHub" height="35" />
</a> <a href="https://paypal.me/thejustinmahar/5">
  <img src="https://justinmahar.github.io/react-kindling/support/coffee-1.png" alt="Buy me a coffee" height="35" />
</a> <a href="https://paypal.me/thejustinmahar/15">
  <img src="https://justinmahar.github.io/react-kindling/support/coffee-3.png" alt="Buy me 3 coffees" height="35" />
</a> <a href="https://paypal.me/thejustinmahar/25">
  <img src="https://justinmahar.github.io/react-kindling/support/coffee-5.png" alt="Buy me 5 coffees" height="35" />
</a>

## Release Notes

See the [CHANGELOG](https://marketplace.visualstudio.com/items/justinmahar.react-bootstrap-snippets/changelog) for release notes.