`setTimeout()` is a JavaScript function that allows you to schedule a piece of code to run after a specified amount of time. 

It takes two arguments:

+ **Function** You provide setTimeout with a function that you want it to run. This function is often referred to as the 'callback', because it gets called after a specified delay.

+ **Delay:** You specify the amount of time (in milliseconds) to wait before running the function.

### Here is an example:

--- code ---
---
language: js
filename:
line_numbers: true
line_number_start: 1
line_highlights: 
---


function delayedFunction() {
  console.log("2 seconds have passed");
}
setTimeout(delayedFunction, 2000);

--- /code ---

Line 1 defines the function and the callback.

Line 4 calls setTimeout with two arguments:
1) the function (`delayedFunction`)
2) the delay in milliseconds (`2000`) 