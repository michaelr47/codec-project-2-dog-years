# codec-project-3-dog-years
//convert age from “human years” to “dog years", second proj i did in intro course js.

// My age as a variable.
const myAge = 21;
// earlyYears is valued as 2 and will change.
let earlyYears = 2;
earlyYears = earlyYears * 10.5; 
// Converting earlyYears to laterYears with algo. 
let laterYears = myAge - 2;
// Multiplying laterYears by 4 to get # in dogs years.
laterYears = laterYears * 4;
console.log(earlyYears);
console.log(laterYears);
// merging both early and later years 
let myAgeInDogYears = earlyYears + laterYears;
// Naming 'michael' lowercased
let myName= 'Michael' .toLowerCase(); 
// finally logging all variables to see if match or not.
console.log(`My name is ${myName}. I am ${myAge} years old in human years which is ${myAgeInDogYears} years old in dogs years.`);

