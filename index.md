<html>

  <head>
    <title> GTulator </title>
    <style>
table, th, td {
text-align: center;
/* background-color: #999966;
border: groove;
border-radius: 5px;*/
  }

table {
  width: 100%;
  height:100%;
}
.button {
 
  background-color: #999966; 
  border: none;
  color: white;
  width:98%;
  height:90%;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 5px;
}
.display {
 
  background-color: #999966; 
  border: none;
  color: BLACK;
  width:98%;
  text-align: right;
  text-decoration: none;
  display: inline-block;
  font-size: 76px;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 5px;
}

</style>
  <body>
    <h1 style="text-align:center"> "The GTulator" </h1>
    <form name="calculator">
      <table>
        <tr>
          <td colspan="4">
            <input type="text" name="display" class="display" id="display" disabled>
          </td>
        </tr>
        <tr>
          <td><input type="button" class="button" name="seven" value="7" onclick="calculator.display.value += '7'"></td>
          <td><input type="button" class="button" name="eight" value="8" onclick="calculator.display.value += '8'"></td>
          <td><input type="button" class="button" name="nine" value="9" onclick="calculator.display.value += '9'"></td>
          <td><input type="button" class="button" class="operator" name="times" value="/" onclick="calculator.display.value += '/'"></td>
        </tr>
        <tr>
          <td><input type="button" class="button" name="seven" value="7" onclick="calculator.display.value += '7'"></td>
          <td><input type="button" class="button" name="eight" value="8" onclick="calculator.display.value += '8'"></td>
          <td><input type="button" class="button" name="nine" value="9" onclick="calculator.display.value += '9'"></td>
          <td><input type="button" class="button" class="operator" name="times" value="x" onclick="calculator.display.value += '*'"></td>
        </tr>
        
        <tr>
          <td><input type="button" class="button" name="four" value="4" onclick="calculator.display.value += '4'"></td>
          <td><input type="button" class="button" name="five" value="5" onclick="calculator.display.value += '5'"></td>
          <td><input type="button" class="button" name="six" value="6" onclick="calculator.display.value += '6'"></td>
          <td><input type="button" class="button" class="operator" name="minus" value="-" onclick="calculator.display.value += '-'"></td>
        </tr>
        <tr>
          <td><input type="button" class="button" name="one" value="1" onclick="calculator.display.value += '1'"></td>
          <td><input type="button" class="button" name="two" value="2" onclick="calculator.display.value += '2'"></td>
          <td><input type="button" class="button" name="three" value="3" onclick="calculator.display.value += '3'"></td>
          <td><input type="button" class="button" class="operator" name="plus" value="+" onclick="calculator.display.value += '+'"></td>
        </tr>
        <tr>
          <td><input type="button" class="button" id="clear" name="clear" value="c" onclick="calculator.display.value = ''"></td>
          <td><input type="button" class="button" name="zero" value="0" onclick="calculator.display.value += '0'"></td>
          
          <td><input type="button" class="button" class="operator" name="div" value="." onclick="calculator.display.value += '.'"></td>
          <td><input type="button" class="button" name="doit" value="=" onclick="calculator.display.value = eval(calculator.display.value)"></td>
        </tr>
      </table>
    </form>
  </body>
  </head>

</html>
