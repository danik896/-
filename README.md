# -function capitalizeFirstLetter(str) {
     if (!str) return str;
return str.charAt(0). toUpperCase() + str.slice(1);
}
function reverseString(str) {
    return str.split('').reverse().join('');
}
function countVowels(str) {
    const vowels = 'aeiou';
    let count = 0;
    for (let char of str.toLowerC)
      if (vowels.includes(char))
        count++;
}
return count;

function removeSpaces(str) {
    return str.replace(/\s+/g, '');
}

function sumArray(arr) {
    return arr.reduce((acc, curr) => acc + curr, 0);
}

function filterEvenNumbers(arr) {
    return arr.filter(num => num % 2 === 0);
}


function findMax(arr) {
    return Math.max(...arr);
}

function flattenArray(arr) {
return arr.flat(1);
}

function uniqueValues(arr) {
    return [... Set(arr)];
}

function printNumbers(n) {
    for (let i = 1; i <= n; i++)
        console.log(i);
}
