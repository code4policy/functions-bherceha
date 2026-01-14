# Assignment: functions

As usual, clone this repo to your `assignments` directory (or wherever you like to work). 

## Python 

We'll use the `pytest` Python library to test the functions we write below. Let's install `pytest` in a Python virtual environment: 

```
python3 -m venv virtualenv         # create a python virtual environment
source ./virtualenv/bin/activate   # activate the virtual environment
pip install pytest                 # install the pytest package
```

1. create a new branch in your git repo called `calculator`

2. inside that branch create a new file called `calculator.py`

3. Write a program that defines four functions (multiply, add, subtract, and divide). These functions should not print anything, they should simply perform a mathematical operation on the two arguments and return the value.

4. You can test whether your functions work by running `pytest` in the current directory. Don't worry if you don't pass all the tests! At this step we only expect you to pass tests for `add`, `subtract`, `multiply`, and `divide`)
	You should ideally see something in the ouptut that looks like
	```
	 2 failed, 4 passed in 0.03s
	 ```

6. Commit to git `git commit -m "add functions to calculator"`and push the change to github.  `git push`

7. At the bottom of the file, Call the function and print a line explaining what is happening. Like this:
	
	```python
	print("I'm going use the calculator functions to multiply 5 and 6")
	x = multiply(5,6)
	print(x)
	```
	
8. Commit this change and explain what you just did in the commit message

9. Run the file with the following command to make sure your python is all right:

	```
	python3 calculator.py
	```

10. Make sure everything works correctly and issue a pull request on github back to the main branch with a message explaining what changes you made in this branch.

11. Accept the pull request into the main branch and delete the `calculator` branch on github.
12. Checkout the main branch, and pull the version of main with the calculator branch merged

	```
	git checkout main
	git pull
	```

13. Delete your local version of the calculator branch

	```
	git branch -D calculator
	```

14. Create a new branch from `main`. In the new branch, add two more functions, `square` and `cube`. both should take a single number as an argument and return the number raised to the appropriate power. 
15. Make a function called `square_n_times` that takes two arguments, `number` and `n`. Have the function square the number `n` times and return the sum.
16. PR the new branch to `main`. Your `calcluator.py` in `main` should now have functions for addition, subtraction, multiplication, division, squaring, cubing, and adding squares `n` times. 

## Javascript (ungraded)

### Install `node`
On WSL: `sudo apt-get install npm`
On Mac: `brew install npm`

### Tasks 
1. create a new branch `js-calculator`
2. inside that branch create a new file called `calculator.js`

3. Write (in javascript) a program that defines four functions (multiply, add, subtract, and divide). These functions should not print anything, they should simply perform a mathematical operation on the two arguments and return the value.

4. Commit to git `git commit -m "add functions to calculator"`and push the change to github.  `git push`

5. At the bottom of the file, Call the function and print a line explaining what is happening. Like this:
	
	```javascript
	console.log("I'm going use the calculator functions to multiply 5 and 6")
	var x = multiply(5,6)
	console.log(x)
	```

6. Commit this change and explain what you just did in the commit message

7. Run the file with the following command to make sure your JavaScript is all right:

	```
	node calculator.js
	```

8. Make sure everything works correctly and issue a pull request on github back to the main branch with a message explaining what changes you made in this branch.

9. Accept the pull request into the main branch and delete the `js-calculator` branch on github.

10. Checkout the main branch, and pull the version of main with the calculator branch merged

	```
	git checkout main
	git pull
	```

11. Delete your local version of the js-calculator branch

	```
	git branch -D js-calculator
	```
