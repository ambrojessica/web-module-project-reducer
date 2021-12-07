# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* onClick is triggered
*goes to actions and finds the handleClick
*in the handleClick it looks for the addOne function
*addOne function executes and returns reducer function from reducer folder
*finds the ADD_ONE function and executes it
* TotalDisplay shows the total plus 1.
