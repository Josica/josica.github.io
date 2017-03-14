---
layout: post
title: "Ruby Array Methods Reference"
description: "Using Ruby's each, map, select and inject methods on arrays."
tags: [ruby]
categories: [programming]
---

<!-- <h2 class="header medium-header">h2 header with 'header medium-header' class</h2> -->
<center>
<img class="img-round" src="{{ site.baseurl }}/assets/images/rubyarrays.png">
<br><br>
<h3 class="header large-header">The .each method</h3>
<h5>Used for iterating over a collection in Ruby. Executes an action using each element of the array as a parameter. It implicitly returns the original array.</h5>
</center>
Example:
<center>
<script src="//repl.it/embed/GThz/8.js"></script>
</center>
<p>In this example, we are iterating over the desserts array, and printing out that we love each dessert, one at a time. The return value is the original array.</p>
<p>If we need to change the return value, we can use the .map method.</p>


<hr>
<center>
<h3 class="header large-header">The .map method</h3>
<h5>Used for iterating over a collection in Ruby when you want to modify and return a new value. Performs an action on each array element. The original array is not modified.</h5>
</center>
Example:
<center>
<script src="//repl.it/embed/GTsL/1.js"></script>
</center>
<p>In this example, we are iterating over the desserts array, and modifying each element in the array, one at a time. The return value is the new modified array.</p>

<hr>
<center>
<h3 class="header large-header">The .select method</h3>
<h5>Used for filtering a collection in Ruby. Selects values from an array by running a condition for each array element and, if true, that element gets added to a new array which is returned. </h5>
</center>
Example:
<center>
<script src="//repl.it/embed/GTvX/0.js"></script>
</center>
<p>In this example, we are running the condition to select all dessert prices that are greater than 2, over each element in the dessert_prices array, and adding each element that returns true into the new array, one at a time. The return value is the new array of prices which are greater than 2.</p>
<hr>
<center>
<h3 class="header large-header">The .inject method</h3>
<h5>Used for totaling values in an array in Ruby. Takes an accumulator (sum) and changes it as many times as there are elements in the array. Returns the final value of the accumulator. Optional initial value for sum.</h5>
</center>
Example:
<center>
<script src="//repl.it/embed/GTwj/1.js"></script>
</center>
<hr>
