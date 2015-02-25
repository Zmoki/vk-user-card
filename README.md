# &lt;vk-user-card&gt;

> A web component to show a profile-card for your VK account.

## Demo

[Check it live!](http://zmoki.github.io/vk-user-card)

## Install

[download as ZIP](https://github.com/zmoki/vk-user-card/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="/src/vk-user-card.html">
    ```

3. Start using it!

    ```html
    <vk-user-card user="1"></vk-user-card>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`user`         | *int*    | `1`        | ID of user

## License

[MIT License](http://opensource.org/licenses/MIT)
