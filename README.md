# time-remaining

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install time-remaining --save
```

Or [download as ZIP](https://github.com/mhozza/time-remaining/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/time-remaining/dist/time-remaining.html">
    ```

3. Start using it!

    ```html
    <time-remaining target="10/20/2030 18:47:42"></time-remaining>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`target`      | *DateTime*  | ---          | Target DateTime


## License

[MIT License](http://opensource.org/licenses/MIT)
