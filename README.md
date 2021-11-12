<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arama Shop</title>
    <link rel="shortcut icon" type="image/png" href="/images/favicon.png"/>

<style>
    .header{
        background-color: darksalmon;
        text-align: center;
        padding: 50px;
    }
.topnav{
    overflow: hidden;
    background-color: darkslategray;
}
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.column {
  float: left;
  padding: 10px;
}
.column.side{
    
    width: 25%;
    
}
.column.middle{
    width: 50%;
   

}
.row:after{
    content: "";
    display: table;
    clear: both;
}
@media screen and (max-width:600px) {
  .column.side, .column.middle {
    width: 100%;
  }
}
.body{
    background-color: #FFEBCD;
}
.h1{
    text-align: center;
}
.img{
    width: 300px;
    height: 300px;
    border-radius: 50px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    opacity: 0.9;
}
.topnav a:hover {
  background-color: #ddd;
  color: black;}
.footer{
  background-color: darkslategray;
  padding: 10px;
  text-align: center;}

</style>

</head>
<body class="body">
<div class="header">
    <h2>Header</h2>
    <img src="/images/aramalogo.jpg" class="img">
</div>

<div class="topnav">
    <a href="#">Link</a>
    <a href="#">Link</a>
    <a href="#">Link</a>
  </div>
    <div>
   <h1 class="h1">Arama Shop</h1>
</div>
<div class="row">
    <div class="column side">
      <h2>Side</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit..</p>
    </div>
    
    <div class="column middle">
      <h2>Main Content</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sit amet pretium urna. Vivamus venenatis velit nec neque ultricies, eget elementum magna tristique. Quisque vehicula, risus eget aliquam placerat, purus leo tincidunt eros, eget luctus quam orci in velit. Praesent scelerisque tortor sed accumsan convallis.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas sit amet pretium urna. Vivamus venenatis velit nec neque ultricies, eget elementum magna tristique. Quisque vehicula, risus eget aliquam placerat, purus leo tincidunt eros, eget luctus quam orci in velit. Praesent scelerisque tortor sed accumsan convallis.</p>
    </div>
    
    <div class="column side">
      <h2>Side</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit..</p>
    </div>
  </div>
<div class="footer"> 
     <h2>footer</h2></div>



</body>

</html>
