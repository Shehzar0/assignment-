# assignment-3
/*QUESTION-1

function addNumberTo(num){
    return function(value){
        return num + value;
    };
}

let addFiveTo = addNumberTo(3); // creates a closure that adds 3 to any number.
let result = addFiveTo(4); // return 7
console.log(result); //output is 7

QUESTION-2

function searchArray(array, value) {
    // base case: if the array is empty, the value is not found
    if (array.length === 0) {
      return false;
    }
  
    // check if the first element of the array is the value
    if (array[0] === value) {
      return true;
    }
  
    // recursive case: call searchArray on the rest of the array
    return searchArray(array.slice(1), value);
  }
  let myArray = [2, 4, 6, 8, 10];
  let searchValue = 2;
  
  let isValueFound = searchArray(myArray, searchValue);
  
  console.log(isValueFound); // true

  QUESTION-3

  function addParagraph(text) {
    const paragraph = document.createElement('p');
    const content = document.createTextNode(text);
    paragraph.appendChild(content);
    document.body.appendChild(paragraph);
  }
   paragraph('This is a new paragraph added with JavaScript!');

   QUESTION-4
  
   function addListItem(text) {
    const ul = document.querySelector('ul'); // Replace 'ul' with the ID or class of your unordered list
    const li = document.createElement('li');
    const content = document.createTextNode(text);
    li.appendChild(content);
    ul.appendChild(li);
  }
  addListItem('This is a new list item added with JavaScript!');*/
