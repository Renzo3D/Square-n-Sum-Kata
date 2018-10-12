# Square-n-Sum-Kata



Description :


Complete the square sum method so that it squares each number passed into it and then sums the results together.


For example: squareSum([1, 2, 2]) should return 9 because 1^2 + 2^2 + 2^2 = 9.


No need of explanation this seems to be pretty straigth forward. 

Here is the code for it. 


function squareSum(numbers){

var result = 0;                                   // create a variable result and initilize it with zero.

for(var i=0; i<numbers.length; i++){              // create for loop to go over all the number inside the array.

  result = result + Math.pow(numbers[i],2);       // result (which is zero), we add each number of the array to the power of two.
  
                                                // Math.pow is a JS function that raise the first number to the power of the second number
  
  
                                               //Math.pow(a,b) === 'a' to the power of 'b' ex: Math.pow(4, 2) === 4^2 === 16.
  }

return result;

}
