# Python-hello-world
<DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css"
    <script defer src="https://pyscript.net/latest/pyscript.js"></head>script>
  <style>
    label{display:block;}
  </style>
</head>
<body>
  <form>
    <label for="operandOne">X:</label>label name="operandOne" id="operandOne" value='10'>
    <label for="total">Result:</label><div name="total" id="total"></div>
  </form>
  <py-script>
    result = Element("total")
result.write("Hello!  The input says:" + str(operandOne))
  </py-script>
</body>
</html>
