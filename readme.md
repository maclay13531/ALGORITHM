# ALGORITHM PANEL
## Using JAVASCRIPT lanaguage

## List
1. FizzBuzz
2. Fibonacci

### Content
1. Fizz Buzz
	* See fizzbuzz.html
	* Basic algorithm to find divisible numbers
	* Find all the numbers that are divisible by 3 and 5

		var list = [];  
		for(var i = 0; i <= 100; i++){  
		&nbsp;&nbsp;&nbsp;&nbsp;if(i % 3 == 0 & i % 5 == 0){  
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;list.push(i);  
		&nbsp;&nbsp;&nbsp;&nbsp;}  
		}  
		console.log(list);  

2. Fibonacci
	* See fibonacci.html
	* Sequence addition of last two numbers in a list
	* First two number will be given to start the sequence
	* Find the 10th fibonacci number. (1 will be considered as the first number)

		var list = [1, 2];  
		for(let i = 1; i < 10; i++){  
		&nbsp;&nbsp;&nbsp;&nbsp;var numberToAdd = list[i - 1] + list[i];  
		&nbsp;&nbsp;&nbsp;&nbsp;list.push(numberToAdd);  
		}  
		console.log(list[9]);  

3. Bubblesort
	* See bubblesort.html
	* Sorting an array with unordered numbers without using a sort method
	
