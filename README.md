# Estructuras

Repository with a set of handy (and not so much) data structures to be used with
node js.

**[CHECK OUT OUR WIKI][1]**


## Install
```bash
npm install --save estructuras
```

All data structures includes:
* add(element)
* remove(element)
* contains(element)
* find(condition)
* findOne(condition)
* isEmpty()
* forEach(callback)
* toArray
* size
Most of the structures include more methods, see documentation.

## Usage
```javascript
const List = require('estructuras').List;

let l  = new List();

l.add("hola");
l.add(2);
l.add(3);
l.add(4);

l.remove(3);

l.forEach((x)=>{
  //Do something
  console.log(x);
})
```

[1]: https://github.com/davidalencia/estructuras/wiki
