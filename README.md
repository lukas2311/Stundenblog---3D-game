# Stundenprotokoll - Informatik Projekt 2. Halbjahr
<b>Torben Starken, Lukas Mackel - Klasse 12e</b>

<h1 id="vorwort">Vorwort</h1>
In diesem Repository haben wir alle Inhalte der Unterrichtsstunden und privaten Treffen im Rahmen unseres zweiten Informatikprojekts notiert. Das Ergebnis unserer Arbeit ist ein 3D-Game, in welchem das Ziel ist, von einer verlassenen Insel zu entkommen, indem man inGame einige Aufgaben bzw. Quests löst.
<br/><br/>
Im Vergleich zu letztem Halbjahr wollten wir dieses Mal, anstatt des Physical Computing, vor allem einen gestalterischen Anspruch umsetzten, weshalb wir neben der umfangreichen Programmierung auch viel und gerne Zeit in die grafische Gestaltung unseres Projektes gesteckt haben. Wie wir das ganze umgesetzt haben und wie das angegangen wird, lässt sich außerdem auf einer Projektseite nachlesen: <a href="https://github.com/lukas2311/3D-Game-Docu/blob/master/README.md">Link</a>
<br/><br/>
<img src="https://user-images.githubusercontent.com/42578917/51550957-c19bea00-1e6d-11e9-9baf-56e92610e7fe.png">

<h1 id="hinweise">Hinweise</h1>

1. Dieses Projekt entspricht für einen Anfänger ungefähr einem Zeitaufwand von 87:45 Stunden. Je nach Anspruch an Komplexität und Funktionalität weicht dies natürlich stark oder weniger stark ab.

2. Als Anfänger ist es oftmals nötig, sich, bevor man mit irgendwas startet, mit der Funktionsweise der genutzten Funktionen auseinanderzusetzen, um bei Bugs auch erkennen zu können, wo der Fehler liegt, und was zu verbessern ist. Letztendlich spart dies einiges an Zeit bei der Entwicklung.

3. Während des Entwicklungsprozesses ist es zudem sinnvoll, das Spiel immer wieder zu exportieren und einen In-Action-Test zu machen. Wir haben dies währenddessen mehrfach gemacht, da man hier im Vergleich zu Tests, die man innerhalb der Engine macht, weitere Glitches und Bugs erkennen kann. Dabei sollte darauf geachtet werden, dass man mit dem Charakter einmal sämtliche Stellen der Map abläuft und quasi versucht einen Bug/Glitch zu erzeugen, indem man zum Beispiel an Stellen spring oder sprintet, an denen man dies normalerweise nicht tut. Nur solche Stress-Tests zeigen, wo Fehler im Spiel liegen und wo man noch nachzubessern hat. 

<h1>Inhaltsverzeichnis</h1>
<ul>
  <li><a href="#vorwort">Vorwort</a></li>
  <li><a href="#hinweise">Hinweise</a></li>
  <li><a href="#">Arbeitsaufwand</a></li>
  <details>
  <summary>Arbeitstage (aufklappen)</summary>
    <li><a href="#einssiebeneinszwei">17.12.18 - Unterricht<a></li>
    <li><a href="#einsachteinszwei">18.12.18 - Unterricht<a></li>
    <li><a href="#einsachteinszweiz">18.12.18 - Zuhause<a></li>
    <li><a href="#einsneuneinszwei">19.12.18 - Zuhause<a></li>
    <li><a href="#zweinulleinszwei">20.12.18 - Zuhause<a></li>
    <li><a href="#zweieinseinszwei">21.12.18 - Zuhause<a></li>
    <li><a href="#zweizweieinszwei">22.12.18 - Zuhause<a></li>
    <li><a href="#zweiachteinszwei">28.12.18 - Zuhause<a></li>
    <li><a href="#nullsiebennulleins">07.01.19 - Zuhause<a></li>
    <li><a href="#nullachtnulleinsz">08.01.19 - Zuhause<a></li>
    <li><a href="#nullachtnulleins">08.01.19 - Unterricht<a></li>
    <li><a href="#nullneunnulleins">09.01.19 - Zuhause<a></li>
    <li><a href="#einsviernulleinsz">14.01.19 - Zuhause<a></li>
    <li><a href="#einsfuenfnulleinsz">15.01.19 - Zuhause<a></li>
    <li><a href="#einsfuenfnulleins">15.01.19 - Unterricht<a></li>
    <li><a href="#zweieinsnulleins">21.01.19 - Unterricht<a></li>
    <li><a href="#zweizweinulleins">22.01.19 - Unterricht<a></li>
    <li><a href="#zweidreinulleins">23.01.19 - Zuhause<a></li>
    <li><a href="#zweineunnulleins">29.01.19 - Unterricht<a></li>
    <li><a href="#nullviernullzwei">04.02.19 - Unterricht<a></li>
    <li><a href="#einszweinullzwei">12.02.19 - Unterricht</a></li>
    <li><a href="#einssechsnullzwei">16.02.19 - Zuhause</a></li>
    <li><a href="#einsneunnullzwei">19.02.19 - Unterricht</a></li>
    <li><a href="#zweizweinullzwei">22.02.19 - Zuhause</a></li>
    <li><a href="#nulleinsnulldrei">01.03.19 - Zuhause</a></li>
    <li><a href="#nullviernulldrei">04.03.19 - Unterricht</a></li>
    <li><a href="#nullviernulldreiz">04.03.19 - Zuhause</a></li>
    <li><a href="#nullfünfnulldrei">05.03.19 - Unterricht</a></li>
    <li><a href="#nullfünfnulldreiz">05.03.19 - Zuhause</a></li>
    <li><a href="#einsachtnulldrei">18.03.19 - Unterricht</a></li> 
    <li><a href="#zweizweinulldrei">22.03.19 - Zuhause</a></li> 
    <li><a href="#zweiviernulldrei">24.03.19 - Zuhause</a></li>
    <li><a href="#zweifünfnulldrei">25.03.19 - Unterricht</a></li>
    <li><a href="#zweisechsnulldrei">26.03.19 - Unterricht</a></li>
  </details>
</ul>


<h3 id="einssiebeneinszwei">17.12.18 - Unterricht</h3>
<h4>Stundenaufwand: 0:45</h4>
  
Heute haben wir uns mit der Ideenfindung beschäftigt. Nachdem wir das letzte Mal ein hardwarelastiges Projekt gemacht haben, wollten wir diesmal eher ein Projekt mit Fokus auf Software erstellen. Dabei kamen (unseren Programmierkenntnissen entsprechend) nur eine Smartphone App, ein Computerprogramm oder ein Videospiel in Frage. Daher informierten wir uns zunächst einmal, was es für Möglichkeiten gab, Programme oder Spiele umzusetzten, welche Engines bzw. Programme dafür bereitstehen, wie weit wir dabei mit unserem aktuellen Wissen kämen und wie möglicherweise das Ergebnis aussehen könnte. 

<h3 id="einsachteinszwei">18.12.18 - Unterricht</h3>
<h4>Stundenaufwand: 1:30</h4>  

Wo wir bereits letzte Stunde dafür aufgebracht hatten, uns zu informieren, was für Möglichkeiten es gibt, wollten wir dieses Mal bereits eine Idee entwickeln, um im Vergleich zu unserem letzten Informatikprojekt sehr früh viel Fortschritt zu machen.

Nach einiger Zeit einigten wir uns dann darauf, keine App, sondern ein Computerprogramm, genauer gesagt ein Computerspiel, zu programmieren. Dazu entschieden wir uns, da wir auch einen gestalterischen, also einen grafischen, Anspruch hatten. Da wir schon Erfahrung mit der Unity Engine hatten, beschlossen wir, diese für unser Projekt zu nutzen. Zudem ist sie deutlich benutzerfreundlicher als z.B. die Unreal Engine und hat ebenfalls eine deutlich größere Community mit einer größeren Anzahl an Lernvideos.
  
<h3 id="einsachteinszweiz">18.12.18 - Zuhause</h3>
<h4>Stundenaufwand: 2:30</h4>

Nun haben wir begonnen uns (erneut) in Unity und die neuesten Updates einzulesen und im Zweifel vorhandenes Wissen aufgefrischt. Zudem haben wir mit der Installation der Unity Engine, sowie einigen Assets begonnen und das Programm eingerichtet. Da die Engine ziemlich groß ist dauerte es entsprechend eine Weile bis das ganze installiert war. 
  
Gleichzeitig haben wir uns darauf geeinigt, wie wir das Projekt umsetzen wollen. Zum einen hatten wir den Anspruch, sämtliche Modelle und Objekte selber zu modellieren, zum anderen einen gewissen grafischen Standart zu erfüllen. Um das zu erreichen, recherchierten wir nach einen angemessenen Stil für unser Projekt und sind unter anderem auf folgende zwei Beispiele getroffen:
  
<p align="center"><img width="600px" src="https://user-images.githubusercontent.com/42578917/51188668-b29dc080-18de-11e9-9426-00ceb5bcf1d1.jpg"></p>

Da uns der Low-Poly-Cartoon-Stil zusagte, wollten wir diesen auch in unserem Projekt umsetzen. Als Modellierungssoftware wollten wir dabei Blender verwenden. Blender vor allem deshalb, da es eine Freeware ist und es daher sehr weit verbreitet ist und es große Mengen an Informationen und Tutorials gibt.
  
<h3 id="einsneuneinszwei">19.12.18 - Zuhause</h3>
<h4>Stundenaufwand: 2:00</h4>
  
Heute haben wir damit begonnen ein kleines Terrain in Unity zu modellieren und überlegt, wie wir einen eigenen Charakter für die Spielwelt umsetzen können. 

Da wir große Fans der Creative Cloud von Adobe und überzeugt von der Qualität und Funktionalität der enthaltenen Programme sind, wollten wir das sich noch in der Beta befindende Tool Adobe Fuse verwenden, mit dem man relativ anspruchsvolle Charaktermodelle und dazugehörige Animationen erstellen konnte. Dabei lassen sich sowohl Körperform und Kleidung, als auch detailgetreu der Gesichtsausdruck, sowie Haarfarben, Augenfarbe usw. den persönlichen Wünschen anpassen. Diese weite Reihe an Funktionen nutzten wir, um zunächst einen Testcharakter zu erstellen. Diesen konnte man dort auch als 3D-Model, also als .fbx Datei, exportieren, was wir direkt testweise machten und testeten, wie sich das entstandene Model in Unity verhält.
 
<h3 id="zweinulleinszwei">20.12.18 - Zuhause</h3>
<h4>Stundenaufwand: 3:30</h4>

Nach einigen Veränderungen haben wir nun endlich den Charakter fertiggestellt. Als nächsten Schritt haben wir diesen dann in Mixamo mit verschiedenen Animationen versehen, eine Vorwärts-, eine Rückwärts- und 2 Seitwärts-Animationen. Diese lassen sich dort direkt auf den Charakter anwenden und testen. Dieser Schritt selber bedurfte nicht viel Zeit und so haben wir den Charakter schnell aus Mixamo exportieren und in Unity importieren können.

Parallel dazu haben wir in Unity einen PlayerController erstellt. Das ist das C#-Programm, das für die Bewegung des Charakters in alle Richtungen verantwortlich ist. Besonders wichtig war hierbei, dass auch eine Sprint-Funktion eingebaut wird, die allerdings nur mit dem Drücken der Shift-Taste UND der W-Taste aktiviert wird. Die nächsten Zeit vebrachten wir daher damit, Sprinten nur beim Vorwärtslaufen möglich zu machen. Um den ganzen Controller umzusetzten, mussten wir uns daher nochmal genauer in die Unity-Engine einlesen, und rausfinden, wie dort die "Verschiebung", also Bewegung von Objekten funktioniert und was man tun muss, um dies zu erreichen.

<h3 id="zweieinseinszwei">21.12.18 - Zuhause</h3>
<h4>Stundenaufwand: 2:45</h4>

Heute haben wir uns dann genauer damit beschäftigt, wie wir die zuvor erstellten Animationen auch in Unity anwenden können. Dann ging es daran, die Animationen an bestimmte Aktionen zu koppeln: Die Lauf-Animation an das Drücken der W-Taste oder die Sprint-Animation an das Drücken der W- und der Shift-Taste. 

Um das zu bewerkstelligen nutzten wir den Unity Animator, der eine bedingte Animation ermöglicht: Wir haben also jeweils ein Script geschrieben, in welchem verschiedene Tastaturaktionen abgefragt werden. An dieses Script lässt sich dann im Unity Animator eine Aktion, in diesem Fall das Abspielen der Vorwärts-Animation, koppeln. Nachdem wir dort eine Weile rumprobiert haben, waren wir mit dem Ergebnis zufrieden. Dann haben wir das ganze noch einmal für alle anderen Bewegungen gemacht und die Scripte abgespeichert.

Einer der Vorteile des Unity-Animator ist der Übergang zwischen den Animationen. Diese erstellt er automatisch, was einen weichen Übergang zwischen den einzelnen Animationen ermöglicht. 
  
<h3 id="zweizweieinszwei">22.12.18 - Zuhause</h3>
<h4>Stundenaufwand: 1:00</h4>

Da wir den Charakter mit einem Capsule-Collider ausgestattet haben, hatte dieser in einer dreidimensionalen Welt auch die Eigenschaften einer Kapsel: Er rollte also Berge zum Teil einfach rückwärts runter! Um dieses Problem zu lösen, haben wir die Rotation-Funktion des Charakters deaktiviert.

Zudem haben wir damit begonnen, die ersten Schritte unseres Projektes in unsere Projektseite zu übernehmen. Da bedeutet, wir haben ein Github-Repository erstellt und mit  einer Readme.txt ausgestattet. Zudem haben wir unser Vorgehen in Adobe Fuse, in Mixamo und die ersten Schritte im Unity-Animator mit aufgenommen. Schon jetzt haben wir gemerkt, dass das Projekt vermutlich ziemlich umfangreich wird und wollten daher bereits jetzt jeden Schritt, den wir in unserem Unity-Projekt machten, sofort ausgiebig in der Projektseite dokumentieren.

<h3 id="zweiachteinszwei">28.12.18 - Zuhause</h3>
<h4>Stundenaufwand: 4:00</h4>

Heute haben wir mit der näheren Ausführung unseres Designentwurfes beschäftigt. Dafür haben wir das 3D-Modellierungs-Tool Blender genutzt und zunächst darin einige Versuche getätigt, um uns mit dessen Funktionsweise zu beschäftigen. Zudem haben wir mit einzelnen Objekten, wie einem Stein, erste Modellierungsversuche für unser Projekt erstellt. 

Schwierig war hierbei, dass Blender sehr stark von der Nutzung von Shortcuts abhängt. Als Anfänger ist es daher schwierig, sich mit Online-Tutorials zu behelfen, da viele der Ersteller davon nahezu ausnahmslos auf Shortcuts zurückgreifen. Daher ist es sehr schwer diesen als Anfänger zu folgen. Für den Anfang war es also unumgänglich, sich eine Liste mit allen verfügbaren Shortcuts anzulegen und diese zu lernen.

<h3 id="nullsiebennulleins">07.01.19 - Zuhause</h3>
<h4>Stundenaufwand: 2:00</h4>

Nachdem wir die Shortcuts nun halbwegs gelernt hatten, begannen wir richtigen Fortschritt in Blender zu tätigen. Also haben wir die bestehenden Modelle verworfen und damit begonnen einen Stein zu modellieren. 

Desweiteren haben wir heute eine Tanne modelliert. Diese sollen später auf dem Terrain in Unity platziert werden und dem grafischen Bild genügen. Schwierig daran war vor allem, die Bäume entsprechend unserer Design-Vorstellung zu modellieren. Dafür müssten sie sowohl einen Comic Stil haben, als auch detailliert genug sein, um noch weiterhin in die Welt zu passen. Daher benötigte es ein wenig Trial and Error bis wir die Objekte so modelliert hatten, dass sie uns gefielen.

<h3 id="nullachtnulleinsz">08.01.19 - Zuhause</h3>
<h4>Stundenaufwand: 2:00</h4>

Heute haben wir weiter an einem zum Stil passenden Baum gearbeitet. Die Tanne hat weder zur Inselart noch zum Stil gepasst weshalb wir diese verworfen haben. Denn zeitgleich beschlossen wir, wie unsere Welt grob aussehen sollte. Dafür benötigten wir dann aber eher Laubbäume statt Tannen, weshalb wir zunächst einen Prototypen eines passenden Baumes entwarfen. Der neue Baum ist detailreicher und passt farblich besser zur Insel. Diesen haben wir erstmals in Unity eingefügt. Mit ein bisschen Drehen und Wenden, sowie Größenanpassungen, gefiehl uns das schon ganz gut und wir beließen es dabei.

Zudem haben wir einige Korrekturen an den Bewegungsabläufen im Script gemacht und eine abschließende Version des Bewegungsscriptes geschreiben. Dabei wurde das Script um eine Rotationsfunktion ergänzt, die wir allerdings später wieder verwarfen, da wir eine einfachere Lösung fanden. Zudem haben wir angefangen uns über die Befehle und Funktionalität einer Kameraführung zu informieren.

<h3 id="nullachtnulleins">08.01.19 - Unterricht</h3>
<h4>Stundenaufwand: 1:30</h4>

Heute haben wir einen ersten Spieltest betrieben. Dabei haben wir festgestellt, dass wir weiter an der Kameraführung arbeiten müssen, da es noch recht dürftig wirkte und sehr komisch war, damit im Spiel umzugehen. Außerdem haben wir das Terrain weiter bearbeitet, um etwas mehr Abwechslung in die Insel zu bekommen. Die Terrain-Bearbeitungs-Funktion in Unity war dabei sehr hilfreich, da es damit sehr einfach ist, Farbe und Kontur in das Terrain zu bekommen. Desweiteren haben wir über weitere Details wie Büsche und Steine gesprochen, mit welcher wir die Umgebung ausstatten wollten, und erste grobe Schnittzeichnungen gemacht.

<h3 id="nullneunnulleins">09.01.19 - Zuhause</h3>
<h4>Stundenaufwand: 3:00</h4>

An diesem Nachmittag haben wir mithilfe des fertig modellierten Baumes einen Wald gestaltet und weiter an der Insel geformt, sodass diese langsam etwas natürlicher wirkte. Dabei merkten wir erst, wie schwierig es ist, eine halbwegs realistische Umgebung zu modellieren, ohne dafür dutzende Baummodelle erstellen zu müssen. Daher hat bereits dies heute einige Zeit benötigt.

Zudem haben wir neue Texturen für Gras und Sand rausgesucht und die Alten ersetzt. Der Trick dabei war, ein Gras-Modell in Blender zu erstellen, es zweidimensional abzufotografieren, dies als PNG zu exportieren, in Photoshop die Konturen auszuschneiden und dann in Unity zu importieren. Um hier ein wenig Arbeitsspeicher zu sparen, haben wir das Gras nämlich nicht einfach als Modell auf der Insel platziert, da dies ewig dauern würde und zudem beim Spieler enorm viel Rechenleistung benötigen würde, sondern auf eine Funktion der Unity-Terrain-Gestaltung zurückgegriffen. In der importiert man ein PNG, welches dann quasi als bewegliches Bild in der Welt eingebunden werden kann. 

Auch für Wasser haben wir eine neue Textur herausgesucht und das Wasserasset damit geupdatet. Zudem haben wir unsere Map mit einer unsichtbaren Wand begrenzt, sodass man nicht mehr tief in den Ozean laufen kann und irgendwann vom Rand der Welt herunterfällt. Dabei musste die Wand zwar unsichtbar sein, aber eben noch ein Hindernis für den Spieler darstellen. 

<h3 id="einsviernulleinsz">14.01.19 - Zuhause</h3>
<h4>Stundenaufwand: 8:00</h4>

Heute haben wir uns weiter um die Gestaltung der Insel gekümmert. Angefangen mit Büschen, über tote und umgefallene Bäume, bis hin zu Steinen und Felsen. Sie sollte aussehen, wie eine verlassene und naturbelassene Insel.

Außerdem haben wir eine Holztreppe modelliert, damit man vom Strand aus auf den oberen Teil der Insel gelangen kann. Desweiteren haben wir an der Inselform weiter gefeilt und sie ästetischer gestaltet.

Parallel dazu haben wir eine rudimentäre Kameraführung implementiert und eine Funktion geschrieben, die prüft, ob sich der Charakter auf dem Boden befindet. Dies war allerdings nicht ganz so einfach wie gedacht: Durch die unterschiedliche Höhe des Bodens, hat das Script nicht sonderlich gut funktioniert, denn obwohl man sich als Spieler nicht mehr auf dem Boden befand, wurde dennoch angezeigt, dass man sich auf dem Boden befindet. Dies stellte ein Problem dar, weswegen wir noch einmal am Script feilten und eine andere Herangehensweise nutzen, in der wir eine Collision mit dem Boden prüften, und anhand dessen ausgaben, ob der Spieler sich auf dem Boden befand. Da allerdings nicht nur das Terrain, sondern auch alle Steine, Bäume, Brücken und Pflanzen zum Boden gehörten, war auch dies nicht sonderlich erfolgreich, weshalb wir auf den ersten Entwurf zurückgriffen.

<h3 id="einsfuenfnulleinsz">15.01.19 - Zuhause</h3>
<h4>Stundenaufwand: 3:00</h4>

Die am vorherigen Tag modellierten Gegenstände haben wir heute auf der Insel platziert und einen Weg von der Treppe zum geplanten Haus gezogen. Nun sieht die Insel schon deutlich lebhafter aus. Dazu haben wir die gesamte Insel mit Steinen umschlossen, um sie realistischer zu gestalten. 

Zudem haben wir uns noch einmal an das Script vom Vortag gemacht. Nachdem wir einige Korrekturen vornahmen, war das Ergebnis halbwegs erfolgreich, sodass wir es nutzen konnten. Daher implementierten wir es und nahmen einige Tests vor. Zudem machten wir einen weiteren Export, um in der Schule einen weiteren Spieltest zu machen.

<h3 id="einsfuenfnulleins">15.01.19 - Unterricht</h3>
<h4>Stundenaufwand: 01:30</h4>

An diesem Tag haben wir einen weiteren Test mit dem neuen Game-Export gemacht. Wir haben festgestellt, dass die Kameraführung weiterhin ein Problem darstellt. Die Kamera folgt zum jetzigen Zeitpunkt nicht der Drehung des Charakters und ist schwer mit der Maus zu steuern, da unter anderem die Axenbewegung umgekehrt ist. Daher haben wir an einer Lösung des Kameraproblems gearbeitet:

Die Kamera stellte im ganzen Projekt eine Herausforderung dar. Denn sie dreht sich nicht einfach mit dem Charakter mit, sondern sie hat eine besondere Bewegung, die man Kamera Orbit nennt. Die Lösung dafür war zumindest auf der X-Y-Achse im Koordinatensystem relativ einfach. Dafür haben wir einfach die Kamera an den Charakter angeheftet, und ein kleines Programm geschrieben, um den Charakter selbst mit der Mausbewegung zu drehen. In der Z-Richtung war das ganze nicht so einfach, weshalb wir dieses Problem erstmal zurückstellten.

<h3 id="zweieinsnulleins">21.01.19 - Unterricht</h3>
<h4>Stundenaufwand: 0:45</h4>

In der heutigen Unterrichtstunde haben wir das Stundenprotokoll weiter ausformuliert, unsere weitere Vorgehensweise und vor allem nächste Schritte für unser Projekt geplant. Wie bereits erwähnt, braucht das Protokoll und die Dokumentation entsprechend Zeit, weshalb wir die ganze Stunde dafür benötigten. Wir entwickelten eine Stuktur für das Protokoll mit Überschrift, Inhaltsverzeichnisse, Vorwort etc. und strukturierten alles. 

<h3 id="zweizweinulleins">22.01.19 - Unterricht</h3>
<h4>Stundenaufwand: 01:30</h4>

In der Doppelstunde heute haben wir an der Dokumentation weitergearbeitet. So langsam wurde auch diese sehr umfangreich, weshalb wir auch diese, wie letzte Stunde das Protokoll, einmal strukturierten. Wir haben also eine Aufteilung in das Design, das Gameplay und die Programmierung vorgenommen und eine grobe Einleitung mit den Zielen des Projektes verfasst.

Parallel haben wir ein Script für ein Pausemenü begonnen. Dies funktionierte aber noch nicht ganz einwandfrei, denn das Pausemenü wollte plötzlich nicht mehr verschwinden. Wir ließen das Problem erstmal so und wandten uns der Erstellung des Pausemenü-GameObjektes zu. Da dies relativ einfach ging, hatten wir gegen Ende der Stunde bereits einen halbwegs funktionstüchtigen Prototypen. 

Außerdem haben wir ein Script geschrieben, damit die Maus im Spiel nicht zu sehen ist, außer wenn das zuvor geschriebene Pausemenü aufgerufen wird. Auch dies war leider nicht ganz einfach: Denn die Maus verschwand zwar im Spiel und wurde wieder eingeblendet, wenn man das Menü öffnete, wollte dann aber nicht mehr verschwinden. 

<h3 id="zweidreinulleins">23.01.19 - Zuhause</h3>
<h4>Stundenaufwand: 05:00 </h4>

Das Problem, dass die Maus, nachdem das Pausemenü aufgerufen wurde, nicht mehr verschwindet, haben wir heute gut umgehen können: Und zwar haben wir, statt des Ein- und Ausblendens der Maus durch Drücken der Escape-Taste, einfach überprüft, ob das Pausemenü im Menü-Script geöffnet ist. Abhängig davon haben wir dann eine Variable verändert, welche an das Maus-Script übergeben wurde und nach der dann die Maus aus- oder eingeblendet wurde.

Desweiteren haben wir der Dokumentation weitergearbeitet. Parallel haben wir einen Kaktus für die zweite Insel modelliert, die erste Insel verschönert und eigene Texturen für Grasboden und Sandboden in Photoshop gezeichnet.

<h3 id="zweineunnulleins">29.01.19 - Unterricht</h3>
<h4>Stundenaufwand: 01:30</h4>

Im Unterricht heute haben wir an der Dokumentation geschrieben und das Terrain für die zweite Insel geformt und geplant, was für Gegenstände auf den Inseln zu finden seien sollen. Zum einen wollten wir eine verlassene Hütte mit der Quest, einen Schlüssel aufzusammeln, implementieren, zum anderen haben wir uns darauf geeinigt, wie der Spieler eigentlich am Ende von der Insel entkommen könnte. Währenddessen überlegten wir, wie man ein solches Schlüssel-Aufsammeln eigentlich macht und wie wir das dann umsetzten wollten.

<h3 id="nullviernullzwei">04.02.19 - Unterricht</h3>
<h4>Stundenaufwand: 0:45</h4>

Heute haben wir die Arbeit an unser Dokumentation fortgesetzt und unser Stundenprotokoll gepflegt. Viel Neues haben wir allerdings nicht geschrieben, da wir heute vor allem das bereits Geschriebene Korrektur gelesen haben.

<h3 id="einszweinullzwei">12.02.19 - Unterricht</h3>
<h4>Stundenaufwand: 01:30</h4>

In der heutigen Stunde haben wir an der Dokumentation gearbeitet. Diesmal haben wir allerdings neue Einträge erstellt. Vor allem zum Pausemenü, wessen Umfang allerdings etwas ausgeufert ist. Zudem fehlte bei dem Eintrag der Kamerasteuerung noch einiges an Code, welchen wir dann ergänzt haben. 
Parallel haben wir noch einen weiteren Game-Test vorgenommmen um die bisherigen Ergänzungen noch einmal zu testen. Bisher hat davon alles funktioniert.

<h3 id="einssechsnullzwei">16.02.19 - Zuhause</h3>
<h4>Stundenaufwand: 07:00</h4>

Am heutigen Tag haben wir eine kleine Zwischeninsel gestaltet. Die dafür benötigten Palmen haben wir modelliert und jeden einzelnen Arbeitsschritt daran für die Dokumentation gescreenshottet. Außerdem haben wir weitere Gräser bearbeitet, die zur jeweiligen Umgebung besser passen. So konnten wir rote Gräser für die Wüste und lange etwas gelblichere Gräser ins Wasser platzieren. 

Zudem haben wir weiter am Pausemenü gearbeitet und erste Recherchen zu einem Hauptmenü vorgenommen. Da dies allerdings nicht ganz so einfach ist und aktuell keine Priorität hat, haben wir dies erstmal zurückgestellt. Da das Pausemenü noch nicht ganz perfekt war, haben wir dann Knöpfe hinzugefügt, mit denen man das Spiel beenden oder fortsetzen kann. Den Rest des Pausemenüs haben wir ja bereits zuvor geschrieben, das Spiel wurde erfolgreich gestoppt, als das Menü geöffnet war, aber die Drehung des Charakters war noch möglich, wenn man die Mause bewegte. Daher haben wir das noch einmal behoben und damit das Pausemenü abgeschlossen.

<h3 id="einsneunnullzwei">19.02.19 - Unterricht</h3>
<h4>Stundenaufwand: 01:30</h4>

Heute haben wir an der Dokumentation gearbeitet und die Bilder von der Palme eingebunden. Da wir nämlich beispielhaft die Modellierung eines Objektes in Blender darstellen wollten, haben wir viele Screenshots gemacht, die nun zurechtgeschnitten, bearbeitet und in die Projektseite eingepflegt werden mussten.

Zudem haben wir angefangen ein Script zu schreiben, wodurch der Charakter Gegenstände wie z.B. einen Schlüssel aufheben kann, um endlich einmal ein wenig Gameplay in das Spiel zu implementieren und so ein bisschen Leben in das Spiel zu bringen. Obwohl wir dachten, das ganze sei relativ schwierig zu lösen, haben wir einen relativ simplen Lösungsansatz entwickelt und ausprobiert. Zunächst war unser Ziel, ein Objekt zu zerstören, wenn man in der näheren Umgebung E drückt.

Ergänzend haben wir ein Problem an unserem Sprungscript gelöst, da dies noch nicht ganz perfekt war. Was genau das Problem war, ist uns allerdings nicht ganz klar, weil wir bei der Lösung des Problems ausschließlich nochmal das Script neu geschrieben haben und jetzt eigentlich nur eine frühere Version einsetzen.

<h3 id="zweizweinullzwei">22.02.19 - Zuhause</h3>
<h4>Stundenaufwand: 2:30</h4>

Heute haben wir Zuhause einen Schlüssel implementiert, um zu testen wie das neu angefangene Script funktioniert. Diesen Schlüssel haben wir am selben Tag auch modelliert. Das ganze war erstaunlich einfach, weshalb wir es relativ schnell geschafft haben, das ganze mitsamt Texteinblendung und Verschwinden des Schlüssels nach dem Aufsammeln zu verwirklichen. Zudem haben wir eine Abstandsbedingung implementiert, also dass der Text nur eingeblendet und der Schlüssel nur zerstört wird, wenn man sich in einem bestimmten Radius um den Schlüssel selbst befindet.

Außerdem haben wir sowohl am Stundenprotokoll als auch an der Dokumentation weiter geschrieben und vor allem die am selben Tag gemachten Fortschritte, also das Aufsammeln des Schlüssels, mit Text und Bildern hineingeschrieben.

<h3 id="nulleinsnulldrei">01.03.19 - Zuhause</h3>
<h4>Stundenaufwand: 4:00</h4>

Heute haben wir eine kaputte Brücke und ein Jump n Run von der ersten Insel zur Zwischeninsel gebaut, um das Gameplay ein bisschen spannender zu machen und den Spieler mehr zu fordern. Damit das funktionierte, haben wir zuvor daher noch einmal am Jump Script gearbeitet, sodass wir eine passendere Sprunghöhe und Flugzeit bzw. Gravitationskraft haben, an die die Entfernungen im Jump n Run angepasst werden kann.

Außerdem haben wir versucht Ideen für die dritte Insel umzusetzten bzw. dessen Terrain zu formen. Es standen zuerst eine Vulkaninsel, ein Berg, eine Schlucht und eine Klippe zur Auswahl. Nach einigen Umsetztungsversuchen, haben wir uns für eine Vulkaninsel entschieden und fingen an diese in Blender zu modellieren und zu überlegen, wie man einen Vulkanausbruch programmiertechnisch umsetzen und visualisieren kann.

<h3 id="nullviernulldrei">04.03.19 - Unterricht</h3>
<h4>Stundenaufwand: 0:45</h4>

Heute haben wir erneut an der Dokumentation gearbeitet. Da wir mit den Bildern der Palme, die wir beispielhaft einbinden wollten, noch nicht ganz fertig geworden sind, haben wir vor allem das fortgesetzt. Als wir damit fertig waren, haben wir den Eintrag noch einmal Korrektur gelesen.

<h3 id="nullviernulldreiz">04.03.19 - Zuhause</h3>
<h4>Stundenaufwand: 8:00</h4>

Um eine Atmosphäre fürs Spiel zu erschaffen, haben wir uns daran versucht Musik in unser Spiel zu implementieren. Dafür haben wir diese in FL Studio 20 erstellt, was sehr viel Zeit gekostet hat, da es uns sehr schwer gefallen ist einen Soundtrack mit richtiger Stimmung zu schreiben. Darüber hinaus haben wir uns darüber informiert wie man Musikzonen erstellen kann, sodass jede Insel einen eigenen Soundtrack bekommen kann. Außerdem haben wir uns mit der Funktionsweise von Soundeffekten beschäftigt.

<h3 id="nullfünfnulldrei">05.03.19 - Unterricht</h3>
<h4>Stundenaufwand: 1:30</h4>

Heute haben wir ein Script für eine Lebensleiste geschrieben, damit durch später hinzukommende Gefahren der Schwierigkeitsgrad des Spiels erhöht wird. Da der Charakter im Wasser Schaden bekommen sollte, war es nötig, einen Timer zu erstellen, der nur runterzählt, wenn der Spieler sich im Wasser befindet und bei einem bestimmten Wert ein Event (also GameOver) auslöst. Außerdem haben wir weiterhin versucht Musikzonen einzubauen, dies bisher aber mit wenig Erfolg.
Während wir an dem Script gearbeitet haben, haben wir einen Piranha modelliert und animiert. Dieser dient vorallem als Grund bzw. Erklärung für das Sterben des Spieler im Wasser - durch einen Piranhaangriff.

<h3 id="nullfünfnulldreiz">05.03.19 - Zuhause</h3>
<h4>Stundenaufwand: 2:00</h4>

Da wir nun das Datum für die Abgabe wissen, haben wir uns daran gemacht, das Stundenprotokoll und die Dokumentation deutlich mehr auszuformulieren, um alles rechtzeitig für die Abgabe zu schaffen. 

Die Zeit heute haben wir daher genutzt um an der Dokumentation weiterzuarbeiten, sowie Stichpunkte aus dem Stundenprotokoll auszuformulieren. Da wir im Stundenprotokoll während unseres Arbeitsprozesses alles in Stichpunkten festgehalten haben, fingen wir nun an, alle Stichpunkte in einen Text auszuformulieren.
  
<h3 id="einsachtnulldrei">18.03.19 - Unterricht</h3>
<h4>Stundenaufwand: 0:45</h4>

Auch heute haben wir die Unterrichtsstunde genutzt, um am Stundenprotokoll zu arbeiten. Wieder haben wir weitere vorhandene Stichpunkte ausformuliert und aktuelle Einträge ergänzt.

<h3 id="zweizweinulldrei">22.03.19 - Zuhause</h3>
<h4>Stundenaufwand: 1:30</h4>

Heute Nachmittag haben wir wieder einmal am Stundenblog gearbeitet und weiter ausformuliert. Zudem haben wir angefangen sämtliche Texte nun inhaltlich zu prüfen und zu verbessern. Außerdem haben wir begonnen, ein Vorwort, sowie Hinweise zu formulieren.

<h3 id="zweiviernulldrei">24.03.19 - Zuhause</h3>
<h4>Stundenaufwand: 3:30</h4>

Da wir bereits die letzten paar Male am Stundenblog gearbeitet haben, ist unser Stundenprotokoll fast fertig. Daher haben wir heute noch einmal einiges an Zeit genutzt, um alle Einträge zu überarbeiten und noch ein paar kleine Stichpunkte auszuformulieren. Da wir leider noch kaum Rechtschreib- und Formulierungsfehler korrigiert haben, müssen wir auch die nächsten zwei Unterrichtsstunden nutzen, um den Stundenblog weiter zu bearbeiten. 

<h3 id="zweifünfnulldrei">25.03.19 - Unterricht</h3>
<h4>Stundenaufwand: 0:45</h4>

Heute haben wir erneut am Stundenblog gearbeitet. Dabei haben wir aufgeteilt, was noch genau zu tun ist, also Korrekturlesen, das Inhaltsverzeichnis überprüfen und die Stunden zählen um alles rechtzeitig für die Abgabe zu schaffen.

<h3 id="zweisechsnulldrei">26.03.19 - Unterricht</h3>
<h4>Stundenaufwand: 1:30</h4>

Heute war dann endlich der Tag, an dem wir unseren Stundenblog beendet und das Nachwort formuliert haben. Schreiben, Strukturieren, Korrekturlesen, Verbessern usw. sind damit abgeschlossen und wir haben dann einen Link zu unserem Blog an Herrn Buhl geschickt.

<h1>Nachwort</h1>

Wie im letzten Informatikprojekt gab es auch diesmal wieder einige Stolpersteine. So haben Kameraführung und Sprung-Scipt deutlich zu viel Zeit beansprucht und wir haben uns des Öfteren etwas zu viel im Design und der Gestaltung der Karte verloren. Über unseren Anspruch, den Umfang und die möglichen Probleme waren wir uns schon zu Beginn bereits bewusst, weshalb wir bereits in den Weihnachtsferien angefangen haben an dem Projekt zu arbeiten, um nicht, wie im Projekt zuvor, gegen Ende hin in Zeitstress zu geraten. Dennoch waren wir jetzt am Ende sehr erstaunt darüber, wie viel Zeit wir doch in das Projekt investiert haben und welchen Umfang das ganze bekommen hat, denn unser Anspruch, jegliche Modelle und Texturen sowie Scripts selber zu schreiben, hat das ganze etwas groß werden lassen. Allerdings sind wir mit dem jetzigen Stand des Spiels sehr zufrieden und wir denken, dass bis zum Ende der Projektarbeit noch einiges an Fortschritt sowohl im Projekt, als auch in der Dokumentation zu beobachten sein werden.
