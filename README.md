## PascalCase
```js
// import module
import PascalCase from 'updev/PascalCase';

// example string
let str = "abcd efgh";

// printing str in PascalCase
console.log(pascal(str));

// Output -> AbcdEfgh
```

## camelCase
```js
// import module
import camelCase from 'updev/camelCase';

// example string
let str = "abcd efgh";

// printing str in camelCase
console.log(camel(str));

// Output -> abcdEfgh
```

## snake_case
```js
// import module
import snake from 'updev/snake_case';

// example string
let str = "aecd efgh";

// printing str in snake_case
console.log(snake(str));

// Output -> aecd_efgh
```

## firstCap
```js
// import module
import firstCap from 'updev/firstCap'

// example string
let str = "aeGd efgh ijkL";

// printing str
console.log(firstCap(str));

// Output -> Aegd Efgh Ijkl
```

## onlyFirstCap
```js
// import module
import onlyFirstCap from 'updev/onlyFirstCap'

// example string
let str = "aeGd efgh ijkL";

// printing str
console.log(onlyFirstCap(str));

// Output -> Aegd efgh ijkl
```

## removeHTMLTags
```js
// import module
import removeHTMLTags from 'updev/removeHTMLTags'

// example tag
let tags = "<h1> Hello World! </h1>";

// printing tags
console.log(removeHTMLTags(tags));

// Output -> Hello World! 
```


## debounce
```js
// import module
import debounce from 'updev/debounce';

// debounce function
debounce(()=>{
  // callback
},time);

Ex - 
debounce(()=>{
  // callback
},1000);
```

## throttle
```js
// import module
import throttle from 'updev/throttle';

// throttle function
throttle(()=>{
  // callback
},1000);

Ex -
throttle(()=>{
 // callback
},1000);
```

## delay
```js
// import module
import delay from 'updev/delay'

delay(()=>{
  // callback
},time);

Ex -
delay(()=>{
console.log("Hello")
},1500);
```
