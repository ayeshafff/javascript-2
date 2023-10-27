# javascript-2
Perform sorting of an array in descending order.

function descendingSort(array) {
  return array.sort((a, b) => b - a);
}

const array = [5, 1, 4, 2, 3];
const sortedArray = descendingSort(array);
console.log(sortedArray);
