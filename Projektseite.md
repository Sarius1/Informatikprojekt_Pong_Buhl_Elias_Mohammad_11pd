# Projektseite




# Inhalt

<p><a href="#kapitell">1. Einleitung</a></p>
<p><a href="#kapitel2">2. Greenfoot</a></p>
<p><a href="#kapitel3">3. Pong</a></p>
<p><a href="#kapitel4">4. Projektentwicklung</a></p>
<p><a href="#kapitel5">5. Vorstellung des Projekts</a></p>
<p><a href="#kapitel6">6. Der Code</a></p>
<p><a href="#kapitel7">7. Kritik</a></p>
<p><a href="#kapitel8">8. Fazit/Aussicht für die Zukunft</a></p>
<p><a href="#kapitel9">9. Quellen</a></p>
<p><a href="#kapitell0">10. Eigenständigkeitserklärung</a></p>





<h2 id="kapitell">1. Einleitung</h2>

Videospiele: FPS, Killstreaks Ping. Um heutzutage zu spielen braucht man einen Leistungsstarken PC mit sehr teuren Komponenten. Viele können sich dies nicht Leisten und sehen nicht den Sinn bei einer Investition von 1000 € bis 2000€, nur um in deren Freizeit beim Spielen ein wenig zu entspannen. Alte Spiele wie Flappy Bird, Tetris und PAC-Man sind Spiele die jeder kennt und liebt. Sie sind aus den 80ern und geben jedem Gamer einen Nostalgieschub. Diese spiele haben schlechte Graphiken, weshalb diese Spiel von jedem gespielt werden können. Warum also nicht ein Spiel programmieren, welchen den breiten Massen zur verfügung steht, es also viele Abnehmer gibt und zusätzlich noch einfach.



<h2 id="kapitel2">2. Greenfoot</h2>
Greenfoot ist ein Coding Programm der objektorientierten Programmierung. Als objektorientierte Programmierung ist es zwischen dem Blockcoden wie bei StarlogoTNG und normalen Sprachen wie C++ und normalem Java. Es ist Javalastig, also eine vereinfachte Version von Java. Des weiteren kann man in einer Umgebung direkt sehen, was man gecodet hat: Daher objektorientiertes Coden.
<p> Es ist ein Programm welches von der University of Kent produziert wurde und von Giganten wie Google und Oracle gesponsort wurde. Es wurde von einem größren Team produziert, die legalen Besitzer sind aber Michael Kölling und Poul Henriksen. <p>
Es ist ein Gratisprogramm, welches auf macOS, Windows, Linux, Solaris und JVM funktioniert. Es ist für Schüler und Studenten konzipiert, um Ihnen das Coden schnell näherzubringen und gute fortschritte in kurzer Zeit zu machen.
   

   
<h2 id="kapitel3">3. Pong</h2>

Das Spiel Pong wurde bereits 1972 von Atari Inc veröffentlicht.
   <details>
  <summary>Erster Pong-Automat   </summary>
  

  ![image](https://user-images.githubusercontent.com/111464150/230014140-97432592-a5e8-46b4-992d-f544ef88e560.png)
</details>
   
 Atari ist ein US-Amerikanischer Spielehersteller aus den 80er-Jahren und hat neben Pong auch viele andere Spiele sowie Konsolen hergestellt. Pong gilt als einer der Urväter der Videospiele, da es weltbekannt und hat die Videospielindustrie zu der Zeit revolutioniert. Es hat mit seiner "Simplicity" Millionen Spieler in Arcades überzeugt.
   
 <details>
  <summary>Atari-Logo   </summary>
  

![image](https://user-images.githubusercontent.com/111464150/230013009-2e52e084-95e3-4b6a-9263-ada063f1579a.png)
</details>
   
Pong ähnelt stark dem Sport Tischtennis oder Tennis. Es gibt zwei Spieler die jeweils ein Paddle bedienen. In der Mitte des Spielfeldes erscheint ein Ball und fliegt auf eine der beiden Seiten zu. Der Spieler muss verhindern, dass der Ball an ihm vorbeifliegt, sondern muss ihn blocken. Falls er dies nicht verhindert, bekommt der andere Spieler einen Punkt.



<h2 id="kapitel4">4. Projektentwicklung</h2>
Nach dem Programmieren in anderen Gruppenkonstallationen war uns schnell klar, dass wir nun zügig mit der Entwicklung eines neuen Projektes beginnen wollten. Schnell war uns klar, dass wir ein Spiel entwickeln wollten, etwas was jeder kennt und von vielen Menschen gespielt wird(vielleicht sogar Suchtpotenzial hat?;)). Nach einiger Zeit sind wir dann auf Pong! gestoßen. Es war das perfekte Spiel zum Coden, da es nicht zu schwer war und man anhand des Spiels gut die Mechaniken mit einer neuen Sprache erlernen kann. Dies war uns sehr wichtig, da wir im letzten Jahr mit StarlogoTNG, eine Blogsprache gearbeitet haben. Dieses Halbjahr wollten wir jedoch mit Greenfoot, einer fortgefahreneren Sprache etwas Entwickeln. 

<h2 id="kapitel5">5. Vorstellung des Projekts</h2>
Pong! ist ein Two-Player-Spiel, welches auf dem realen Spiel Tischtennis 
https://isurfstormarn.de/iserv/file/-/Groups/Klasse%2011p/Profil_Seminar_Informatik/Informatikprojekt
Link zum Video
<h2 id="kapitel6">6. Der Code</h2>
Ball
* movement
 
Paddle
* Als nächstes ist der Code für das Paddle dran. Der erste Teil ist hier eingeblendet

![image](https://user-images.githubusercontent.com/111464150/236014743-79a79b9b-0feb-45cc-9a81-0f29080c02db.png)


Im ersten Teil werden einfache Größen wie höhe breite Farbe etc. bestimmt. Außerdem wird bereits festgelegt, wie man die Paddles bewegen soll, nämlich mit den up und down Tasten. Beim zweiten Teil geht es vor Allem darum, was die Folge vom drücken der Tasten ist.


![image](https://user-images.githubusercontent.com/111464150/236015433-020fdeb2-630c-4f37-b4b4-bc50aeae9a8f.png)


Sobald man beispielsweise die Down-Taste drückt, verändert das Paddle seinen Y-Wert um zwei. Außerdem geben wir noch am Ende an, dass das Paddle nicht die Welt verlassen darf. Dadurch setzten wir ein Limit an Y-Werten, welches das Paddle nicht überschreiten darf. Dadurch gibt es keine Ungleichheiten zum echten Spiel und es fühlt sich wie das echte Spiel an.


Score
Der Score war mit das schwierigste am Coden. Dies liegt nämlich daran, dass der Score auf viel Variablen und Funktionen der anderen Classes zugreifen muss um den Score anzuzeigen
<h2 id="kapitel7">7. Kritik</h2>
Der Sprung von StarlogoTNG zu Greenfoot war ein gewaltiger, aber dennoch ein Fortschritt. AUfgrund einer ganz anderen Umgebung haben wir erstmal Einfindungszeit in das Programm gebraucht. Diese haben wir sinnvoll durch die Lernaktivitäten genutzt, welche von Joy of Code bereitgestellt wurden. Dadurch konnten wir die Umgebung besser kennenlernen und gleichzeitig viele bereits bekannte Code-Blocks kennenlernen. So haben wir booleansche Variablen, if-Bedinungen und vieles andere Wiederholt. Dies hätte man vermeiden können, indem man wiederholende Einheiten, die man bereits bei StarlogoTNG behandelt hat überspringt. Andererseits ist die Umgebung eine andere, weshalb sich die bereits bekannten Coding-mechanisms ändern und man sich diesen änderungen bewusst sein sollte. Daher kann man bei diesem Punkt Zwiegespalten sein. Ein anderer Punkt ist, dass Greenfoot immer noch kein vollständiges Programm ist und die Funktionen daher eingeschränkt sind. Des weiteren ist das Pong-Spiel auch nicht ganz unsere Idee, da das Spiel bereist sein 50 Jahre Jubiläum gefeiert hat. Ein weiterer Kritikpunkt ist aber auch die Einfachkeit des Spiels. Viele Spiele aus der heutigen Zeit haben anschauliche, fast reale Graphiken. Spieler können mit fast allem in der Welt interagieren und das Spiel wird zusätzlich durch Power-Ups,Level und andere Sachen interessant gemacht. Auch kann man es als negativ Werten, dass Pong in der Zweidimensionalitt gefangen ist. Beim Release des Spiels war es noch was ganz normales, doch heute überwiegen dreidimensionale Spiele einfach den Markt. Allerdings muss man auch sagen, dass man Pong! nicht einfach in ein 3-D Spiel umändern kann, da es einfach von den Mechaniken her auf 2-D ausgelegt ist und es keinen Sinn macht diese Krampfhaft auf 3-D zu ändern. Es würde auch den eigentlichen Sinn des Spiels, und zwar des einfachen Zeitvertreibs zu Zweit entfliehen und sich in eine andere Richtung bewegen.

<h2 id="kapitel8">8. Fazit/Aussicht für die Zukunft</h2>
Neben Tetris ist Pong ein Spiel, welches die Gaming-Industrie Revolutioniert hat. Mit seiner "Simplicity" hat es mehrere 100 Millionen User überzeugt und viele spielen es bis heute. Obwohl es nicht schwer war zu coden, haben wir persönlich viel mitnehmen können. Eines der schwierigsten Coding-Elemente war nämlich das Score-Board. Es war dennoch der perfekte Einstieg für das coden mit Java. Wir konnten viele verschiedene Techniken lernen und durch Selbsterkenntnis auch viel persönlich mitnehmen können. Dank der vielen Lerneinheiten vorab, konnten wir das Selbstständige Lernen "lernen". Dies bedeutet, dass wir uns viel selbstständig erarbeitet haben und bei Hilfe Quellen aus dem Internet zur rate gezogen haben und nur wenn wir gar nicht weiterwussten Hilfe beim Lehrer suchten. Dies ist eine Fähigkeit, welche im Studium ( was ja viele nach dem Abitur anstreben) sehr essentiell ist, vielen aber nicht aufgrund der Unterrichtsgestaltung mitgegeben werden kann. Diese trifft es dann anz plötzlich, wenn sie ein großes Maß an Freiheiten besitzen, mit denen sie nicht umgehen können. Aufgrund der Gestaltung des Unterrichts, konnten wir diesen Skill jedoch schon aus der Schule mitnehmen.

<h2 id="kapitel9">9. Quellen</h2>
https://de.wikipedia.org/wiki/Pong
https://www.greenfoot.org/about
https://www.greenfoot.org/doc/joy-of-code
https://praxistipps.chip.de/markdown-auf-github-alle-befehle_48373
https://en.wikipedia.org/wiki/Greenfoot
https://www.volker-berg.de/EP/greenfoot.html

<h2 id="kapitell0">10. Eigenständigkeitserklärung</h2>

Hiermit erkläre ich, dass ich die vorliegende Arbeit selbstständig verfasst und keine anderen als die angegebenen Quellen und Hilfsmittel benutzt habe. Alle sinngemäß und wörtlich übernommenen Textstellen aus fremden Quellen wurden kenntlich gemacht.

Elias Michno und Mohammad Rezaei

Unsere Projektseite umfasst ............ Wörter
