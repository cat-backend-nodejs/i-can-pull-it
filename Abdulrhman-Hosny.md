```
function sumOfIntegersUpTo(n) {
    let sum = 0;
    for (let i = 1; i <= n; i++) {
        sum += i;
    }
    return sum;
}

// Example usage:
const n = 5;
const sum = sumOfIntegersUpTo(n);
console.log(`Sum of integers up to ${n} is: ${sum}`);
```
