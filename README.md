# generate-unique-id
a light-weight module for generating random unique id fast by removing all underlying processess
and optimize faster

## generating an id asynchronously

add a callback to automatically make it asynchronous

```javascript
const GRI = require('generate-unique-id')
let generator  = new GRI( length of id required )

generator.generate((id)=>{
   console.log(id)  // a unique id with a lenth passed on to constructor
})

```
## generating an id synchronously

add no callback and assign for a synchronous effect

```javascript
const GRI = require('generate-unique-id')
let generator  = new GRI( length of id required )

let id = generator.generate()

console.log(id)  // generated id

```
