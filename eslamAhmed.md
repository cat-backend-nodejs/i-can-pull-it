let n=prompt("enter the number:" );
n=parseInt(n);
let arr=[0];
for(i=1 ;i<=n;i++)
arr.push(i);
let sum=arr.reduce((sum,current)=>sum+current,0)
 

