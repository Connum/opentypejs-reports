# opentypejs-reports
[Opentype.js](https://github.com/opentypejs/opentype.js) test reports generated with [icu-project/text-rendering-tests](https://github.com/unicode-org/text-rendering-tests)

## Test Reports

This is the command I use to generate the reports for OpenType.js only:
```sh
python check.py --engine=OpenType.js --output=reports/{version}.html
# or
python check.py --engine=OpenType.js --output=reports/master-{commit-hash}.html
```

### Releases
* [1.3.3](https://connum.github.io/opentypejs-reports/reports/1.3.3.html)
* [1.3.4](https://connum.github.io/opentypejs-reports/reports/1.3.4.html)

### Master
