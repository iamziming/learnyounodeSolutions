# My solutions to learnyounode.

#####1. HELLO WORLD
```JavaScript
console.log('HELLO WORLD');
```

#####2. BABY STEPS
```JavaScript
var result = 0;
for (i = 2; i < process.argv.length; i++) {
  result += Number(process.argv[i]);
}

console.log(result);
```

#####3. MY FIRST I/O!
```JavaScript
var fs = require("fs");
var contents = fs.readFileSync(process.argv[2]);
var result = contents.toString().split("\n").length - 1;

console.log(result);
```

#####4. MY FIRST ASYNC I/O!
#####5. FILTERED LS
#####6. MAKE IT MODULAR
#####7. HTTP CLIENT
#####8. HTTP COLLECT
#####9. JUGGLING ASYNC
#####10. TIME SERVER
#####11. HTTP FILE SERVER
#####12. HTTP UPPERCASERER
#####13. HTTP JSON API SERVER
