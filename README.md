# Skola
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
    <ol>
      <li><a href="#">Vēsture</a></li>
      <li><a href="#">Skolas nosaukumu maiņas</a></li>
      <li><a href="#">Zināmie skolas vadītāji (1229—1804)</a></li>
	  <li><a href="#">Skolas absolventi</a></li>
    </ol>
  </nav>
  
  <article>
    <div><h1>Vēsture</h1>
    <p><body rightmargiin="10">Rīgas Valsts 1. ģimnāzija (saīsinājumā RV1Ģ vai RV1.ģ) ir vispārējās pamata un vidējās izglītības iestāde Rīgā. Tā ir pilsētas senākā skola. Ģimnāzija specializējas matemātikas un valodu padziļinātā apgūšanā. Mācības šajā skolā notiek latviešu valodā.
    <p>Kopš 1996. gada ģimnāzija piedalās Starptautiskā bakalaurāta mācību programmas realizācijas projektā. Skolai kā pirmajai Latvijā dibināta absolventu un draugu biedrība ar mērķi finansiāli atbalstīt skolu. Skolā darbojas jauniešu koris "Kamēr...". Kopš 2009. gada Draudzīgā aicinājuma fonda skolu reitingā un kopš 2013. gada Ata Kronvalda fonda Latvijas skolu reitingā Rīgas Valsts 1. ģimnāzija ieņem pirmo vietu ģimnāziju un lielo skolu grupā.</p>
    <p>Lai iegūtu vietu skolā, ir jāiztur matemātikas konkurss, kurā uz vienu vietu pretendē 8-10 skolēni. 9. klases noslēgumā skolēniem jāiztur vēl viens matemātikas konkurss, lai saglabātu vietu skolā. 2019. gadā konkursam uz 10. klasi pieteicās vairāk nekā tūkstoš Latvijas 9. klašu skolēnu.</p>
    <p>Skolas pastāvēšanai iespējams izsekot līdz pat 1211. gadam, kad bīskaps Alberts Rīgā nodibināja Svētās Marijas katedrāli un pie tās — Livonijas bīskapijas domkapitula klosteri. Kādā 1239. gada 19. aprīļa dokumentā minēts, ka domkapitula sholastiķis (mācību pārzinis) bijis kanoniķis Heinrihs, kas uzskatāms par pirmo zināmo Rīgas Doma klostera skolas vadītāju. Skola atradās Doma baznīcas krustejā un bija paredzēta katoļu garīdznieku sagatavošanai. Tās mācību programma atbilstoši viduslaiku latīņu skolu tradīcijai bija sadalīta triviuma ciklā — gramatika, retorika un dialektika. 1524. gadā luterāņu sarīkotajos baznīcu grautiņos katoļu Doma klostera skolu slēdza. 1528. gadā Rīgas rāte skolu no jauna atvēra kā laicīgu pilsētas otrās pakāpes skolu un par Domskolas pirmo rektoru iecēla Nīderlandes kalvinistu sludinātāju Jākobu Batusu (Jacobus Battus, miris 1546. gadā). Pēc viņa Domskolas rektori bija Retgers Pistorijs (no 1538) un Hermanis Vilkens (1554—1561), vēlākais Heidelbergas Universitātes rektors, kas savās publikācijās par burvestībām pieminējis Rīgas apkārtnes vilkačus. Skolā bija trīs klases, kurās mācīja klasiskās valodas, gatavojot tālākām studijām universitātēs. </p>
    <p>Zviedru Vidzemes laikā ar Zviedrijas karaļa Gustava II Ādolfa lēmumu 1631. gadā uz Doma skolas bāzes izveidoja Rīgas Akadēmisko ģimnāziju. Tajā bija trīs augstākās klases, kurās uzņēma pēc piecu klašu Domskolas beigšanas.</p>
    <p>Pirmie ģimnāzijas profesori bija Hermanis Samsons (ģimnāzijas inspektors), Johans Struborgs un Johans Hēfelns, vēlākie profesori bija Johans Brēvers (filozofija, vēsture, teoloģija), Johans Rihmanis (filozofija), Henings Vite (retorika un vēsture), Johans Pauls Mellers (jurisprudence un matemātika), kas ģimnāzijā izveidoja observatoriju ar diviem teleskopiem. </p>
	<p>Ģimnāzijā tika rīkoti publiski disputi un priekšlasījumi, kas saglabājušies līdz mūsu dienām. 1656. gadā ģimnāzijas ēka Otrā Ziemeļu kara laikā krievu bombardēšanas dēļ tika nopostīta, un 1675. gadā Zviedrijas karalis Kārlis XI nodibināja otru pilsētas ģimnāziju — Kārļa liceju (latīniski: Schola Carolina), kas atradās pie Sv. Jēkaba baznīcas. Rīgas Akadēmiskā ģimnāzija pie Rīgas Doma darbu atsāka 1678. gadā. Pēc Rīgas ieņemšanas Lielā Ziemeļu kara laikā 1711. gadā ģimnāzijas klases tika slēgtas, tomēr turpināja darboties Rīgas Domskola, kurā pakāpeniski atjaunojās klasiskās ģimnāzijas tradīcijas. Šajā periodā skolā strādāja vēlākais filozofs Johans Gotfrīds Herders (1764—1769) un rektora amatā bija ievērojamie apgaismības laikmeta darbinieki Karls Filips Mihaels Snells (1780—1787) un Kārlis Gotlobs Zontāgs (no 1788).</p>
    <p>1787. gada 12. jūlijā pēc Krievijas ķeizarienes Katrīnas II rīkojuma tika svinīgi atklāta jaunā ģimnāzijas — Rīgas liceja — ēka Pils laukumā 2 (ēka celta 1785.—1787. gadā, arhitekts Matiass Šonss). 1804. gadā Vidzemes guberņas izglītības reformu laikā Domskolu pārveidoja par Rīgas apriņķa galveno mācību iestādi — Rīgas 1. apriņķa skolu, 1861. gadā — par Rīgas reālģimnāziju, kurā mācījās arī Vilhelms Ostvalds (1864—1871), bet 1873. gadā — par Rīgas Pilsētas ģimnāziju. Publiskai apskatei Rīgas pilsētas reālģimnāzijā 1869. gadā atklāja Rīgas pilsētas gleznu galeriju. 1874. gadā pēc Rīgas galvenā arhitekta Johana Daniela Felsko projekta tika uzcelta tagadējā skolas ēka Raiņa bulvārī 8. Rīgas pilsētas gleznu galerija 1879. gadā tika pārcelta uz netālo Kerkoviusa namu (tagad Kalpaka bulvārī 4). Vecā skolas ēka pie Doma baznicas tika nojaukta 1888. gadā, būvējot pilsētas muzeju. Šajā laikā skolā mācījušies Jānis Pliekšāns, Pēteris Stučka un citi vēlākie latviešu sabiedriskie darbinieki.</p>
	<p>Rusifikācijas periodā 1894. gadā skolu pārveidoja par klasisko ģimnāziju, vēlāk — par valsts ģimnāziju (Государственная гимназия) ar krievu mācību valodu. 1919. gadā Stučkas valdība pārdēvēja to par Rīgas 1. vidusskolu ar latviešu mācību valodu, Latvijas Republikas laikā tika atjaunota Rīgas pilsētas 1. ģimnāzija, kuras direktors ilgu laiku bija Jānis Stiprais (1922–1935), tad Jānis Lapiņš (1935—1939). Pēc Latvijas okupācijas skolu atkal pārdēvēja par Rīgas 1. vidusskolu un 1944. gadā nosauca tās pirmā direktora Leona Paegles vārdā.</p>
	<p>Pēc Latvijas Republikas atjaunošanas skola atguva Rīgas 1. ģimnāzijas vārdu, bet kopš 1996. gada tiek dēvēta par Rīgas Valsts 1. ģimnāziju. Meklējot datus par skolas vēsturi, jāņem vērā, ka laika posmā, kad skolu sauca par Rīgas pilsētas 1. ģimnāziju, pastāvēja arī Rīgas Valsts 1. ģimnāzija, kas nav saistīta ar šajā rakstā minēto skolu.</p>
	<div><h1>Skolas nosaukumu maiņa</h1>
	<p>Pēc Latvijas Valsts arhīva datiem, Rīgas Valsts 1. ģimnāzija piedzīvojusi vismaz 15 dažādus nosaukumus:</p>
	<ul type="circle"> 
	<li> 1211.—1528. — Domkapitula klostera skola </li>
	<li> 1528.—1631. — Rīgas pilsētas Domskola </li>
	<li> 1631.—1710. — Rīgas Akadēmiskā ģimnāzija </li>
	<li> 1711.—1804. — Rīgas Domskola (klasiskā ģimnāzija)</li>
	<li> 1804.—1860. — Rīgas 1. apriņķa skola </li>
	<li> 1861.—1873. — Rīgas Reālģimnāzija </li>
	<li> 1873.—1894. — Rīgas Pilsētas ģimnāzija ar reālskolas un ģimnāzijas klasēm </li>
	<li> 1894.—1895. — 8 klašu klasiskā ģimnāzija </li>
	<li> 1896.—1919. — Valsts ģimnāzija </li>
	<li> 1919.—1920. — 1. vidusskola </li>
	<li> 1920.—1940. — Rīgas pilsētas 1. ģimnāzija </li>
	<li> 1940.—1944. — Rīgas 1. vidusskola </li>
	<li> 1944.—1990. — Ar Darba Sarkanā Karoga ordeni apbalvotā Rīgas L. Paegles 1. vidusskola </li>
	<li> 1990.—1996. — Rīgas 1. ģimnāzija </li>
	<li> 1996.—pašlaik — Rīgas Valsts 1. ģimnāzija </li>
	</ul>
    <div><h1>Zināmie skolas vadītāji (1229—1804)</h1> </div>
	<div class="collumn">
	<h2> Laiks </h2>
	<p> ap 1239. </p>
    <p>1528.—1538. </p>
    <p>no 1538. </p>
    <p>1554.—1561. </p>
    <p>ap 1576. </p>
    <p>1579.—1589. </p>
    <p>1589.—1596. </p>
    <p>no 1631. </p>
    <p>no 1669. </p>
    <p>no 1681. </p>
    <p>1755.—1765. </p>
    <p>1765.—1780. </p>
    <p>1780.—1787. </p>
    <p>no 1788. </p>
    <p>līdz 1804. </p>
	<div class="collumn" style="background colour:#aaa;">
	<h2> Personas </h2>
	<p>mācību pārzinis (scholasticus) Domkapitula kanoniķis Heinrihs</p>
	<p>rektors Jakobs Batuss (Jacobus Battus, miris 1546)</p>
	<p>rektors Retgers Pistorijs (Bekers)</p>
	<p>rektors Hermanis Vilkens (Vilikinds, Vitekinds)</p>
	<p>rektors Georgs Marsovs</p>
	<p>rektors Heinrihs Mellers</p>
	<p>rektors un inspektors Johans Rīvijs</p>
	<p>ģimnāzijas inspektors Hermanis Samsons</p>
	<p>rektors Georgs Lauterbahs</p>
	<p>rektors Mihaels Pinsderfers (Pinsdörffer)</p>
	<p>rektors un inspektors Johans Gothelfs Lindners</p>
	<p>rektors Gotlībs Šlēgels</p>
	<p>rektors Karls Filips Mihaels Snells</p>
	<p>rektors Kārlis Gotlobs Zontāgs</p>
	<p>rektors Johans Augusts Albanuss</p>
	
<footer>
  <p>Footer</p>
</footer>
