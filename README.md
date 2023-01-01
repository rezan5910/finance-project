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
after further reading on the array methods i have implemented a .reduce() method on the new array i created to return the same result.


3rd part of the assigmnets requires the calulacation of total average changes from month to month 
in order to calculate total i needed to create and empty array to store the values od the chnages by iterating through the copy of array of numbers and calutaling the differences from month to month

4th and 5th part of the assignment reqquires the calculation of greatest increase and greatest decrease in profits and print out when these occurances took place and the value of the change. 
in order ot calulate these reuqirements, i need to keep track of the changes of each pair of adjoining months stored in a sperate variable, within this new variable excute a iteration that compares the rate of change to the previous difference, if the changes positive indicating it as profit and if the chnages are negative indicating it as a loss