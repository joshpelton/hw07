# hw07
  Joshua Pelton      Dennis Scheglov
  
  Provided with the equation (x^n)e^-x)dx, backwards recursion was used to integrate from 0 to 1 and minimize inherent error.  
The error in calculating pi was diminished with a modification to the provided equation. By removing the presence of subtraction in the numerator, error was minimized. Initially counting up from n = 0 to n = 100, the situation was flipped such that the program counted *down* from n = 100 to n = 0. The program compares the performance of the recursive function using a high-quality gneeral GSL integrator, with E = 10^-9.
  
  Another goal was to compare the two functions in terms of the times they took per call, in a similar fashion to Midterm 1; by
calling them multiple times and then dividing by the number of calls for greater accuracy.
  
## Results
   The general integrator took 1.1362176e-3 seconds/call.
   The recursive integration took 6.781900e-7 seconds/call.
   We found that the recursive integrator was 1.675454e03 times faster than the general integrator.
# hw07
