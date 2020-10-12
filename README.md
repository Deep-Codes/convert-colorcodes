## Color Code Conversions

npm install
```bash
npm i convert-colorcodes
```

```javascript
const {hexToHSL , hexToRGB, hexToCMYK} = require('convert-colorcodes')

console.log(hexToRGB('#1e1e1e'))
console.log(hexToHSL('#1e1e1e'))
console.log(hexToCMYK('#1e1e1e'))

// rgb(30,30,30)
// hsl(0,0%,12%)
// cmyk(0,0,0,0.88)

```
