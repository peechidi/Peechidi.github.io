<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Coursera assignment</title>
<style>
*{box-sizing: border-box;}

h1{font-size:75%;}
h2{font-size:25%;
Float:right;
height:10px;
width:50px;
border:1px solid black;}
#h3{background-color:blue;}
#h4{background-color:green;}
#h5{background-color:red;}
.row{width:1200;}
.column{
  float: left;
  width: 1200;
  padding: 20px;
background-color:gray;
border:1px solid black;
margin:5px;}
/*for desktop: */
@media screen and (min-width: 992px){.row{width:400px;}
}

/*for mobile phone: */
@media screen and (max-width: 767px){.row{width:1200px;}
}
/*For tablets: */
@media screen and (max-width: 991px) and (min-width:768px){.row{width:600px;}
}
</style>
</head>
<body>

<h1>My Responsive Design</h1>

<div class="row">
  <div class="column">
    <h2 id="h3">DESIGN</h2>
    <p>HELLO there. wo-hoo welcome to my responsive design on coursera.</p>
  </div>
  
  <div class="column">
    <h2 id="h4">LAYOUT</h2>
    <p>YEAH I am really loving this course and am making my layout</p>
  </div>
  
  <div class="column">
    <h2 id="h5">MEDIA QUERY</h2>
    <p>WHOA media query, I really don't get all of it. can you please help out.</p>
  </div>
</div>
  </body>
</html>

