<!DOCTYPE html>
<html>
  <title>JavaScript</title>
  <head>
  </head>
<body>
  <script>
    alert("Қош келдің!");
  </script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Резюме</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="java.css">
</head>
<body>
   <style type="text/css">
  i { color: red;
    }
    h1 { 
    background: yellow;
     }
   </style>
  <h1> Түркістанова Бәтима </h1>
  <a href="https://ltdfoto.ru/image/XBC3hV"><img src="https://ltdfoto.ru/images/2022/11/30/bati.jpg" alt="bati.jpg"  <img width="380" height="250" alt="WhatsApp-Image-2022-12-05-at-00.52.37.jpg" border="0" /></a>
<hr/>
</style>
</head>
<body>
  <div id="wrapper"> 
    <div id="header">
<body text="blue" background-color="black">
   <h1><i>Түркістанова Бәтима Серікқызы 25 желтоқсан 2003 жылы Маңғыстау облысы Бейнеу ауданында дүниеге келдім.</h1> </i>
</body>
<H1> Отбасымда 6 адамбыз </H1>
<body text="blue">
<UL>
<li> Әкем </li>
<ul type="disk">
<li> Анам </li>
<ul type="circle">
<li> Мен  </li>
<ul type="square">
<li> 2 інім </li>
<ul type="square">
<li> 1 сіңілім </li>
</ul>
<HR align="center" color="red" size=4 width=300%; >
<font color ="blue">
<h2> Хобби : </h2></font>
<font color="black">
<em>
<ol type="I" start="1">
<li> Құрбыларыммен кездесу </li>
<li> кино қарау </li>
</font>
<font><br>
</font>
 <a href="резюме.html">Резюме</a>
 <a href="Расписание.html">Расписание</a>
<script>
  var months = new Array(16);
  months[1]="қаңтар"; months[2]="ақпан"; months[3]="наурыз"; months[4]="сәуір"; months[5]="мамыр"; months[6]="маусым"; months[7]="шілде"; months[8]="тамыз"; months[9]="қыркүйек"; months[10]="қазан"; months[11]="қараша"; months[12]="желтоқсан";

  var time = new Date();
  var thismonth = months[time.getMonth() + 1];
  var date = time.getDate();
  var thisyear = time.getYear();
  var day = time.getDay() + 1;

  if (thisyear < 2000)
      thisyear = thisyear + 1900;
  if (day == 1) DayofWeek = "Жексенбі";
  if (day == 2) DayofWeek = "Дүйсенбі";
  if (day == 3) DayofWeek = "Сейсенбі";
  if (day == 4) DayofWeek = "Сәрсенбі";
  if (day == 5) DayofWeek = "Бейсенбі";
  if (day == 6) DayofWeek = "Жұма";
  if (day == 7) DayofWeek = "Сенбі";
</script>
            
<script>           
setInterval(function() {
  var cd = new Date();
  var clockdat = document.getElementById("clockdat");
  clockdat.innerHTML = cd.toLocaleTimeString();
}, 1000);
</script>
<body    
<div class="center" style="background-color: #e2d0bc; padding:5px;">
  <span style="color:darkgreen;">Бүгін:</span>
  <span style="color:62929e; font-size:18px;">
  <script>
      document.write(date+" ");
      document.write(thismonth+ " "+thisyear+" "+"жыл"+" — "+ DayofWeek);
  </script>
  (<span id="clockdat" style="color:darkgreen;"></span>)
  </span>
</div>
</body
