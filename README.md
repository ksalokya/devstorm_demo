## PascalCase
```js
// import module
import PascalCase from 'devstorm/PascalCase';

// example string
let str = "abcd efgh";

// printing str in PascalCase
console.log(PascalCase(str));

// Output -> AbcdEfgh
```

## camelCase
```js
// import module
import camelCase from 'devstorm/camelCase';

// example string
let str = "abcd efgh";

// printing str in camelCase
console.log(camelCase(str));

// Output -> abcdEfgh
```

## snake_case
```js
// import module
import snake_case from 'devstorm/snake_case';

// example string
let str = "aecd efgh";

// printing str in snake_case
console.log(snake_case(str));

// Output -> aecd_efgh
```

## firstCap
```js
// import module
import firstCap from 'devstorm/firstCap'

// example string
let str = "aeGd efgh ijkL";

// printing str
console.log(firstCap(str));

// Output -> Aegd Efgh Ijkl
```

## onlyFirstCap
```js
// import module
import onlyFirstCap from 'devstorm/onlyFirstCap'

// example string
let str = "aeGd efgh ijkL";

// printing str
console.log(onlyFirstCap(str));

// Output -> Aegd efgh ijkl
```

## removeHTMLTags
```js
// import module
import removeHTMLTags from 'devstorm/removeHTMLTags'

// example tag
let tags = "<h1> Hello World! </h1>";

// printing tags
console.log(removeHTMLTags(tags));

// Output -> Hello World! 
```

## debounce - works on DOM.
```js
// import module
import debounce from 'devstorm/debounce';

// debounce function
debounce(()=>{
  // callback
},time);

Ex - 
debounce(()=>{
  // callback
},1000);
```

## throttle - works on DOM.
```js
// import module
import throttle from 'devstorm/throttle';

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
import delay from 'devstorm/delay';

// example function
function example() {
    console.log("hello world!");
}

// call delay function
delay(example, 1000)

// Output -> hello world! (will be printed after 1 sec)
```

## date_dmy
```js
// import module
import dmy from 'devstorm/date_dmy';

// convert today's date to dd-mm-yyyy format
console.log(dmy())

// Documented on - 7th May, 2022
// Output -> 07-05-2022
```

## date_mdy
```js
// import module
import mdy from 'devstorm/date_mdy';

// convert today's date to dd-mm-yyyy format
console.log(mdy())

// Documented on - 7th May, 2022
// Output -> 05-07-2022
```

## date_ymd
```js
// import module
import ymd from 'devstorm/date_ymd';

// convert today's date to dd-mm-yyyy format
console.log(ymd())

// Documented on - 7th May, 2022
// Output -> 2022-05-07
```

## isLeap
```js
// import module
import isLeap from 'devstorm/isLeap';

// calling isLeap Fn
console.log(isLeap(2020));

// Output -> true
```

## formate_date_util
```js
// import module
import util from 'devstorm/format_date_util';

// return day, date and year
console.log(util(new Date()))

// Documented on - 7th May, 2022
// Output -> { day: '07', month: '05', year: 2022 }
```

## randomNumberInRange
```js
// import module
import random from 'devstorm/randomNumberInRange';

// generate random number in range 1 - 100
console.log(random(1,100));

// Output -> 28 (may vary)
```

## triggerFnPerSec
```js
// import module
import triggerFnPerSec from 'devstorm/triggerFnPerSecond';

// example function
function example() {
    console.log("hello world!");
}

// call trigger function
triggerFnPerSec(example)

// Output -> hello world
// will be keep printed after 1 sec
```

## triggerFnPerInterval
```js
// import module
import triggerFnPerInterval from 'devstorm/triggerFnPerInterval';

// example function
function example() {
    console.log("hello world!");
}

// call trigger function
triggerFnPerInterval(example, 1500)

// Output -> hello world
// will be keep printed after 1.5 sec
```
