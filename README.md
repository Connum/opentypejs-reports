# [opentypejs-reports](https://github.com/Connum/opentypejs-reports)
[Opentype.js](https://github.com/opentypejs/opentype.js) test reports generated with [icu-project/text-rendering-tests](https://github.com/unicode-org/text-rendering-tests)

## Test Reports

This is the command I use to generate the reports for OpenType.js only:
```sh
python check.py --engine=OpenType.js --output=reports/{version}.html
# or
python check.py --engine=OpenType.js --output=reports/master-{commit-hash}.html
```
And for couting the passed/failed tests, run this in the Chromium dev console:
```js
`(passing: ${$$('.conformance-pass').length}, failing: ${$$('.conformance-fail').length})`
```

### Releases
* [1.3.3](https://connum.github.io/opentypejs-reports/reports/1.3.3.html) (pass: 25, fail: 720)
* [1.3.4](https://connum.github.io/opentypejs-reports/reports/1.3.4.html) (pass: 37, fail: 708)

### Master
* [f6b7548](https://connum.github.io/opentypejs-reports/reports/master-f6b7548809635ab05ac2a046579922bf3bca6a97.html) (pass: 37, fail: 708)

### Test/WIP
* [Connum/opentype.js:optimize-svg#099bc17](https://connum.github.io/opentypejs-reports/reports/test-connum_svg-optimize-099bc17ecfe9030edcd1530b2792063cb7981c56.html) (passing: 56, failing: 689)
* [Connum/opentype.js:optimize-svg#7e4de2c](https://connum.github.io/opentypejs-reports/reports/test-connum_svg-optimize-7e4de2c2ce9e822161b61349cf2a7ec55c7fd05e.html) (passing: 69, failing: 676)
