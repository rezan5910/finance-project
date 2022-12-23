in order to creat a net total all the number in the array of arrays i am extracting the mnumbers into an new array
for this i initially i run a for loop 
```
const finVal =[];
for (let i=0 ; i<finances.length ; i++){
  finVal.push(finances[i][1])
}
console.log(finVal);

```
however after further learning array methods i have modified and updated this a map method which is more readable.

i will be using the extracted array to run all the remaining calculations


net total calulation 
i will need to add all the numbers in the array and store them in to a new variable and call it 
my inital approach was a simple for loop on the new array
```
// let netTotal= 0;
// for (let i=0; i<finVal.length; i++){
//   netTotal += finVal[i];
// }

```
after further reading on the array methods i have implemented a .reduce method on the new array i created to return the same result.
