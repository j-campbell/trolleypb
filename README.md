# trolleypb
A simple program to kill runaway rails processes

`current status : HelloWorld` - Currently just prints `Hello, world!` #firstgem

## Todo

1. Use system calls to find runaway rails processes
2. parse output of `1` to create an array of `PID`s
3. kill `PID`s

## Proposed API

```bash
-l    : list    - don't delete
-v    : verbose - show detailed output
```

## Future Plans

* Expand to kill runaway rails processes