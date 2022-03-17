<section>
    <p class="explanation">Below, a For Statement is calculating and printing the sum and product of every fourth integer from 5 - 21 inclusive. In the second section, a While Statement is calculating and printing the sum and product of every third integer from 3 - 21 inclusive.</p>
    <div id="drag" class="hw4-part1-divbox ui-draggable ui-draggable-handle" style="position: relative; width: 720px; inset: -9px auto auto -94px; height: 361.188px;">
      <h2>For Statement:</h2>
      <p id="for-sum">The sum of 5 + 9 + 13 + 17 + 21 is 65.</p>
      <p id="for-product">The product of 5 * 9 * 13 * 17 * 21 is 208,845.</p>
      <h2>While Statement:</h2>
      <p id="while-sum">The sum of 3 + 6 + 9 + 12 + 15 + 18 + 21 is 84.</p>
      <p id="while-product">The product of 3 * 6 * 9 * 12 * 15 * 18 * 21 is 11,022,480.</p>
      <p class="drag-box">*(drag this entire box around, it moves via JQuery UI!)</p>
    </div>

    <!-- <div class="explanation">
      <h3>Use Cases:</h3>
      <p>Study tool for elementary students.</p>
    </div> -->
    <div class="bottom-buttons">
      <a href="hw4.html" class="btn btn-success btn-md">HW 4 Home Page</a>
      <a href="index.html" class="btn btn-success btn-md">CNIT 133 Home Page</a>
    </div>
  </section>
  <br>
  <script>

  var sum = 0;
  for (var number = 5; number <= 21; number += 4){
    sum += number;
  }
  document.getElementById("for-sum").innerHTML = "The sum of 5 + 9 + 13 + 17 + 21 is " + sum + ".";

  var product = 1;
  for (var x = 5; x <= 21; x += 4){
    product = product * x;
  }
  document.getElementById("for-product").innerHTML = "The product of 5 * 9 * 13 * 17 * 21 is " + product.toLocaleString(2) + ".";

  var x = 0;
  var sum = 0;
  while (x < 21){
    x = 3 + x;
    sum = x + sum;
  }
  document.getElementById("while-sum").innerHTML = "The sum of 3 + 6 + 9 + 12 + 15 + 18 + 21 is " + sum + ".";

  var whileProduct = 1;
  var y = 3;
  while (y <= 21) {
    whileProduct *= y;
    y = y + 3;
  }
  document.getElementById("while-product").innerHTML = "The product of 3 * 6 * 9 * 12 * 15 * 18 * 21 is " + whileProduct.toLocaleString(2) + ".";

  </script>
  
  
