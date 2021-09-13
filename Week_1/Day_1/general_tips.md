### Using arguments to run a process

To run a `.js` file, from the terminal, it is possible to pass arguments, too.

For example:

```bash 
node myFile.js arg1 arg2 arg3
```

The following script, prints the list of such arguments:

```javascript
'use strict';

for (let j = 0; j < process.argv.length; j++) {
    console.log(j + ' -> ' + (process.argv[j]));
}
```

Source: [Command line arguments in Node.js](https://stackabuse.com/command-line-arguments-in-node-js/)