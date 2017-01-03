# Quadratic Equations Solver

This script has only one function which solves quadratic equation in form like:
![Equation form](http://akak.ru/recipes/pictures/000/013/861_big.jpg)

You can use this script in following way:

1) Clone repository: `git clone https://github.com/Sir-Nightmare/14_pre_commit_hook.git`
2) Import function to your `from quadratic_equations.py import get_roots` 
3) Use function `root1, root2 = get_roots(a, b, c)`

## Tests and pre-commit hook 

The `get_roots` function is tested.  
If you need to modify the function and want to check it before each commit
you can put put `pre-commit` file to `.git\hooks`  
The commit will be done only if all tests will work properly. 
Otherwise an error message will be shown

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
