# Naanmudhalvan
Mohammed suhail rasith
<html>
<head>
<title>Objects</title>
</head>
<body>
<p id="demo"></p>
<script type="text/javascript"> 
document.write("DATE OBJECTS"); 
document.write("<br>"); 
document.write("***** *******");
 document.write("<br>");

var d = new Date();
 document.write(d.getDate()); 
document.write(".");
 document.write(d.getMonth()+1); 
document.write(".");
 document.write(d.getFullYear()); 
document.write("<br><br>");

document.write("NUMBER  OBJECTS"); 
document.write("<br>");
 document.write("****** *******");
 document.write("<br>");

var x = 10;
var y = new Number(10); 
document.write(typeof x);
 document.write("<br>");
 document.write(typeof y); 
document.write("<br><br>");

document.write("EVENT OBJECTS");
 document.write("<br>"); 
document.write("***** ********"); 
document.write("<br><br>");
function GetEventType(eventObj)
{
alert("The type of the event : "+eventObj.type);
}
document.write("<br>");
</script>
<button onclick="GetEventType(arguments[0]);">Click on Me!</button>
</body>
</html>
