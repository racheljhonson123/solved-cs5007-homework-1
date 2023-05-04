Download Link: https://assignmentchef.com/product/solved-cs5007-homework-1
<br>
<h1>1             Arithmetic expressions</h1>

Convert each of the following mathematical expression in an equivalent Python expression. Write the expression in the designated space in your template module a line of Python code.

The values of the three rational variables <em>a</em>, <em>b </em>and <em>c </em>are assigned at the beginning of the template module and should not be modified.

<ol>

 <li>4<em>ab </em>+ <em>bc</em></li>

 <li><em>b</em><sup>3</sup></li>

</ol>

√

<ol>

 <li><em>ab</em></li>

 <li>(<em>ac </em>+ <em>ba</em>)<em>/bc</em></li>

 <li><em>a</em><sup>2 </sup>− <em>b</em><sup>4 </sup>+ 2<em>ab</em></li>

</ol>

<h1>2             Expressions, Python operators</h1>

Write the following Python expressions into the designated places in the template module. Run the module.

<ol>

 <li>(8<em>//</em>6) ∗ 6</li>

 <li>(8<em>/</em>6) ∗ 6</li>

</ol>

Explain in a comment line why the value of expressions <strong>a. </strong>and <strong>b. </strong>are different.

<h1>3             Boolean expressions</h1>

Convert each of the following logical expression in an equivalent Python expression.

Write the expression in the designated space in your template module a line of Python code.

The values of the Boolean variables <em>a</em>, <em>b </em>and <em>c </em>are assigned at the beginning of the template module and should not be modified. Recall that ∨ is “or”, ∧ is “and”, ¬ is “not” and → is implication.

<ol>

 <li><em>a </em>∧ (<em>b </em>∨ <em>c</em>)</li>

 <li><em>a </em>→ (<em>b </em>∨ <em>c</em>)</li>

 <li>(<em>a </em>∧ <em>b</em>) ∨ (¬<em>c</em>)</li>

 <li><em>a </em>→ (<em>b </em>→ (¬<em>c</em>))</li>

</ol>

<h1>4             Function</h1>

Wind chill is defined by the following formula:

Wind Chill = 13<em>.</em>13 + 0<em>.</em>621 × <em>T </em>− 12<em>.</em>1 × <em>V </em><sup>0<em>.</em>15 </sup>+ 0<em>.</em>3967 × <em>T </em>× <em>V </em><sup>0<em>.</em>16</sup>

In this formula, <em>T </em>is the temperature in Celsius and <em>V </em>is the wind velocity in kilometers per hour.

<ul>

 <li>Define a function WindChill in your template module to calculate the wind chill for any temperature and velocity. For instance, a call to WindChill(−20<em>,</em>30) prints the following result:</li>

</ul>

At -20C and 30 kph winds, it feels like -33.1156286189848C

Your function should NOT return anything, but PRINT the result on IDLE. Call your windChill function with arguments -20 for T and 30 for V.

<ul>

 <li>Write a similar function, named WindChill2, that does not print but returns the result. Write an appropriate statement using this second function, so as to print this returned result.</li>

</ul>

<h1>5             Errors in a Python program</h1>

def euc(x1,y1,x2,y1): lambda = (x1-x2)**2 gamma = (y1-y2)**2

return((lambda+gamma)**(1//2)) result = euc(1,3,2,7) print(“result”)

Function euc was written to calculate a distance with following formula:

p((<em>x</em><sub>1 </sub>− <em>x</em><sub>2</sub>)2 + (<em>y</em>1 − <em>y</em>2)2

Unfortunately, the function definition, call and print statement contain 5 errors. Explain in a command line each error, within the template module. Re-write correctly the function and the call/print statement in the template module.

<h1>6             Extra credit</h1>

This part is not mandatory but may provide extra credits, up to 5 points. Consider the following Python function.

def myFct(value): if(value==1):

return value

else: return value+myFct(value-1)

Explain in a comment line the result returned by the function (2 points). You should not paraphrase the code (this will not give you points), but rather explain with one simple sentence what is the result of a call to this function.

B <em>You may print the result of the function call with values </em>3<em>, </em>4 <em>and </em>5 <em>(</em>i.e.<em>, successive calls), for instance. In addition, observe that the function is recursively called by itself in the else statement. What is the effect of this instruction?</em>

Write a simpler function myFct in the template module, that returns exactly the same result, but encoded without using if and else and without the <em>recursion </em>call myFct(value-1). Your function must NOT use more advanced concepts such as while and for loops. (3 points).