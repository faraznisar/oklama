# Just random stuff that no one except me will ever read more than likely.


1. Javascript
  * Using `onClick={someFunction}` directly references the function and executes it on click without creating an extra function, making it more efficient for simple handlers. In contrast, `onClick={() => someFunction()}` creates a new function on each render, ideal for scenarios where arguments need to be passed or additional operations are required before executing the function.

