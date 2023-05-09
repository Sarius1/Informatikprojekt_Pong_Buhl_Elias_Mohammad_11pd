# Blog

# 09.01.2022
Heute haben wir uns mit der Projektfindung beschäftigt. Nach dem beenden einer Pandemie war uns unklar wie es weitergehen soll. StarlogoTNG als Programm zum Programmieren ist ja bereits nicht mehr erlaubt. Von nun an sind schwerere, oder besser gesagt forderndere Programme gefordert. Natürlich ist da die Auswahl riesig und wir haben uns zuallererst in die verschiedenen Programme reingelesen. Auch war ein neues Projekt gefragt, weshalb wir uns auch mit der Projektfindung beschäftigt haben.
Projektfindung welches Programm? welchjes Projek


# 16.01.2022
Heute haben wir uns für ein Programm geeinigt, ud zwar Greenfoot. Greenfoot ist ein Java-lastiges Programm, mit welchem man vereinfacht Programmieren kann. Nun stellt sich noch die Frage, welche Art von Programm wir coden wollen. Sehr schnell war uns klar, dass es ein Spiel werden sollte, doch welches Spiel. Als Auswahl standen uns Spiele wie Pong, ein Tischtennisähnliches Spiel, aber auch andere einfache Spiele.

# 14.02.2023
Heute haben wir die Gruppen geändert. Anstatt also der Gruppe aus Arvid und Elias, ist die Gruppe Mohammad und Elias entstanden. Dies hat jedoch das erarbeitete nicht aufgehalten, da beide Gruppen auch vor der neuen Koalition auf dem gleichen Stand waren. So arbeiten beide Gruppen mit Greenfoot. Außerdem haben wir uns für ein entgültiges Projekt entschieden. Wir werden bei Greenfoot Pong programmieren. Pong ist ein guter Einstieg, weil es nicht zu fordernd ist, aber dennoch einige Herausforderungen bereitstellt. Also haben wir mit den Vorbereitungen angefangen. Denn neben dem letztendlichen Projekt sollte man die Sprache gut beherrschen. Also haben wir nach Tutorials zu Greenfoot auf Youtube gesucht.

# 21.02.2023
Heute haben wir die Einführung in Greenfoot mit Tutorials gestartet. Dazu haben wir noch tolle Tutorials, welche von Greenfoot bereitgestellt wurden gefunden. Bei Joy of Code gibt es ca. 33 Tutorials zur Einführung in Greenfoot. Also haben wir direkt gestartet.
 https://www.greenfoot.org/doc/joy-of-code
 Wir haben uns heute mit folgenden Lerneinheiten beschäftigt
* Introduction
  * Bei der Einleitung wurde noch nicht gecodet. es wurde lediglich gezeigt, was man alles so mit Greenfoot machen kann. es wurde auch gezeigt, wie man Greenfoot richtig installiert etc. Dies war für uns relativ irrelevant, da Greenfoot bereits installiert war. Daher konnten wir große Teile des Videos skippen.
* Installing Greenfoot
  * bei dieser Einheit ging es wieder nur um die Installation, weshalb wir die schnell übersprungen haben
* Classes and Objects
  * Bei dieser Einheit wurde die Umgebung erläutert. Es wurde gezeigt wie man Szenarios öffnet und eine Idee in einen Code umwandelt. Aber auch wie man den Code "zerteilt um Übersicht zu schaffen. Dies wurde anhand eines bereits existierenden Szenarios gezeigt, wo man Igel fortbewegen konnte auf dem Bildschirm, welche Äpfel aßen.

# 28.02.2023

Heute haben wir mit dem Bearbeiten der Code of Joy Einheiten fortgefahren.
*  finally some code
   *  Heute ging es endlich mit dem Coden los. Zuerst haben wir ein Szenario erstellt und dieses in verschiedene Klassen unterteilt. ![image](https://user-images.githubusercontent.com/111464150/230055811-d8db0b0d-7aba-4363-80b1-53399abb2b79.png)  Im noch relativ simplen Code haben wir ein Void erstellt, wo eine Schildkröte platziert wurde. Des weiteren haben wir der Schildkröte eine Bewegung zugewiesen wie move(1). Wenn man noch turn(1) hinzufügt bewegt sich die Schildkröte im Kreis. Jedoch muss man die Schildkröten noch manuell hinzufügen und erscheinen nicht automatisch
*  if statements
   *  Um in das Thema der Bedinungen einzuleiten wurde das Problem mit der worldEdge gezeigt. Wenn sich eine Schildkröte nämlich dem Ende der Welt nähert stoppt diese einfach nur. Dies will man ändern, sodass unter der Bedinung, dass die Schildkröte die Weltgrenze berührt ein Ereignis eintritt.![image](https://user-images.githubusercontent.com/111464150/230057899-cf303028-b0dc-450a-b0e2-2ef2c81feacf.png)
So hat man bei if-statements immer einer condition, auf die ein statement immer antwortet, falls diese erfüllt ist. Wir haben programmiert, dass wenn sich eine Schildkröte der worldedge nähert, diese sich um eine bestimmte Gradzahl dreht und so nicht stoppt.
*  adding random behaviour
   *  Bei random behaviour wurde uns gezeigt, wie man ein random Bewegungen im Code einfügt. Diese sind nämlich nicht wirklich random sondern mathematisch ausgerechnet. So kann eine Schildkröte eine 10% Wahrscheinlichkeit haben sich umzudrehen. Dafür braucht man einen neuen Code nämlich 
  <p> (getRandomNumber(...) <...) <p>
 Wenn man einsetzt
<p> (getRandomNumber(100) < 10) <p>
 ist nun eine 10% wahrscheinlichkeit für ein Ereignis angegeben. Dies ist für die meisten Videospiele ganz interessant um sogeannte NPCs oder Bots zu programmieren.
 Da wir heute auch anwesend waren hat Herr Buhl uns eine Teslaspule für das Projekt einer anderen Gruppe gezeigt sowie einen LRC- Schaltkreis.

# 01.03.2023
 
Heute haben wir mit dem Bearbeiten der Code of Joy Einheiten fortgefahren.
*  Lettuce is Good for You! (collision detection)
   * Heute haben wir neben den Schildkröten noch den Salat als Schauspieler hinzugefügt. Dieser Salat hat keine funktion, bis auf die Tatsache, dass die Schildkröte mit ihm interagieren kann. Die Schildkröte kann nämlich, während sie über ihn rüberkrabbelt, ihn essen. Dafür braucht man nur eine if Funktion, welche sagt, dass wenn eine Schildkröte über einen Salat krabbelt sie ih isst und der Salat verschwindet. Des weiteren wurde gezeigt, wie man ein Layout speichert, sodass man nicht immer wieder neu die Schauspieler(Actors rüberziehen muss).
*   Keeping your Code Clean
    * Wie der Titel bereits besagt, wurde gezeigt wie man seinen Code geordnet hält. Dies ist wichtig, da der Quellcode mit der Zeit immer länger wird. Um nicht den Überblick zu verlieren und Fehler zu vermeiden kann man dies auf verschiedene Art und Weise vorbeugen. Man kann bspw.Leere Zeilen einbauen.   
*   Snakes on a Plane!
    * In dieser Lektion haben wir eine neue Klasse, nämlich die Schlangen (snakes) hinzugefügt. Diese sollten die Schildkröte jagen und aufessen. Dazu hat man einfach den Code der Schildkröte genommen, welche ein mehr oder weniger random-Verhalten haben und Salat essen kopiert, und in das der Schlange eingefügt. Da wir jedoch wollen, dass die Schlange die Schildkröte isst, mussten wir noch ändern, dass sie bei Kontakt keinen Salat, sondern Schildkröten isst.
 ![image](https://user-images.githubusercontent.com/111464150/235751228-6b792006-7348-40c4-b683-b13e8e2e0709.png)

# 03.03.2023
*  It's done: Play the Game! (keyboard control) (with teacher commentary)
*  Make it Your Own (changing images)
*  Fun with Sound
   *  Diese Einheit beschäftigt sich, wie der Titel bereits sagt mit dem Einfügen von Sounds. Dies ist auch ziemlich einfach, da man lediglich nach der if-Funktion und der Folge einfach einen Sound aus seinen Files hinzufügen muss. Wir haben dazu einfach den Sound von Code of Joy gedownloaded, um es möglich autenthisch zu halten. letztendlich sollte der Code ungefähr wie folgt aussehen:
 ![image](https://user-images.githubusercontent.com/111464150/235773201-a9a07354-af19-414e-9310-de9e60c4fe02.png)
Dabei wird der Sound als String in der JavaSprache verwendet. So haben wir Sound für die Schildkröten und Schlangen in der kleinen Simulation hinzugefügt.
*  The Structure of a Class
   *  Bei der Lerneinheit DStructure of a class ging es zum einen darum Ordung zwischen den verschiedenen Klassen zu schaffen. Zum anderen ging es aber auch darum, die verschiedenen Klassen roichtig anzuordnen. Dies ist vor allem für größere Projekte mit vvieölen Klassen etc von Bedeutung.
*   A First Look at Variables
    * Bei dieser Einheit ging es zum ertsen mal um Variablen. Dies wurde anhand einen Beispiels spielerisch gezeigt, was diese überhaupt sind. Aufgrund unserer letzten Projekte mit StarlogoTNG war da aber nicht viel neues dabei.
# 06.03.2023
 Heute haben wir mit den verschiedenen Lerneinheiten fortgefahren. Diese waren sogar besonders von Bedeutung für unser Projekt Pong! welches wir im Anschluss der Einheiten coden werden.
* Object Interaction (first encounter)
  * Bei den Objektinteraktionen geht es darum , wie verschiedene Objekte miteinander interagieren können. Dazu verwendet man die erlenten Variablen, sowie if.Strukturen. Dadurch kann man Simulationen und Spiele belebter machen.
*   Adding a Score Counter
    * Diese Einheit war für uns von großer Bedeutung. Dies liegt daran, dass bei Pong! auch ein Scoreboard benötigt wird. Daher konnten wir hier schon viel lernen und später bei unserem Projekt so anwenden. Dies zeigt wieder, dass die verschiedenen Einheiten sehr nützlich sind, da man zum einen viel allgemeines lernt, aber auch viel Spezifisches für unser Projekt.
*   Bouncy Coloured Balls
    * Bei Bouncy coulored Balls ging es darum, Objekten verschiedenen Farben zuzuordnen. Außerdem hat man ein Gebiet festgelegt, welches die Bällee nicht überschreiten können und bei Berührung abprallen und die Farbe ändern   
*   Bouncy Balls with Mouse Input
    * TEXT   
# 09.03.2023
*  Class Methods vs Instance Methods
   *Text
*  Dealing with errors
  * TEXT 
* How to display text
  * TEXT..................................................................................................................................................................................................................................
 # 13.03.2023
* Paddles movement
  * TEXT
 ![image](https://user-images.githubusercontent.com/111464150/235778905-94413617-e939-4233-933f-8e104f129266.png)

# 20.03.2023
* Coden von Pong
  * TEXT 
* Paddle funktion
  * Heute haben wir mit dem Coden von Paddles fortgefahren
# 25.03.2023
* Coden von Pong
  * TEXT 
*  Ball movement
   * TEXT 
 ![image](https://user-images.githubusercontent.com/111464150/235779188-2345c51a-00bd-4d72-a11c-cc8de1db8e1f.png)
![image](https://user-images.githubusercontent.com/111464150/235779257-facdfed3-b9a3-49fe-a976-8d858e4658ac.png)

# 30.03.2023
* Coden von Pong
  * TEXT 
* Score
  * TEXT 
# 02.04.2023
* Score
  * TEXT 
 ......................................................................................................................................................................................................................................
# 05.04.2023
Heute hatten wir den Seminartag, hatten also den ganzen Tag Zeit, an unserem Projekt zu arbeiten. Da wir jedoch schon weit fortgeschritten waren, hatten wir nicht zu viel zutun. Eine Herausforderung war jedoch das Scoreboard. So meinte bereits der ursprüngliche Coder von Pong!, dass das Scoreboard das komplizierteste am ganzen Projekt war. Wir konnten ihm da nur zustimmen, da wir dafür auch Herr Buhls Hilfe in Anspruch nehmen mussten.
Dies hatte jedoch irgenwann geklappt, wo wir nur noch mit Herr Buhl im Computerraum waren und alle bereits nachhause gegangen sind. jedoch waren wir mit dem Spiel an sich fertig. Anbei ein Bild, wie es am Ende aussieht.
 ![image](https://user-images.githubusercontent.com/111464150/235778562-e7b31713-2846-4144-bb86-a8fb1d68f951.png)
Außerdem haben wir parallel bereits angefangen die Projektseite auszuschreiben. Ein grobes Konzept hatten wir zwar, mussten dieses jedoch noch ausschreiben.
 
 # 25.04.2023
Nach langen Osterferien war dies unsere erste Stunde wieder mit dem Projekt. Leider ist die Präsenzstunde ausgefallen, weshalb wir uns auf digitaler Ebene getroffen haben und den Blog ergänzt haben. Dabei haben wir an der Formatierung gearbeitet, also der Ästhetik, aber auch am Inhalt. Viele Blogeinträge erscheinen uns im nachhinein etwas zu kurz und unausführlich, weshlalb wir uns die Zeit nehmen, an diesen in den nächsten Tagen noch zu arbeiten. Dabei ist vor Alem das Erscheinungsbild wichtig, da der Inhalt in großen Teilen bereits im Blog steht, nur noch ausgeschrieben werden muss. Des weiteren haben wir auch an der Projektseite weitergearbeitet, welche neben dem Projekt auch eine große Rolle für die Benotung spielt, weshalb auch da viel Arbeit reingesteckt werden muss.
# 02.05.2023
Heute haben wir weiter am Ausschreiben des Blogs und der Projektseite fortgefahren. Dies hat wieder eine einige Zeit in Anspruch genommen
