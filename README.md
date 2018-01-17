# jsfiddleCountUpBy


var numberOne = parseInt(prompt("Enter a number"));

if (isNaN(numberOne)) {
  alert("Enter numbers only.");
} else {


  var multiple = parseInt(prompt("Enter another number"));


  if (isNaN(multiple)) {
    alert("Enter numbers only.")
  } else {

    var instances = numberOne / multiple;

    var numberArray = [];
    for (i = 0; i < instances; i += 1) {
      numberArray.push(multiple + i * multiple);
    }
    alert("Your number is " + numberArray);
  }
}
