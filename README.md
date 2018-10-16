
<html>
    <head>

        <style>body {background-color: powderblue;}
h1   {color: black;}
p    {color: black;}
        table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 100%;
}

td, th {
    border: 1px solid black;
    text-align: left;
    padding: 8px;
}
        </style>
        <style>
ul1 {


    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333333;
}

li{
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 16px;
    text-decoration: none;
}

li a:hover {
    background-color: #111111;
}

</style>
    </head>
    <body>
        <h1 style="background-color:violet;">Hello World</h1>
        <h1>How To Improve English Communication</h1>
        <p>English communication can be improved by interaction with different kind of people and also improved by writing and reading newspapers.Exploring Google will also help to improve english communication. </p>

   <h2 style="font-size:20px;">List of good books that help to improve English</h2>
   <p><i><mark>they are</mark></i></p>
       <ul2 style="list-style-type:square">
           <li>Harry potter </li><br />
           <li>Agatha cristie</li> </ul2>
           <p styl1e="color:purple">Image of a book</p><br />
            <a href="https://images.search.yahoo.com/yhs/search;_ylt=Awr9KRTPmHpb4zEAPlEPxQt.;_ylu=X3oDMTByNWU4cGh1BGNvbG8DZ3ExBHBvcwMxBHZ0aWQDBHNlYwNzYw--?p=books&fr=yhs-pty-pty_extension&hspart=pty&hsimp=yhs-pty_extension#id=0&iurl=http%3A%2F%2Fimg.talkandroid.com%2Fuploads%2F2013%2F11%2Fstack_of_books.jpg&action=click">Image</a>
            <a href="index.html">Home</a>||<a href="index2.html">Contact </a>
                <img src="image of books.jpg" width="200" height="300">

   <h2>Books Table</h2>

<table>
  <tr>
    <th>Books</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Agatha Cristie</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Harry Potter</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Sudha Murthy</td>
    <td>Roland Mendel</td>
    <td>Austria</td>
  </tr>

</table>

<ul1>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul1><br />
   <h3>Countries famous for english communication with their capitals</h3><!--java script-->
<p>Click the button, to hide all elements with the class name "city"</p>

<button onclick="myFunction()">Hide elements</button>

<h2 class="city">London</h2>
<p>London is the capital of England.</p>

<h2 class="city">Washington D C</h2>
<p>Washington D C is the capital of USA.</p>
<script>
function myFunction() {
  var x = document.getElementsByClassName("city");
  for (var i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
}
</script><!--java script-->
<h1>My First Google Map</h1>

<div id="map" style="width:400px;height:400px;background:yellow"></div>

<script>
function myMap() {
var mapOptions = {
    center: new google.maps.LatLng(51.5, -0.12),
    zoom: 10,
    mapTypeId: google.maps.MapTypeId.HYBRID
    }
var map = new google.maps.Map(document.getElementById("map"), mapOptions);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js=myMap"></script>


    </body>

</html>
