## Website Performance Optimization portfolio project

Achieved Pagespeed Insights score of 87 out of 100 for index.html by,
    1.optimised the pictures of index.html by imageoptim
 
Achieved 60 fps for pizza.html by,
    1. Optimized the loops to eliminate multiple instants of DOM acess.
    2. Replacing document.querySelector() by document.getElementById() as these web api call is faster.
    3. Replacing document.querySelectorAll() by document.getElementsByClassName() as these javascript web api call is faster than previous one.
    4. It is better to save the array length, which is part of the condition statement and it enhance more efficiency.
    5. The 'newwidth' and 'dx' variables go out the loop. As,the pizza sizes are all the same, a fixed value defined for starting the iteration/loop for both variables.
    6. A variable pizzasDiv is assigned for document.getElementById("randomPizzas") outside of the loop.
    7. The phase variable is initialized so the for loop will prevent it from being created every time the loop is executed.
    8. The number of background pizzas is reduced to 24.
    9. The elem variable is initialized so the for loop will prevent it from being created every time the loop is executed.
    10. The document.getElementById() Web API call is faster. So, moving this DOM call outside the for statement and save it into a local variable.
