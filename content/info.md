---
Title: Információk a programról
Description: Köszöntöm az AudioJavaGame súgójának oldalán. Bár a játékprogram használata viszonylag egyszerű, ez az oldal részletesen leírja a használatát, és igyekszik válaszolni az esetleges kérdésekre.
Robots: index, follow
---

## %meta.title%

%meta.description% <!-- replaced by the above Description meta header -->

<h2> Tartalom </h2>
<ul>
	<li> <a href="#step1" > 1. lépés - Zenefájlok betöltése </a> </li>
	<li> <a href="#step2"> 2. lépés - Egyéb beállítások </a> </li>
	<li> <a href="#step3"> 3. lépés - Játék </a> </li>
</ul>

<a name = "step1"> </a>
<h2> 1. lépés </h2>
<p>
A játék egy egyszerû kvízjáték, amely az Ön saját zenéirõl tesz fel kérdéseket.
Az játék kezdetekor kiválasztható a mappa, amelyben az *.mp3 fájlok találhatók.
Alapértelmezetten ez az a mappa, amelyben az alkalmazás található 
(tehát Tallózás helyett az 'AduioJavaGame.jar' áthelyezhetõ a zenéket tartalmazó mappába.)
A zenék beolvasását minden elindításkor a 'Választott mappa figyelése' gombbal lehet megkezdeni.
Ez a folyamat a fájloktól és a mappaszerkezettõl függõen hosszú ideig is eltarthat. 
A folyamat végérõl egy felugró ablak fog tájékoztatni.
</p>

![Zenefileok kiválasztása a programban](%base_url%/img/AudioJavaGame-select-music-folder.png)
<br /><small> A zenefileok mappájának kiválasztása </small>

![Elkészült beolvasás](%base_url%/img/AudioJavaGame-scanned-music.png)
<br /><small> Így néz ki, amikor elkészült a beolvasás.</small>

<a name="step2"> </a>
<h2> 2. lépés </h2>
 <p>
 A játék kezdése elõtt beállíthatja az életeinek számát: vagyis azt, hogy hány helytelen választ
 adhat, mielõtt véget érne a játék. Ezt a fõ ablak tetején lévõ panelen teheti meg.
 A játék indításához - a 1. lépés befejezése után - kattintson a 'Kezdõdjön a játék!'
 feliratú gombra.
 </p>
 
 <a name="step3"> </a>
 <h2> 3. lépés </h2>
 <p> 
 A játék során minden kérdéshez egy-egy zenerészletet fog hallani, a beolvasott zenék közül.
 A feladat, hogy válaszoljon a kérdésre. Ha helyesen felel, 100 ponttal lesz gazdagabb,
 ha helytelenül, egy élettel lesz szegényebb. Ha már nincs több élete, vége a játéknak.
 </p>
