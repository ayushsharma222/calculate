<!DOCTYPE html>
<html>
<head>
<title>CALCULATOR</title>
<style>
body{
 background:skyblue;
}
*{
   box-sizing:border-box;
   -webkit-box-sizing:border-box;
   -moz-box-sizing:border-box;
}
.wrap{
     width:400px;
     margin:auto;
     height:auto;
     background:black;
     padding:15px;
}
input[type=text] {
    width:100%;
    padding:10px;
    font-size:22px;
    font-width:bold;
    margin-top:20px;
    border-radius:5px;
}
input[type=button] {
    width:89px;
    padding:10px;
    font-size:22px;
    font-width:bold;
    border-radius:5px;
}
#del{
    width:100%;
}
</style>
</head>
<body>
<div class ="wrap">
    <form name ="cal">
       <input type ="text" name ="display">
       <br><br>

       <input type ="button" value ="9" onclick ="cal.display.value+='9'">
       <input type ="button" value ="8" onclick ="cal.display.value+='8'">
       <input type ="button" value ="7" onclick ="cal.display.value+='7'">
       <input type ="button" value ="+" onclick ="cal.display.value+='+'">
       <br><br>
       <input type ="button" value ="6" onclick ="cal.display.value+='6'">
       <input type ="button" value ="5" onclick ="cal.display.value+='5'">
       <input type ="button" value ="4" onclick ="cal.display.value+='4'">
       <input type ="button" value ="-" onclick ="cal.display.value+='-'">
       <br><br>
       <input type ="button" value ="3" onclick ="cal.display.value+='3'">
       <input type ="button" value ="2" onclick ="cal.display.value+='2'">
       <input type ="button" value ="1" onclick ="cal.display.value+='1'">
       <input type ="button" value ="*" onclick ="cal.display.value+='*'">
       <br><br>
       <input type ="button" value ="0" onclick ="cal.display.value+='0'">
       <input type ="button" value ="/" onclick ="cal.display.value+='/'">
       <input type ="button" value ="%" onclick ="cal.display.value+='%'">
       <input type ="button" value ="=" onclick ="cal.display.value=eval(cal.display.value)">
       <br><br>
       <input type ="button" value ="DELETE" onclick ="cal.display.value= ''" id ="del">
    </form>
    </div>
    </body>
    </html>
