# Related Work

This lists other alternatives.


## [md-to-json](https://www.npmjs.com/package/md-2-json)

> https://github.com/ajithr/md-2-json

### Example

#### Simple content

```js

var md2json = require('md-2-json');

md2json.parse('This is a markdown content');

/* output
{
    raw: "This is a markdown content\n"
}
*/

```

#### Multiline Content

```js

var md2json = require('md-2-json');
var mdContent = `
# Heading 1

This is a para

- This is a list

## Heading 2

This is a para
`

md2json.parse(mdContent);

/* output
{
    "Heading 1": {
        raw: "This is a para\n - This is a list\n",
        "Heading 2": {
            raw: "This is a para\n"
        }
    }
}
*/

```

## [md2json](https://www.npmjs.com/package/@jackens/md2json)

Code repository is 404
