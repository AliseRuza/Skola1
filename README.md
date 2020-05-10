# Skola
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Container for flexboxes */
section {
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: #f1f1f1;
  padding: 10px;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
</head>
<body>
<header>
  <h2>Rīgas Valsts 1. ģimnāzija</h2>
</header>

<section>
Satura rādītājs
  <nav>
    <ul>
      <li><a href="#">Vēsture</a></li>
      <li><a href="#">Skolas nosaukumu maiņas</a></li>
      <li><a href="#">Zināmie skolas vadītāji (1229—1804)</a></li>
	  <li><a href="#">Skolas absolventi</a></li>
    </ul>
  </nav>
  
  <article>
    <div><h1>Vēsture</h1></div>
    <p><body rightmargiin="10">Rīgas Valsts 1. ģimnāzija (saīsinājumā RV1Ģ vai RV1.ģ) ir vispārējās pamata un vidējās izglītības iestāde Rīgā. Tā ir pilsētas senākā skola. Ģimnāzija specializējas matemātikas un valodu padziļinātā apgūšanā. Mācības šajā skolā notiek latviešu valodā. </p>
    <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
  </article>
</section>

<footer>
  <p>Footer</p>
</footer>

</body>
</html>
