## Overview

This web-component introduces a custom element `dsheiko-xreference` that retrieves and displays a fragment of
a specified external resource matching given grep condition or selector

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install dsheiko-xreference --save
```

Or [download as ZIP](https://github.com/dsheiko/x-reference-xtag).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="../src/dsheiko-xreference.html">
    ```

3. Start using it!

    You can extract a fragment by CSS selector:
    ```html
    <dsheiko-xreference href="url-address" locator="a-CSS-selector">
        Text content
    </dsheiko-xreference>
    ```
    or you can use a regexp condition:
    ```html
    <dsheiko-xreference href="url-address" grep="reg-exp">
        Text content
    </dsheiko-xreference>
    ```


## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`openModal`   | None         | void        | Implicit request for showing the fragment.

## Events

Event         | Description
---           | ---
`click`       | Retrieve and show a modal with fragment


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## License

[MIT License](http://opensource.org/licenses/MIT)


# Create X-Tag Components

[Guide for creating X-Tag Components](https://github.com/x-tag/core/wiki/Creating-X-Tag-Components)

# Use X-Tag Components

[Using X-Tag components in your applications](https://github.com/x-tag/core/wiki/Using-X-Tag-Components-in-your-application)

