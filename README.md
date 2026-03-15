<!DOCTYPE html>
<html>
<head>
<title>KAMUI Temple</title>

<style>

body{
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:#e6e6e6;
font-family:serif;
}

.box{
width:420px;
height:450px;
border:6px solid black;
position:relative;
display:flex;
justify-content:center;
align-items:center;
}


.kamui{
position:absolute;
left:-90px;
font-size:26px;
font-weight:bold;
animation:move 2s infinite alternate ease-in-out;
}

@keyframes move{
from{top:210px;}
to{top:240px;}
}


.temple{
position:relative;
width:180px;
height:260px;
display:flex;
flex-direction:column;
align-items:center;
}


.roof-top{
width:0;
height:0;
border-left:25px solid transparent;
border-right:25px solid transparent;
border-bottom:25px solid #8b0000;
}


.roof-main{
width:0;
height:0;
border-left:90px solid transparent;
border-right:90px solid transparent;
border-bottom:45px solid #b30000;
margin-top:-5px;
}


.upper{
width:100px;
height:40px;
background:#d4a373;
border:3px solid black;
}


.roof-mid{
width:0;
height:0;
border-left:70px solid transparent;
border-right:70px solid transparent;
border-bottom:35px solid #c40000;
margin-top:-3px;
}


.body{
width:140px;
height:110px;
background:#c89b6d;
border:3px solid black;
display:flex;
justify-content:space-around;
align-items:flex-end;
padding-bottom:5px;
}


.pillar{
width:12px;
height:80px;
background:#7a4e2d;
}


.door{
width:40px;
height:75px;
background:#5c4033;
}


.stair1{
width:160px;
height:10px;
background:#777;
margin-top:3px;
}

.stair2{
width:140px;
height:10px;
background:#888;
}

.stair3{
width:120px;
height:10px;
background:#999;
}

</style>
</head>

<body>

<div class="box">

<div class="kamui">KAMUI</div>

<div class="temple">

<div class="roof-top"></div>
<div class="roof-main"></div>

<div class="upper"></div>

<div class="roof-mid"></div>

<div class="body">
<div class="pillar"></div>
<div class="door"></div>
<div class="pillar"></div>
</div>

<div class="stair1"></div>
<div class="stair2"></div>
<div class="stair3"></div>

</div>

</div>

</body>
</html>
