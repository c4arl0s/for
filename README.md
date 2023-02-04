# for

# 1. [Using For Loop to List Iterate Over Numbers]()

```bash
for i in {1..10}; do echo $i; done
```

```console
1
2
3
4
5
6
7
8
9
10
```

# 2. [Array Iteration]()

```bash
a=(1 2 3 4)
```

```bash
for y in "${a[@]}"; do echo "$y"; done
```

```console
1
2
3
4
```

# 3. [For Loop with C-style syntax]()

```bash
for (( i = 0; i < 10; i++ )); do echo "The iteration number is $i"; done
```

```console
The iteration number is 0
The iteration number is 1
The iteration number is 2
The iteration number is 3
The iteration number is 4
The iteration number is 5
The iteration number is 6
The iteration number is 7
The iteration number is 8
The iteration number is 9
```
