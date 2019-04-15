

### keys.each - each_key

```
$ be benchmark-driver keys_each-each_keys.yml --rbenv '2.6.2'
Warming up --------------------------------------
           keys_each     2.251M i/s -      2.331M times in 1.035687s (444.24ns/i)
            each_key     2.510M i/s -      2.592M times in 1.032618s (398.38ns/i)
Calculating -------------------------------------
           keys_each     2.410M i/s -      6.753M times in 2.802186s (414.95ns/i)
            each_key     1.820M i/s -      7.530M times in 4.137156s (549.39ns/i)

Comparison:
           keys_each:   2409954.2 i/s
            each_key:   1820198.7 i/s - 1.32x  slower
```

### String#split(string or regexp)

```
$ be benchmark-driver string_split_string-regexp.yml --rbenv '2.6.2'
Warming up --------------------------------------
              string     3.019M i/s -      3.046M times in 1.008679s (331.20ns/i)
              regexp   334.496k i/s -    353.724k times in 1.057482s (2.99μs/i)
Calculating -------------------------------------
              string     3.161M i/s -      9.058M times in 2.865472s (316.34ns/i)
              regexp   344.448k i/s -      1.003M times in 2.913325s (2.90μs/i)

Comparison:
              string:   3161117.6 i/s
              regexp:    344448.0 i/s - 9.18x  slower
```
