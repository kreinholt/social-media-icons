# &lt;social-media&gt;

> A Polymer element with a set of scalable social media icons

![alt tag](http://www.hejty.com/github/social-media-320.png)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install social-media --save
```

Or [download as ZIP](https://github.com/hejty/social-media/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/social-media.html">
    ```

3. Start using it!

    ```html
    <social-media></social-media>
    ```

## Options

Attribute       | Options                                                   | Default                       | Description
---             | ---                                                       | ---                           | ---
`icon`         	| `dribbble`, `facebook`, `github`, `googleplus`, `lastfm`, `reddit`, `soundcloud`, `tumblr`, `twitter`    | `github`                      | Logo
`size`          | *int*                                                     | `32`                         	| The size of icon
`color`         | *hex*                                                  	| -     						| The fill color
`href`          | *string*                                                  | -                           | The target URL

## Examples:

```html
<social-media icon="github" color="#bada55" size="320" href="https://github.com/hejty"></social-media>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/hejty/social-media/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
