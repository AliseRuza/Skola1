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
  background-image:src="images/skola.jpg";
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
  clear:both;
  margin-left:4px;
  margin-right:4px;
  height:4em
  display: block;
}
parent {
   min-height:100%;
   position:relative;
   margin:0 20px 4em
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
      <li><a href="#vesture">Vēsture</a></li>
      <li><a href="#nosaukumi">Skolas nosaukumu maiņas</a></li>
      <li><a href="#vaditaji">Zināmie skolas vadītāji (1229—1804)</a></li>
	  <li><a href="#absolventi">Skolas absolventi</a></li>
    </ol>
  </nav>
  
  <article>
    <div><h1 id="vesture">Vēsture</h1>
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
	<div><h1 id="nosaukumi">Skolas nosaukumu maiņa</h1>
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
    <div><h1 id="vaditaji">Zināmie skolas vadītāji (1229—1804)</h1> </div>
	<table>
	<tr>
    <th>Laiks</th>
    <th>Personas</th>
  </tr>
	<tr>
	<td> ap 1239. </td>
	<td>mācību pārzinis (scholasticus) Domkapitula kanoniķis Heinrihs</td>
	</tr>
	<tr>
    <td>1528.—1538. </td>
	<td>rektors Jakobs Batuss (Jacobus Battus, miris 1546)</td>
	</tr>
	<tr>
    <td>no 1538. </td>
	<td>rektors Retgers Pistorijs (Bekers)</td>
	</tr>
	<tr>
    <td>1554.—1561. </td>
	<td>rektors Hermanis Vilkens (Vilikinds, Vitekinds)</td>
	</tr>
	<tr>
    <td>ap 1576. </td>
	<td>rektors Georgs Marsovs</td>
	</tr>
	<tr>
    <td>1579.—1589. </td>
	<td>rektors Heinrihs Mellers</td>
	</tr>
	<tr>
    <td>1589.—1596. </td>
	<td>rektors un inspektors Johans Rīvijs</td>
	</tr>
	<tr>
    <td>no 1631. </td>
	<td>ģimnāzijas inspektors Hermanis Samsons</td>
	</tr>
	<tr>
    <td>no 1669. </td>
	<td>rektors Georgs Lauterbahs</td>
	</tr>
	<tr>
    <td>no 1681. </td>
	<td>rektors Mihaels Pinsderfers (Pinsdörffer) </td>
	</tr>
	<tr>
    <td>1755.—1765. </td>
    <td>rektors un inspektors Johans Gothelfs Lindners</td>
	</tr>
	<tr>
    <td>1765.—1780. </td>
	<td>rektors Gotlībs Šlēgels</td>
	</tr>
	<tr>
    <td>1780.—1787. </td>
	<td>rektors Karls Filips Mihaels Snells</td>
	</tr>
	<tr>
	<td>no 1788. </td>
	<td>rektors Kārlis Gotlobs Zontāgs</td>
	</tr>
	<tr>
	<td>līdz 1804. </td>
	<td>rektors Johans Augusts Albanuss</td>
	</tr>
	<tr>
	<div><h1 id="absolventi">Skolas absolventi</h1></div>
	<h2> Rainis </h2>
	<p>Viens no ievērojamākajiem latviešu literātiem, dzejnieks un dramaturgs. Īstajā vārdā Jānis Pliekšāns. Dzimis 1865. gada 11. septembrī Dunavas pagasta Varslavānos, miris 1929. gada 12. septembrī Majoros, Jūrmalā, apbedīts 15. septembrī Rīgā, Rīgas jaunajos kapos, kas vēlāk nosaukti Raiņa vārdā.</p>
	<p><a href="https://enciklopedija.lv/skirklis/55869-Rainis">Uzzini vairāk par Raini ŠEIT</a></p>
<footer>
  <p><a href="http://r1g.edu.lv/v/index/">
  <img src="images\skola.jpg.jpg" alt="saite" style="width:42px;height:42px;border:0;">
</a>
</p>
</footer>
