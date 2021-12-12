/*Tradutor de pt para balêies, um dos meus primeiros programas. Ainda to aprendendo a usar o github*/

let input = 'procurando Nemo, onde ele esta';
const vowels =['a', 'e', 'i', 'o', 'u'];
let resultArray = [];

for(let i = 0; i < input.length; i++){
  //console.log('i is' + i);
  for (let j = 0; j < vowels.length; j++){
    //console.log('j is' + j);
    if(input[i] === vowels[j]){
      resultArray.push(input[i]);
    }
    if(input[i] === 'e'){
      resultArray.push(input[i]);
    }
     if(input[i] === 'u'){
      resultArray.push(input[i]);
    }
  }
};
console.log(resultArray.join('').toUpperCase());
