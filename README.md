# AfriNet
link it to live site  https://2017070162.github.io/AfriNet/.
<!DOCTYPE html>
<html>
    <title>www.AfriNet.com</title>
  
    <head>
    <style>
    * {
      box-sizing: border-box;
    }
    
    body {
      font-family: Arial;
      padding: 5px;
      background: #f1f1f1;
    }
    
    /* Header/Blog Title */
    .header {
      padding: 0px;
      text-align: center;
      background:rgb(115, 145, 55);
      background-size:cover;
      background-position:center;

    }
    
    h1 {
      font-family: 'raleway';
      font-size: 70px;
    }
    
    /* Style the top navigation bar */
    .topnav {
      overflow: hidden;
      background-color: #333;
    }
    
    /* Style the topnav links */
    .topnav a {
      float: left;
      display: block;
      color: #f2f2f2;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    
    /* Change color on hover */
    .topnav a:hover {
      background-color: #ddd;
      color: black;
    }
    
    /* Create two unequal columns that floats next to each other */
    /* Left column */
    .leftcolumn {   
      float: left;
      width: 75%;
    }
    
    /* Right column */
    .rightcolumn {
      float: left;
      width: 25%;
      background-color: #f1f1f1;
      padding-left: 20px;
    }
    
    /* Add a card effect for articles */
    .card {
      background-color: white;
      padding: 10px;
      margin-top: 10px;
    }
    
    /* Clear floats after the columns */
    .row:after {
      content: "";
      display: table;
      clear: both;
    }
    
    /* Footer */
    .footer {
      padding: 10px;
      text-align: center;
      background:rgb(115, 145, 55);
      margin-top: 10px;
    }
    
    /* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
    @media screen and (max-width: 800px) {
      .leftcolumn, .rightcolumn {   
        width: 100%;
        padding: 20;
      }
    }
    
    /* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
    @media screen and (max-width: 400px) {
      .topnav a {
        float: none;
        width: 100%;
      }
    }
    p{
      font-family: 'Lucida Sans';
      font-weight: bold;
      color:black ;
    }
    h1{
      font-family: 'Lucida Sans';
      font-weight: bold;
    }
    p a{ color:black;

    }

    
 
 </style>
    
    
    </head>
    <body>
    
    <div class="header">
      <h1>AfriNet</h1>
      <p>There is always something new in Africa.</p>
      
    </div>
    
    <div class="topnav">
      <a href="AfriNet.html">Home</a>
      <a href="Updates.html">Updates</a>
      <a href="Tourism.html">Tourism</a>
      <a href="About Us.html" style="float:right">About Us</a>
    </div>
    
    <div class="row">
      <div class="leftcolumn">
        <div class="card">
          <h2>Africa</h2>
        </div>
        <div>
