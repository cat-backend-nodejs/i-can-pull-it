# problem solution

**Problem:** Find the sum of all positive integers less than or equal to $n$.

**Code (JavaScript):**

function getSum(n){
    return (n * (n + 1)) / 2;
}

console.log(getSum(5));  
console.log(getSum(10)); 
