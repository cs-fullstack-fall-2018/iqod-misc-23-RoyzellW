# IQOD_Misc_23
Interview Question of the Day

Write a function/method to print an integer with commas as thousands separators.

### Example:
```
print(formatANumber(1000)
print(formatANumber(1010111)
print(100)
```
### Output:
```
1,000
1,010,111
100
```

function SemiColonAdder(num) {


  for (var i = 0; i < num.length; i++) {
    if (num[i] % 3 === 0) {
      num.splice(num[i], 0, ',');
    } else {
      console.log(num[i]);
    }
  }
}
