# genoset-221
[![Build Status](https://travis-ci.org/calweb/genoset-221.png?branch=master)](https://travis-ci.org/calweb/genoset-221)

Use this module to help determine if there's an [increased risk of gluten intolerance and celiac disease](http://www.snpedia.com/index.php/Gs221) in europeans.

## Information

<table>
<tr>
<td>Package</td><td>genoset-221</td>
</tr>
<tr>
<td>Description</td>
<td>Increased risk of gluten intolerance and celiac disease in europeans</td>
</tr>
<tr>
<td>Node Version</td>
<td>~ 6.9.1</td>
</tr>
</table>

## Compatibility

This genoset is to be used with DNA-JSON. See [dna2json](https://github.com/genomejs/dna2json) for more information.

## Usage

```js
var riskGlutenIntolerant = require('genoset-221')
var dna = require('./dna.json')

console.log(riskGlutenIntolerant(dna))
// → `true` or `false`
```

## Contributions

This Project follows the StandardJS style guide.

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

To Contribute:

- Clone Repo
- `npm install`
- Write Code
- Write Test(s)
- Submit Pull Request

## License

_genoset-221 is available under the [MIT](https://mths.be/mit) license.
