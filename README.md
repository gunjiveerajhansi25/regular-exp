<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Regular Expressions</h2>

<p>email-address matching:</p>

<p id="demo"></p>

<script>
  let text = "karthibabu20004";
let value = text.match(/[a,b]/g);
document.getElementById("demo").innerHTML = value; 

</script>

</body>
</html>
