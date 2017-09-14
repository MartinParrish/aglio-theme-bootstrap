# Algio Theme for Bootstrap

Theme for [Aglio](https://github.com/danielgtaylor/aglio)

NPM package [here](https://www.npmjs.com/package/aglio-theme-bootstrap).

## Usage

First install the npm package globally:
```
npm install -g aglio-theme-bootstrap
```

Then generate your API documentation using your API blueprint.
```
aglio -i your/api/blueprint.apib -t bootstrap --theme-template triple -o your/api/documentation.html
```

## Differences from Olio

The main core of this theme is from the [Olio theme](https://github.com/danielgtaylor/aglio/tree/olio-theme).

Here are the differences:

#### Markdown-it table

Martdown-it outputs the open table tag with `class="table"`.
