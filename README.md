<!DOCTYPE html>
<html>
<head>
<title>calculater project by Js</title>
  <style>
     
*{
  margin:15px;
}
main{
  height: 600px;
width:350px;
  border:2px solid black;
  border-radius:10px; 
}
#display{
  height: 69px;
width: 315px;
border-radius:10px;
  font-size:30px

}
#container{
  display:grid;
  grid-template-columns: auto auto  auto auto;
  gap:10px
}
.box{
  height:45px;
  width:45px;
  border:1px solid black;
  border-radius:50%;
  text-align:center;
  font-size:30px;
  color:#333030;
}
.box:hover {
  height:44px;
  width: 44px;
  background-color:#d3edd3
}
#c{
  background-color:#ff8800
}
#s{
  background-color:#e6e6e6
}
#q{
  background-color:#e6e6e6
}
#h{
  background-color:#e6e6e6
}
#g{
  background-color:#e6e6e6
}
#m{
  background-color:#e6e6e6
}

#p{
  background-color:#e6e6e6
}
#b{
  background-color:#e6e6e6
}
  </style>
  
  </head>
<body>

  <main>
<input type="text" id="display" readonly/>
    

<div id="container">
  <div class="box"id="s" onclick="a = ''
document.getElementById('display').value=a;">C</div>
  
  <div class="box"id="q" onclick="a = a+'%'
document.getElementById('display').value=a;">%</div>
  
<div class="box"id="h" onclick="a = a+'developed by :Jarif    roll=6'
document.getElementById('display').value=a;">#</div>
  
<div class="box"id="b" onclick="a = a+'/'
document.getElementById('display').value=a;">/</div>
  
<div class="box" onclick="a = a+'7'
document.getElementById('display').value=a;">7</div>
  
<div class="box" onclick="a = a+'8'
document.getElementById('display').value=a;">8</div>

<div class="box" onclick="a = a+'9'
document.getElementById('display').value=a;">9</div>
  
<div class="box"id="g" onclick="a = a+'* '
document.getElementById('display').value=a;">*</div>
  
<div class="box" onclick="a = a+'4'
document.getElementById('display').value=a;">4</div>
  
  <div class="box" onclick="a = a+'5'
document.getElementById('display').value=a;">5</div>
  
<div class="box" onclick="a = a+'6'
document.getElementById('display').value=a;">6</div>
  
<div class="box"id="m"onclick="a = a+'-'
document.getElementById('display').value=a;"><b>-</b></div>
  
<div class="box"onclick="a = a+'1'
document.getElementById('display').value=a;">1</div>
  
  <div class="box"onclick="a = a+'2'
document.getElementById('display').value=a;">2</div>
  
<div class="box"onclick="a = a+'3'
document.getElementById('display').value=a;">3</div>
  
<div class="box"id="p"onclick="a = a+'+'
document.getElementById('display').value=a;">+</div>
  
<div class="box"onclick="a = a+'00'
document.getElementById('display').value=a;">00</div>
  
<div class="box"onclick="a = a+'0'
document.getElementById('display').value=a;">0</div>
  
<div class="box"onclick="a = a+'.'
document.getElementById('display').value=a;"><b>.</b></div>
  
<div class="box"id="c"onclick="
  a = eval(a);

document.getElementById('display').value=a;"><b>=</b></div>
</div>
</main>
  <script>
     let a ='';
document.getElementById('display').value=a;
</script>
</body>
</html>
<!--finished -->

