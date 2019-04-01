

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
