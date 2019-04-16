# 60_wrapBinarySearch

2. log_2(n) = count means that 2 to the *count* power is equal to *n*. Its graph is increasing and concave. Moreover, there is a vertical asymptote at x = 0, and the domain of the function is (0, infinity).

3. **Problem**
   Find the index of the element with the specified value in a list.

   **Recursive abstraction**
   When I am asked to find the index of the element with the specified value in a list
   , I can find the index of the element with the specified value in a sublist of that list.

   **Steps for the recursive solution**
      **Instructions for base case**
   0. **Base case 0**: If the list is empty, return -1. Otherwise ...
   0. **Base case 1**: If the element midway in the list is equal to the specified value, return the index of that element. Otherwise ...
      **Instructions for recursive case**:
   1. **Additional Processing**: If the element midway in the list is greater than the specified value,
   2. **Combine**: return the result of ...
   3. **Recursive abstraction**: applying the process on the sublist to the left of that element.
   1. **Additional Processing**: otherwise ...
   2. **Combine**: return the result of ...
   3. **Recursive abstraction**: applying the process on the sublist to the right of that element.
