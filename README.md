# refer
JavaScript library for refer.is
# main
```js
async function main(){
    const {refer} = require('./refer');
    const ref= new refer();
    let req=await ref.short_url("url")
    console.log(req)
}
main()
```
