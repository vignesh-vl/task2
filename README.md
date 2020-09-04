
<html>
 <head> 
  <style>
    table,h2, h3, h1, p
    {  font-family: Times New Roman;
      text-align:center;
      margin:auto;
      padding:25px;
    }  
  </style> 
 </head> 
 <body id="body"> 
  <h1><i><b>INDIAN PREMIER LEAGUE</b></i> </h1> 
  <b><i><h2><p id="text"></p> </h2></i> </b> 
  <i><h3> <p id="text2"></p> </h3></i> 
  <table> 
   <tbody> 
    <tr> 
     <td><input type="button" value="RCB" id="rcb" style="background-color:red;color:white"></td> 
     <td><input type="button" value="CSK" id="csk" style="background-color:yellow;color:green"></td> 
     <td><input type="button" value="MI" id="mi" style="background-color:blue;color:white"></td> 
    </tr> 
   </tbody> 
  </table> 
  <script>
   function displayfunction()
{var r="Champions 🏆🏆🏆2020 ";
var d="Royal challengers Banglore";
document.getElementById("text").innerHTML=r;
    document.getElementById("text2").innerHTML=d;
    
    document.getElementById("body").style=" background-color:red;color:white";
    
  
  
  
}
function displayfun()
{var r="Champions 🏆🏆🏆2020 ";
var d="Chennai Super Kings ";
document.getElementById("text").innerHTML=r;
    document.getElementById("text2").innerHTML=d;
    
    document.getElementById("body").style=" background-color:yellow;color:green";
    
  
  
  
}

function displayfunc()
{var r="Champions 🏆🏆🏆2020 ";
var d="Mumbai Indians";
document.getElementById("text").innerHTML=r;
    document.getElementById("text2").innerHTML=d;
    
    document.getElementById("body").style=" background-color:blue;color:white";
    
  
  
  
}
    var x = document.getElementById("rcb"); 

x.addEventListener("click", displayfunction);
var  y  = document.getElementById("csk"); 

y.addEventListener("click", displayfun);
var z = document.getElementById("mi"); 

z.addEventListener("click", displayfunc);

</script> 
 </body>
</html>
