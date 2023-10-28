# kavin
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #f1f1f1;
  padding: 20px;
  font-family: Arial;
}

/* Center website */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: white;
  padding: 10px;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<!-- MAIN (Center website) -->
<div class="main">

<h1>WELCOME TO MY LIBRARY</h1>
<hr>

<h2>my book collection</h2>
<p>the most valuable gifi you can receive is an honest friend.</p>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src="C:\Users\ELCOT\Desktop\kavin 1\img 7.jpeg" alt="books" style="width:100%">
      <h3>THER WILL BE SPACE</h3>
      <p>"Songs, stars, people, when you can't choose any of these, you brace yourself and face yourself.".</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="C:\Users\ELCOT\Desktop\kavin2\img 6.jpeg" alt="Lights" style="width:100%">
      <h3>KAN SIMITTAL</h3>
      <p>The past will hurt while it's sweet or it'll be sweet while it hurts. The present will shake it off.</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="C:\Users\ELCOT\Desktop\kavin3\img8.jpeg" alt="books" style="width:100%">
      <h3>EZHUTHUPIZHAI</h3>
      <P>The weight of the high responsibility of 'father' that he has accepted for so long is amazing.</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="C:\Users\ELCOT\Desktop\kavin5\img 23.jpeg" alt="books" style="width:100%">
      <h3> THE AIMLESS TRAVELER</h3>
      <p>We survive by exploiting nature for our selfish gains, and the result is sure to end up in unexpected ways..</p>
    </div>
  </div>
<!-- END GRID -->
</div>

<div class="content">
  <img src="C:\Users\ELCOT\Desktop\kavin\img 100.jpeg" alt="N.MUTHUKUMAR" style="width:100%">
  <h3>N.MUTHUKUMAU IS MY FAVORITE LYRICIST IN WORLD</h3>
  <p>Crab, quail, chicken, mutton, fish and everything else is called 'single omelette' which is not worthy to settle on the plate. They will go in with great pain of neglect.</p>
  <p>While reading books you underline your favorite lines in red ink. That would annoy me. 'Don't force your opinion on me. I may not like your favorite line. What are you underlining?' I will be angry. You will say quietly..</p>
  <P>'It is not so. From here I shake hands with the writer who wrote this somewhere.</P>>
</div>

<!-- END MAIN -->
</div>
