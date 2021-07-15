# Ping Pong Schläger-Reservation

![image info](Bilder/pingPong_banner.png)

# Demovorschau
![Alt Text](Bilder/dragon_ping_pong.gif)


# Inhalt
1. [Kurzfassung](#kurzfassung)
   1. [Idee](#idee)
   2. [Umsetzung](#umsetzung)
   3. [Ergebnis](#ergebnis)
3. [Use cases](#usecase)
   1. [Fully dressed use cases](#fullyDressedUsecases)
   2. [Use case Diagramm](#useCaseDiagramm)
4. [Diagram](#Diagram)
    1. [Klassendiagramm](#klassendiagramm)
    2. [Ablaufdiagramm](#ablaufdiagramm)
5. [Usability-Test](#usability-test)
6. [Wireframe](#wireframe)
7. [Schlusswort](#schlusswort)

## Kurzfassung <a name="kurzfassung"></a>
###Idee <a name="idee"></a>
Mit diesem Tool kann sich der Benutzer beim Reservierungstool anmelden oder registrieren und einen oder mehrere Tischtennisschläger reservieren. Das Tool bietet dem Benutzer weitere Funktionen, wie z. B. die Auswahl, welches Niveau, wie viele Schläger, ob mit oder ohne Tischtennisbälle und für wie lange.

###Umsetzung <a name="umsetzung"></a>
Bei der Umsetzung dieser Idee sind wir so vorgegangen, dass wir zuerst ein MindMap erstellt haben,
welches uns einen Überblick über die verschiedenen umzusetzende Aufgaben verschafft. Danach haben wir diese nach Prioritäten eingeteilt. 
![Mindmapping](Bilder/mindMap.png)


## Mindmap <a name="mindMap"></a>


## Use cases <a name="usecase"></a>
### Fully dressed use cases <a name="fullyDressedUsecases"></a>
![FullyDressedUseCases](Bilder/fullyDressedUseCases/fduc_1_2.png)

![FullyDressedUseCases](Bilder/fullyDressedUseCases/fduc_3_4_5.png)

![FullyDressedUseCases](Bilder/fullyDressedUseCases/fduc_6_7_8_9.png)

![FullyDressedUseCases](Bilder/fullyDressedUseCases/fduc_10_11_12_13_14.png)

## Diagram <a name="Diagram"></a>

### Klassendiagramm <a name="klassendiagramm"></a>
![KlassenDiagramm](Bilder/classDiagram.png)

### Use case Diagramm <a name="useCaseDiagramm"></a>
![use case diagramm](Bilder/uscd.png)

## Usability-Test <a name="usability-test"></a>

### Was möchten wir testen?
Wir möchten testen, wie benutzerfreundlich unsere Applikation ist.
Die Applikation ist so entworfen, dass sie einen Tischtennisschläger für eine bestimmte Zeit reservieren können. Nun wollen wir den Usability-Test überprüfen, indem wir zwei verschiedene Szenarien wie folgt durchspielen:

### Das erste Test-Szenario
Das Wetter ist am Samstag sehr schön und Sie möchten Tischtennis-Schläger für einen ganzen Tag reservieren. Da Ihr Niveau Anfänger und das Ihrer Freunde Profi sind, müssen Sie zwei Tischtennis-Schläger reservieren, aber mit zwei verschiedenen Niveaus.

#### Anweisung: 
1. Nehmen wir an, Sie haben bereits ein Konto erstellt, melden Sie sich an.
2. Klicken Sie auf "Start Reservation".
3. Sie werden auf die nächste Seite weitergeleitet und klicken nun auf "Check Availability".
4. Jetzt können Sie zum Warenkorb hinzufügen, wenn Sie es mögen und es verfügbar ist.
5. Um ein anderes Level zu wählen, klicken Sie auf den Navigationslink "Level".
6. Wiederholen Sie die Schritte 1, 2, 3 und 4 für den zweiten Schläger mit einem anderen Level.

#### Feedback von Person 1 

| Thema | Testergebnis | Verbesserungspotenzial |
| ----------- | ----------- | ----------- |
| Login | ok | - |
| Level auswählen | ok  | - |
| Datum auswählen | ok | - |
| Einen oder mehrere Schläger zum Warenkorb hinzufügen | ok | - |
| Bezahlen | ok  | - |

### Das zweite Test-Szenario
Sie haben sich erfolgreich für die Tischtennisschläger entschieden, die Sie reservieren wollten, aber Sie stellen gerade fest, dass Sie eine Änderung zu Ihrer Reservierung mitbringen sollten. Sie sollten die Verfügbarkeit prüfen, ob es möglich ist, sie an zwei Tagen hintereinander zu reservieren.

#### Anweisung:

1. Navigieren Sie zur Level-Seite.
2. Klicken Sie auf eine der Levels.
3. Um die Verfügbarkeit zu sehen, klicken Sie auf "Check Availability".
4. Wenn es ein passendes Datum für Sie gibt, dass zwei Tage in Folge bietet, wählen Sie das Datum aus und klicken Sie auf Add to shopping cart.

#### Feedback von Person 2 

| Thema | Testergebnis | Verbesserungspotenzial |
| ----------- | ----------- | ----------- |
| Login | ok | - |
| Level auswählen | ok  | - |
| Datum auswählen | nicht ok | Es war nicht sehr benutzerfreundlich, das Verfügbarkeitsdatum zu prüfen. Nach Erhalt des Feedbacks werden nun die verfügbaren Daten mit grün hervorgehobenen Zellen und nicht verfügbare Daten mit rot hervorgehobenen Zellen angezeigt. |
| Einen oder mehrere Schläger zum Warenkorb hinzufügen | ok | - |
| Bezahlen | ok  | - |

## Wireframe
[Wireframe](Wireframe.md) für die Ping-Pong Schläger Reservation.



