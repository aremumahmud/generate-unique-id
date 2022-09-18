# generate-unique-id
a module for generating randowm unique id

## generating an id

```
const GRI = require('generate-unique-id')
let generator  = new GRI( length of id required )

generator.generate((id)=>{
   console.log(id)  // a unique id with a lenth passed on to constructor
})

```
