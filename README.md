To run from command line:

```
compute threshold limit
```

Example:
```
./compute 5 100
```
Assumptions:

- Compile is in `Unix(LF)` format. Encoding: `UTF-8`

- One number per line

- `Enter` is pressed after each number

Processing is triggered by one of the following:

- `EOF` keystroke (`Ctrl+D` in Unix, `Ctrl+Z` in Windows)
  
  Note: you still need to press `Enter` after last number

- 100 numbers were entered
