<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="description" content="CALCULATOR">
<meta name="viewport" content=width=device-width, initial-scale=1.0">
<title> CALCULATOR </title>
</head>
<body>
<form>
Value 1:<input type="text" id="value1" >
Value 2:<input type="text" id="value2">
Operator:
<select id="operator">
<option value="add">Add</option>
<option value= "min">Minus</option>
<option value= "div">Divide</option>
<option value= "mul">Multiply</option>
</select>
<button type="button" onclick="calc()"> Calculate </button>
</form>
<div id="result"></div>
<script type="text/javascript">
function sumValues()
{
  var x = parseInt(document.queryselector("#value1").value);
  var y = parseInt(document.queryselector("#value2").value);
  var z = document.queryselector("#operator").value;
  var calculate;
  if (z =="add") {
  ccalculate = x + y;
}
 else if (z =="min") {
  ccalculate = x - y;
}
 if (z =="div") {
  ccalculate = x / y;
}
 if (z =="mul") {
  ccalculate = x * y;
}
document.queryselector("#result").innerhtml=calculate;
}
</script>
</body>
</html> 
