# Range

This is an implementation of a Range function in JavaScript.

It's not very quick, but it was fun to write.

If you are looking for something fast then just use the Lodash range function
instead.


## Usage

```javascript
range(start, end, step)
range(end) // Assumes 0
```

If you specify only one argument, the function assumes that you want to start
from 0, and the first argument is then treated as an "end" instead of a
"start".

```javascript
range(5)        // [0, 1, 2, 3, 4, 5]
range(1, 5)     // [1, 2, 3, 4, 5]
range(-2, 2)    // [-2, -1, 0, 1, 2]
range(2, -2)    // [2, 1, 0, -1, -2]
range(0, 10, 2) // [0, 2, 4, 6, 8, 10]
range(0, 10, 3) // [0, 3, 6, 9]
range(10, 10)   // [10]
```

## Who wrote it

  + [Erik Watson](mailto:erik@erikwatson.me)
