# &lt;baasic-articleeditor&gt;

> [Baasic](http://www.baasic.com) article editor Web Component, enabling users to edit the content inline and set the permissions on each section.

## Demo

[Check it live!](http://demo.baasic.com/polymer/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install baasic-articleeditor --save
```

Or download the source code and install it manually in your projects.

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/baasic-articleeditor/baasic-articleeditor.html">
    ```

3. Start using it!

    ```html
        <baasic-articleeditor
        auto=false
        application="webcomponents" 
        article="{{article}}" slug="{{slug}}"
        hideSaveButton="true" 
        on-article-save="{{reload}}></baasic-articleeditor>
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/baasic/baasic-sdk-polymer-article-editor/releases).
