 ![Joel](Https://GitHub.com/joelwmulongo/fleet/blob/main/joel.gif?raw=true) <br>
 <body style="background-image:url(stackoverflow.png); background-size: cover; background-repeat: no-repeat; "> Current Time: <span id="txt"></span>  
<Html>
<Script language= "javascript">  
window.onload=function(){getTime();}  
function getTime(){  
var today=new Date();  
var h=today.getHours();  
var m=today.getMinutes();  
var s=today.getSeconds();  
// add a zero in front of numbers<10  
m=checkTime(m);  
s=checkTime(s);  
document.getElementById('txt').innerHTML=h+":"+m+":"+s;  
setTimeout(function(){getTime()},1000);  
}  
//setInterval("getTime()",1000);//another way  
function checkTime(i){  
if (i<10){  
  i="0" + i;  
 }  
return i;  
}  
</script>
<Marquee> now yes </marquee> </html>
<Img SRC= "stack_overflow.png" height = "40" width = "40">

 
