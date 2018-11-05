# Array
数组


1. 数组降维 [1,2,[3,4,[5,6]]] => [1,2,3,4,5,6]

let arr = [1,2,[3,4,[5,6]]].toString().split(',')；
let arr2 = []；
for(let i = 0; i < arr.length; i++ ) {
  arr2.push( eval(arr[i]) );
}

