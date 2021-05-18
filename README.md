# React-Bootstrap Snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/justinmahar.react-bootstrap-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=justinmahar.react-bootstrap-snippets)

It's finally here! 350+ [React-Bootstrap](https://react-bootstrap.github.io/) snippets for VS Code.

These snippets make building apps with React-Bootstrap an absolute pleasure.

This extension supports:

- 🙌 All `react-bootstrap` components. The complete package.
- 💁‍♀️ `import` snippets, for quick and easy importing.
- 🙋‍♂️ Example snippets from the docs for convenience.

**Just type `rb` and press <kbd>Ctrl</kbd>+<kbd>Space</kbd> for autocompletion. VS Code will autocomplete the component you need.**

![Demo](./images/demo.gif)

Want to see what's included and more demo gifs? Scroll on!

## 📚 Supported languages (file extensions)
- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)

## 📖 Snippets

**All snippets start with `rb` for React-Bootstrap.**

There are over 350 snippets available for components, imports, and examples. Read more on each below.

### Component Snippets

All of React-Bootstrap's components are supported.

For example, `rb:alert`, `rb:badge`, `rb:breadcrumb`, etc.

Where applicable, suggestions are made for which components to use inside a given component, such as `thead` and `tbody` inside a `Table`.

### Import Snippets

Component import snippets are available for all React-Bootstrap components. 

All imports begin with `rb:import` followed by the component name. For example, `rb:import:row` will import `Row`. 

Since it's such a common use case, you can also use `rb:import:grid` to import `Container`, `Row`, and `Col` all at once.

![Imports](./images/imports.gif)

### Example Snippets

Where applicable, examples from the docs are provided as snippets. These can be very helpful as a starting point when working with more complex components, or for use as quick placeholders.

Example snippets all end with `-example`. 

For instance, `rb:alert-example` will insert an example `Alert` to build upon.

![Examples](./images/examples.gif)

### Alert and Modal Functions

For convenience, function snippets are included for the show/hide functions needed for modals and dismissible alerts.

![Functions](./images/functions.gif)

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

These pair nicely with the snippets for `rb:alert-dismissible` and `rb:modal`.


### Table Utilities

This extension includes utilities for tables so you can quickly build table headers and table rows.

Use `rb:table-row-X` and `rb:table-header-row-X`, where `X` is the number of columns from 2-9, to quickly build rows in your `thead` and `tbody`.

![Tables](./images/tables.gif)

## Note To You, The Developer

My goal was to make this one of the best snippets extensions available to you. As such, I spent countless hours reading the docs to make this as great as I could, and I truly hope you find it useful.

That being said, if you find a bug or see a way to improve this extension, please feel free to [open an issue](https://github.com/justinmahar/vscode-react-bootstrap-snippets/issues) or submit a [pull request to the project](https://github.com/justinmahar/vscode-react-bootstrap-snippets).

This is a brand new extension, so...

## 🌟 If you found this extension helpful, please **[rate it](https://marketplace.visualstudio.com/items?itemName=justinmahar.react-bootstrap-snippets&ssr=false#review-details)** and **[star it](https://github.com/justinmahar/vscode-react-bootstrap-snippets)** so others can find it. :)

And as always, happy coding!

-Justin

## Release Notes

### [1.0.0] - 2021-05-17

- Initial release of React-Bootstrap snippets.

### [1.0.1]-[1.0.4] - 2021-05-18

- Update documentation. 
- Add demo gif.