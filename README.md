## math-scripts
command line python scripts for doing mathy stuff

### clists (compare lists)
**insersection**, **difference** and **symmetric difference** of n lists
```sh
clists '234,23  , 12, 45  , 61' '234, 23,12, 45, 83'
clists -s '|' '234|23  | 12| 45  | 61' '234| 23|12| 45| 83'
clists '1,2,3' '1,3,4' '3,4,5'
```

### comper (combinations and permutations)
**combinations** and **permutations** of lists or sets
```sh
comper 'd,o,g,c,a,t' -n 3 -s , -o ,
```

### xor
xor (optionally binary) strings of different lengths
```sh
xor 6161 20 202020 -p
xor aa ' ' '  b' -b -p
```

## license
This code is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
