# Kapitel 2 Handys

„Die größte Bedrohung der Privatsphäre lauert nicht mehr auf dem
Schreibtisch, sondern in der Hosentasche*.“ ~ John McAfee*

Unser ganzes Leben passt in unsere Hosentasche: Kontakte, Fotos,
Banking-Apps – alles auf einem kleinen Gerät, das wir ständig bei uns
tragen: unser Handy. Es sammelt Unmengen an Informationen über unser
Leben, unsere Gewohnheiten und unseren Standort.

Kein Wunder, dass das Handy eines der am meisten überwachten Geräte ist.
Deshalb ist es entscheidend, ein sicheres und vor allem privates Handy
zu besitzen, damit wir selbst bestimmen können, welche Daten wir teilen
und welche nicht.

Beim Thema „Handys und Privatsphäre“ hört man oft, dass echte
Privatsphäre mit einem Smartphone unmöglich sei. Egal, was man tut,
Hardware und Software würden immer Daten über die Nutzung sammeln – so
das Argument. Sicher steckt da etwas Wahres drin. Aber ich werde dir
jetzt nicht raten, dein Handy wegzuwerfen und nie wieder zu telefonieren
oder Nachrichten zu schreiben – das wäre zu viel verlangt. Stattdessen
möchte ich dir eine Lösung vorstellen, die dir ein Höchstmaß an
Sicherheit und Privatsphäre bietet, ohne dass du auf die Vorteile
moderner Technologie verzichten musst.

Nun stellt sich wahrscheinlich die Frage: Android oder iOS – welches
Betriebssystem bietet mehr Privatsphäre und Sicherheit?

Die Antwort lautet: keines von beiden. Zwar sammelt und teilt Apple in
der Regel weniger Daten als Android (bzw. Google), aber auch hier werden
immer noch viele Informationen erhoben und geteilt. Wer wirklich
Privatsphäre und Sicherheit erreichen möchte, sollte auf ein anderes
Betriebssystem umsteigen. Im vorherigen Kapitel ging es um das
Betriebssystem Linux für Computer. Das gleiche machen wir auch hier mit
unserem Handy.

Ein angepasstes Betriebssystem, auch Custom Operating System genannt,
ist ein System, das nicht vom Handyhersteller stammt, sondern von
unabhängigen Entwicklern erstellt wurde. In diesem Kapitel geht es um
GrapheneOS, ein solches Betriebssystem, das von Daniel Micay ins Leben
gerufen wurde und mittlerweile von einem Entwicklerteam als
Non-Profit-Projekt weitergeführt wird.

Ein separates Betriebssystem klingt vielleicht kompliziert und
umständlich, aber meine Erfahrung zeigt, dass es gar nicht so schwierig
ist. Viele zögern anfangs, den Schritt zu einem neuen Handy und
Betriebssystem zu gehen, doch hinterher sind sie froh über die
Entscheidung und können sich darauf verlassen, dass ihre Daten wirklich
privat und sicher sind. Auch die Benutzerfreundlichkeit leidet nicht
darunter, denn diese Betriebssysteme bieten alle Funktionen, die man von
einem normalen Android-Handy kennt. Optisch merkt man also keinen
Unterschied.

Unsere Anforderungen an das neue Betriebssystem sind: Sicherheit,
Privatsphäre und ein Android ohne Google.

| Hinweis |
|----|
| Ein „entgoogeltes“ Android ist ein Betriebssystem, das auf der reinen Basisversion von Android aufbaut – ohne jegliche Google-Dienste. Das bedeutet: Keine Google-Apps, keine Tracker, kein Play Store und keine Play Services. Es ist die reinste Form von Android. |

Zugegeben, Google bietet viele nützliche Dienste und Apps an. Doch diese
gehen oft mit tiefen Eingriffen in unsere Privatsphäre einher. Dass
Google Daten sammelt und teilt, ist kein Geheimnis – das eigentliche
Problem ist, dass man sich kaum dagegen wehren kann, wenn man dieses
Betriebssystem nutzt.

Das Android Open Source Project, der Kern der Android-Betriebssysteme,
enthält noch immer einige Google-Elemente – was nicht überrascht, da
Google das System entwickelt hat. Doch es gibt Entwicklergemeinschaften,
die alle Google-Komponenten entfernen und diese durch alternative,
sichere Lösungen ersetzen möchten. So werden beispielsweise die
Zeiterfassung oder Benachrichtigungen durch Open-Source-Alternativen
ersetzt, und der bisher von Google bereitgestellte Ortungsdienst durch
eine sicherere Option wie den Mozilla Location Service.

## GrapheneOS

GrapheneOS ist ein „entgoogeltes“ Betriebssystem, das von Grund auf mit
einem klaren Fokus auf Sicherheit und Privatsphäre entwickelt wurde. Es
basiert auf der Grundbasis von Android, also von der Benutzeroberfläche
gibt es nicht viele Unterschiede.

Jedoch merkt man gleich beim Einrichten besteht darin, dass man keinen
Account benötigt, um das Handy zu starten. Ein weiteres Merkmal ist,
dass es keinen App Store oder vorinstallierte Apps gibt – lediglich eine
Kamera-App, einen privaten Browser und einige wenige andere Anwendungen
sind vorhanden. Denn der Nutzer selber soll entscheiden was er braucht
an Apps und was nicht.

Besonders hervorzuheben ist die „App-Sandbox-Funktion“ von GrapheneOS.
Während bei Google-Android Apps frei miteinander und mit dem Internet
kommunizieren können, bleiben die Apps bei GrapheneOS in einem
„Sandkasten“ isoliert. Das bedeutet, dass sie nicht einfach auf andere
Apps zugreifen können und die Kommunikation vollständig blockiert ist.
Zudem kannst du den Internetzugang für einzelne Apps komplett
deaktivieren, sodass sämtliche Daten nur auf dem Gerät selbst bleiben –
etwas, das bei Standard-Betriebssystemen nicht möglich ist.

Ein weiterer Sicherheitsaspekt von GrapheneOS ist die Art und Weise, wie
Updates und die Installation des Betriebssystems gehandhabt werden. Im
Vergleich zu anderen entgoogelten Betriebssystemen ist GrapheneOS das
einzige, bei dem du den Bootloader nachträglich wieder sperren kannst.
Das bedeutet, dass ein Angreifer mit physischem Zugriff auf dein Gerät
kein anderes Betriebssystem installieren kann. Außerdem werden alle
Software sowie Sicherheitsupdates durchgeführt, ohne dass der
Update-Server auf dein Gerät zugreifen muss. Der Server kennt lediglich
die IP-Adresse des Geräts und die Version, die aktualisiert werden soll.
Kurz gesagt, die Risiken von Cyberangriffen und der Installation von
Malware werden drastisch reduziert. GrapheneOS ist also wie Android,
jedoch mit einem maximalen Fokus auf Privatsphäre und Sicherheit.

### Die benötigte Hardware

Wie bereits in Kapitel 1 erwähnt, rate ich dringend davon ab, ein
bereits genutztes Gerät zu verwenden. Denke daran: Dein aktuelles Handy
hast du über Jahre hinweg genutzt, warscheinlich ohne wirklich auf
Privatsphäre oder Sicherheit zu achten. Deine Daten sind auf den Servern
von Google oder Apple gespeichert und mit deiner echten Identität
verknüpft. Zudem sind sie an die Seriennummer des Handys gekoppelt.
Selbst wenn du das Gerät auf die Werkseinstellungen zurücksetzt, bleibt
die Seriennummer bestehen. Nach einiger Zeit könnte das neue
Betriebssystem möglicherweise wieder mit deiner alten Identität in
Verbindung gebracht werden – und all deine Bemühungen um mehr
Privatsphäre wären umsonst.

Um dieses Problem zu umgehen, empfehle ich, ein neues Gerät zu kaufen,
das niemals mit deiner Identität verknüpft wurde. Auch gebrauchte oder
generalüberholte Geräte sind hier keine gute Wahl. Zwar argumentieren
einige Privatsphäre-Experten, dass man mit einem gebrauchten Gerät seine
Spuren verwischen könnte, doch es gibt auch Risiken. Sollte das Gerät
zuvor einem Kriminellen gehört haben, der von Geheimdiensten überwacht
wurde, könnten diese Überwachungen bei dir fortgeführt werden. Und falls
es sich um ein gestohlenes Gerät handelt, könnte die Polizei schnell vor
deiner Tür stehen. Natürlich lässt sich das erklären, aber deine
Identität wäre dennoch mit diesem Gerät verknüpft. Zwar ist das Risiko
für diese beiden Probleme gering, aber ich möchte mir diese
Kopfschmerzen ersparen und bin bereit, dafür minimal mehr zu bezahlen.

Am besten kaufst du ein neues Gerät in einem Elektronikladen und
bezahlst bar. Noch besser wäre es, wenn du einen Freund oder Verwandten
bittest, das Gerät für dich zu kaufen. Falls es Videoaufnahmen des Kaufs
gibt, wäre dein Gesicht nicht mit dem Gerät verknüpft. Ich weiß, das
klingt nach übertriebener Vorsicht, aber es minimiert das Risiko.

### Welches Handy sollte man kaufen?

Leider gibt es nicht viele Optionen, da GrapheneOS ausschließlich auf
Google Pixel-Geräten läuft. Das mag überraschend erscheinen –
schließlich möchten wir doch von Google wegkommen, oder? Ja, das wollen
wir auch. Dennoch nutzen wir lediglich die Hardware von Google, während
wir die Software durch ein privates, sicheres Betriebssystem ersetzen.
Pixel-Geräte sind die einzigen, die hohe Sicherheitsstandards erfüllen
und offiziell die Installation eines anderen Betriebssystems erlauben.

Ich empfehle, eher die neueren Modelle zu kaufen, da diese länger
Sicherheits- und Softwareupdates erhalten. Hier ist eine Liste der
aktuell verfügbaren Geräte sowie der Zeitrahmen, bis wann deren
Sicherheits- und Softwareupdates enden. Eine stets aktuelle Übersicht
findest du unter: grapheneos.org/faq#device-lifetime.

| **Gerätname**           | **Ende von Sicherheits- und Softwareupdates** |
|-------------------------|-----------------------------------------------|
| Google Pixel 9 Pro Fold | August 2031                                   |
| Google Pixel 9 Pro XL   | August 2031                                   |
| Google Pixel 9 Pro      | August 2031                                   |
| Google Pixel 9          | August 2031                                   |
| Google Pixel 8a         | Mai 2031                                      |
| Google Pixel 8 Pro      | Oktober 2030                                  |
| Google Pixel 8          | Oktober 2030                                  |
| Google Pixel Tablet     | Juni 2028                                     |
| Google Pixel 7a         | Mai 2028                                      |
| Google Pixel 7 Pro      | Oktober 2027                                  |
| Google Pixel 7          | Oktober 2027                                  |
| Google Pixel 6a         | Juli 2027                                     |

Tabelle 1: Sicherheitsupdates bei GrapheneOS pro Modell

Letztlich bleibt es deine persönliche Entscheidung, welche Größe,
welches Design und welche technischen Spezifikationen (wie Kamera,
Speicherplatz usw.) du bevorzugst. Ich greife immer lieber zu den
a-Modellen, da sie kleiner und günstiger sind und dennoch mit den
technischen Spezifikationen mithalten können.

## Installation von GrapheneOS

Es gibt zwei Möglichkeiten, GrapheneOS zu installieren: über die
offizielle Webseite oder per Terminal. In diesem Leitfaden konzentrieren
wir uns auf die einfachere webbasierte Variante, die besonders für
weniger technikaffine Nutzer geeignet ist. Wenn du bereits Erfahrung mit
dem Terminal hast, kannst du eine detaillierte Anleitung dafür unter
grapheneos.org/install/cli einsehen.

Für alle anderen beschreibe ich nun Schritt für Schritt den webbasierten
Installationsprozess. Nimm dir dafür ausreichend Zeit, denn die
Installation kann unter Umständen abgebrochen werden oder länger dauern.
Plane idealerweise etwa zwei Stunden ein, auch wenn der eigentliche
Flash-Vorgang meist nur 20 bis 40 Minuten in Anspruch nimmt. Die
folgenden Schritte sind bewusst ausführlich gehalten, um mögliche Fehler
zu minimieren. Beachte, dass sich die Anleitung in Zukunft ändern kann,
auch wenn der grundlegende Prozess ähnlich bleibt. Bevor wir mit der
Installation von GrapheneOS beginnen können, muss das Handy vorbereitet
werden. Dieser Schritt ist bei beiden Installationsmethoden
erforderlich.

- Starte dein Google Pixel-Handy. Es werden einige Informationen
  abgefragt, und du wirst gebeten, dich mit einem Google-Konto
  anzumelden. Überspringe alles und gib keine persönlichen Daten ein.
  Auch WLAN, PIN und Zeitzone musst du nicht eingeben. Unser Ziel ist es
  nur, in die Einstellungen zu gelangen.

- Wisch nach oben, um das Menü mit den Apps zu öffnen, und tippe auf
  „Einstellungen“.

- Wähle den Punkt „Über das Telefon“ aus.

- Scrolle nach unten und tippe mehrmals (ca. 7–10 Mal) auf die
  „Build-Nummer“, bis die Meldung „Du bist jetzt Entwickler“ erscheint.

- Gehe zurück ins Hauptmenü der Einstellungen und öffne den Unterpunkt
  „System“.

- Wähle dort die „Entwickleroptionen“ aus und aktiviere sowohl
  „OEM-Entsperrung“ als auch „USB-Debugging“.

- Schalte danach das Handy aus.

### Installation von GrapheneOS über die Webseite

- Öffne auf deinem Computer/Laptop die Webseite
  grapheneos.org/install/web. Hier findest du eine Übersicht über die
  verschiedenen Schritte – es kann hilfreich sein, diese einmal
  durchzulesen, bevor du weitermachst.

- Drücke gleichzeitig den Ein/Aus-Knopf und die Leiser-Taste (der
  oberste und unterste Knopf auf der rechten Seite des Geräts). Dies
  bringt dich ins Bootloader-Interface, wie auf der Webseite gezeigt.

- Verbinde das Handy mit deinem Computer, am besten mit dem originalen
  Kabel, das mit dem Handy geliefert wurde, um mögliche Probleme zu
  vermeiden.

- Klicke auf der Webseite auf „Unlock bootloader“. Eine Benachrichtigung
  erscheint, in der du dein Gerät (z. B. Google Pixel 7a) auswählst und
  mit „Connect“ bestätigst.

- Drücke auf deinem Handy die Leiser-Taste, bis „Unlock Bootloader“
  ausgewählt ist, und bestätige die Auswahl mit dem Ein/Aus-Knopf. Es
  sollte jetzt rot „unlocked“ stehen, siehe Abbildung 7 links.

- Zurück auf der Webseite klicke auf „Download release“.

- Sobald der Download abgeschlossen ist, klicke auf „Flash release“.
  Dies überspielt GrapheneOS auf dein Handy – das kann ein paar Minuten
  dauern.

- Anschließend klicke auf der Webseite auf „Lock bootloader“.

- Wähle erneut mit der Leiser-Taste auf dem Handy „Lock Bootloader“ aus
  und bestätige dies mit dem Ein/Aus-Knopf.

- Zum Abschluss sollte im Handy-Interface der Eintrag „Device state:
  locked“ in Grün erscheinen (siehe Abbildung 7 rechts). Der Prozess ist
  damit abgeschlossen.

- Wähle mit der Leiser-Taste „Start“ und starte das Handy durch Drücken
  des Ein/Aus-Knopfes neu. GrapheneOS wird nun gestartet.

<span id="_Toc196572870" class="anchor"></span>Abbildung 7 Bootemenü
GrapheneOS

Auch das mitgelieferte Kabel des Herstellers ist entscheidend, da die
Verwendung anderer Kabel Fehler verursachen kann. Ich hoffe, dass du
GrapheneOS erfolgreich installiert hast und wir nun mit der Einrichtung
fortfahren können.

Während des Startvorgangs – und auch bei zukünftigen Neustarts – wird
eine Meldung erscheinen: „Your device is loading a different operating
system“ („Ihr Gerät lädt ein anderes Betriebssystem“). Diese Warnung
kann ignoriert werden; sie ist lediglich ein Versuch von Google, dich
zurückzugewinnen.

## Erste Schritte nach der Installation

- Wähle deine bevorzugte Sprache und Region. Zwar kannst du hier falsche
  Angaben machen, aber das führt in der Praxis oft zu mehr Problemen als
  Nutzen. Deshalb empfehle ich, Deutschland und Deutsch auszuwählen.

- Deaktiviere den Standort. Dies kannst du später nach Belieben anpassen
  – dazu später mehr.

- Schütze dein Gerät mit einer sicheren PIN. Die Fingerabdruck-Option
  überspringen wir vorerst.

- Überspringe alle Wiederherstellungsoptionen und tippe auf „Start“.

GrapheneOS ist jetzt installiert und einsatzbereit. Es sind keine
Updates unmittelbar nach der Installation erforderlich, da die neueste
Version bereits heruntergeladen wurde. Dein Gerät ist nun vollständig
verschlüsselt und frei von Google-Diensten. Obwohl GrapheneOS von Haus
aus äußerst sicher und privat ist, nehmen wir einige zusätzliche
Einstellungen vor, um das Beste aus dem System herauszuholen.

- Gehe in die Einstellungen und wähle erneut den Punkt „Über das
  Telefon“ aus.

- Tippe wiederholt auf die „Build-Nummer“, bis du erneut als Entwickler
  freigeschaltet bist. Gib deine PIN ein, falls nötig.

- Gehe dann zurück zu „System“ und öffne die „Entwickleroptionen“.

- Vergewissere dich, dass „OEM-Entsperrung“ und „USB-Debugging“
  deaktiviert sind; schalte sie falls nötig aus.

- Schalte anschließend oben „Entwickleroptionen verwenden“ ab und starte
  das Handy neu.

### WLAN

Wenn das WLAN auf deinem Handy aktiviert ist, sucht es ständig nach
bekannten Netzwerken. Dabei überträgt es einzigartige
Identifikationsmerkmale, die für Tracking-Zwecke genutzt werden können.
Besonders in Einkaufszentren ist dies weit verbreitet. Verschiedene
Geschäfte verwenden WLAN-Verbindungen, um die Bewegungen und
Einkaufsgewohnheiten der Kunden zu verfolgen. Du musst dich nicht einmal
mit deren WLAN verbinden; es genügt, das WLAN aktiviert zu haben. Dein
Handy sucht dann nach bekannten Netzwerken und übermittelt entsprechende
Informationen. Um das zu verhindern, sollte das WLAN stets deaktiviert
sein, es sei denn, du verbindest dich gezielt mit einem Netzwerk. Da man
jedoch häufig vergisst, das WLAN auszuschalten, wenn man das Haus
verlässt, bietet GrapheneOS eine nützliche Funktion: Es kann das WLAN
automatisch deaktivieren, sobald du das Haus verlässt.

- Gehe dazu in die Einstellungen und suche nach „Turn off Wi-Fi
  automatically“.

- Standardmäßig ist „never“ voreingestellt. Ich empfehle, „2 min“
  auszuwählen, damit das WLAN nach zwei Minuten ohne Netzwerkverbindung
  automatisch ausgeschaltet wird.

### Auto-Reboot

Bei GrapheneOS ist standardmäßig eingestellt, dass das Gerät nach 72
Stunden automatisch neu startet. Dies ist ein Sicherheitsfeature. Wenn
dein Handy gestohlen oder beschlagnahmt wird oder verloren geht und über
72 Stunden nicht entsperrt wird, erfolgt ein Neustart. Dadurch wird eine
erneute PIN-Eingabe erforderlich, der Fingerabdrucksensor wird
deaktiviert und zwischengespeicherte Dateien werden gelöscht. Persönlich
bevorzuge ich es, den automatischen Neustart auf 24 Stunden zu setzen.

- Um dies anzupassen, gehe in die Einstellungen, suche nach
  „Auto-Reboot“ und wähle die gewünschte Zeitdauer aus.

### Fingerabdruck

In der Privatsphäre-Community wird intensiv darüber diskutiert, ob man
einen Fingerabdruck zur Entsperrung des Handys verwenden sollte. Ein
Argument dafür ist, dass in öffentlichen Räumen andere Personen oder
Kameras einen bei der Eingabe der PIN beobachten können. Ein
Fingerabdruck ist in solchen Situationen diskreter. Andererseits besteht
das Risiko, dass jemand dich unter Zwang oder im Falle einer
Bewusstlosigkeit deinen Fingerabdruck nutzen könnte, um das Handy zu
entsperren. In diesem Fall bietet eine PIN mehr Sicherheit. Zudem hat
die Polizei das Recht, deinen Fingerabdruck zu verwenden, um Zugang zu
deinem Handy zu erhalten, während dies bei einer PIN komplizierter ist.
Du musst also selbst entscheiden, welchen Weg du wählen möchtest. Sollte
du dich für die Einrichtung des Fingerabdrucks entscheiden, wird dieser
nicht mit anderen geteilt und auch nicht als Bild auf dem Gerät
gespeichert. Es werden lediglich Daten gespeichert, die überprüfen, ob
es sich um deinen Fingerabdruck handelt.

- Um den Fingerabdruck zu aktivieren, suche in den Einstellungen nach
  „Fingerabdruck“.

- Zum Einrichten musst du deine PIN bestätigen und den Anweisungen
  folgen.

### PIN-Scrambling

Um zu verhindern, dass jemand deine PIN-Eingabe über die Schulter oder
mit Kameras beobachtet, kannst du die Funktion des sogenannten
PIN-Scramblings aktivieren. Diese Funktion verändert zufällig die
Positionen der Zahlen auf dem Sperrbildschirm, sodass es unmöglich wird,
deine PIN allein durch Zuschauen zu erraten. Zwar dauert die Eingabe der
PIN dadurch etwas länger, aber sie erhöht die Sicherheit erheblich.

- Um diese Funktion zu aktivieren, suche in den Einstellungen nach
  „Scramble PIN input layout“ und aktiviere sie.

### **Duress-Passwort**

Das Duress-Passwort ist eine Art „Selbstzerstörungscode“ in GrapheneOS,
der für Situationen entwickelt wurde, in denen dein Hauptpasswort
möglicherweise kompromittiert wurde. Mit einer speziellen PIN kannst du
das Gerät zurücksetzen oder sensible Daten löschen. Diese Funktion
sollte jedoch mit äußerster Vorsicht verwendet werden, da die Eingabe
des Duress-Passworts zur sofortigen Löschung aller Daten auf dem Gerät
führt. Daher sind regelmäßige Backups in diesem Zusammenhang besonders
wichtig.

- Zum Aktivieren suche in den Einstellungen nach „Duress password“ und
  wähle das gewünschte Selbstzerstörungspasswort.

### ![](images/media/image9.png)Schnelleinstellungen

GrapheneOS ermöglicht es, die Kamera und das Mikrofon auf Softwareebene
zu deaktivieren. Wenn eine App Zugriff auf die Kamera oder das Mikrofon
benötigt, erhältst du eine Benachrichtigung und kannst diese Funktionen
aktivieren. Anschließend musst du die Kamera und das Mikrofon manuell
wieder sperren. Um schnellen Zugriff auf diese Einstellungen zu haben
und sie stets im Blick zu behalten, kannst du sie im Schnellzugriffsmenü
hinterlegen.

- Um das Schnellzugriffsmenü anzupassen, ziehe das Menü herunter und
  klicke auf das Stiftsymbol.

- Jetzt kannst du durch Halten und Verschieben das Menü so anpassen, wie
  es für dich am besten ist.

- Bei mir steht in der ersten Reihe „Internet“ und „Flugmodus“. In der
  zweiten Reihe befinden sich „Mikrofonzugriff“ und „Kamerazugriff“,
  damit ich schnell sehe, ob Kamera und Mikrofon blockiert sind.

- Darunter habe ich „Standort“, „Bluetooth“, „Taschenlampe“ und
  „Energiesparmodus“ angeordnet, da ich diese häufig verwende. Du kannst
  natürlich nach Belieben anpassen, was für dich am wichtigsten ist.

## ![](images/media/image11.png)Nutzerprofile

Moderne Android-Geräte ermöglichen es, mehrere Nutzerprofile zu
erstellen. Das ist besonders praktisch, um verschiedene Lebensbereiche,
wie Arbeit und Privatleben, zu trennen oder Apps voneinander zu
separieren. So können Apps in dem einen Profil nicht auf Apps oder Daten
in anderen Profilen zugreifen. Jedes Profil hat also seine eigenen
Einstellungen, Apps und Sicherheitsmaßnahmen. Während Android bis zu
vier Profile unterstützt, erlaubt GrapheneOS die Erstellung von bis zu
32 Profilen.

Theoretisch kannst du für jede App ein eigenes Profil erstellen, um
maximale Privatsphäre zu erreichen. Für die meisten von uns wäre das
jedoch zu aufwendig und unnötig. Zusätzlich kannst du je nach Profil
unterschiedliche Sicherheitsfunktionen aktivieren, z. B. Fingerabdruck,
längere PINs oder PIN-Scrambling. Hier folgen einige empfohlene
Profil-Typen.

**Eigentümer (nur PIN):** Dies ist das Standardprofil, das nicht
gelöscht werden kann. Einige systemübergreifende Einstellungen lassen
sich nur hier vornehmen. Ich halte dieses Profil möglichst leer und
nutze es kaum. Die einzigen installierten Apps sind F-Droid, Aurora
Store und eine VPN-App, um sie in andere Profile zu kopieren.

**Privat (PIN und Fingerabdruck für schnellen Zugriff):** Dieses Profil
wrd am häufigsten genutzt. Hier mache ich Fotos, speichere meine
Kontakte, installiere und verwende Apps und surfe im Internet. Alle
Messenger-Apps sind in diesem Profil, sodass ich die meiste Zeit hier
verbringe.

**Arbeit (PIN und Fingerabdruck):** Um Arbeit und Privatleben zu
trennen, nutze ich ein separates Arbeitsprofil. Hier sind alle
Arbeits-E-Mails, Messenger und Apps, die ich ausschließlich beruflich
benötige. Diese Trennung hilft mir, mich voll auf die Arbeit zu
konzentrieren, ohne dass sich die Bereiche vermischen.

**Finanzen (PIN und PIN-Scrambling für maximale Sicherheit):** Viele
Banken verlangen die Nutzung einer speziellen Banking-App für den
Zugriff auf Konten und Transaktionen. Da Banken bekannt dafür sind,
viele Nutzerdaten zu sammeln, ist es sinnvoll, ein separates Profil für
solche Apps zu nutzen. So bleiben andere Profile vor Datenzugriffen
geschützt, und meine Finanzdaten sind vor unerwünschtem Zugriff sicher.

**Unsichere Apps (PIN und Fingerabdruck für schnellen Zugriff):** In
diesem Profil sollten alle Apps untergebracht werden, die möglicherweise
unsicher sind und viele Daten sammeln – beispielsweise Google- und
Facebook-Apps. Durch die Isolierung dieser Anwendungen kann ich die
Menge an Daten minimieren, die solche Unternehmen sammeln.

**Privacy (PIN und PIN-Scrambling für maximale Sicherheit):** In diesem
Profil strebe ich maximale Anonymität an. Hier nutze ich den Tor-Browser
und Bitcoin-Apps, um sicher und privat zu surfen und zu bezahlen, ohne
dass andere Profile davon Kenntnis erlangen.

Wenn du eine Identität vollständig von einem Alias trennen möchtest,
kannst du für diesen Alias ein eigenes Profil mit speziellen Messenger-
und E-Mail-Apps einrichten. Allerdings musst du jedes Profil manuell
konfigurieren – das bedeutet, alle Apps neu herunterzuladen und die
Einstellungen anzupassen, was zeitaufwendig sein kann. Es ist wichtig,
im Voraus zu überlegen, welche Profile du wirklich benötigst. Eine
weitere Idee wäre, ein eigenes Profil nur für die Navigation zu
erstellen, sodass der Standort in den anderen Profilen immer deaktiviert
bleibt. Es gibt viele Möglichkeiten, Profile individuell anzupassen.

### Nutzerprofil erstellen

- Öffne die „Einstellungen“ und wähle „System“ und dann „Mehrere
  Nutzer“.

- Aktiviere die Option „Mehrere Nutzer“ und erstelle über „Nutzer
  hinzufügen“ ein neues Profil.

- Jetzt kannst du Berechtigungen festlegen. Deaktiviere „Im Hintergrund
  ausführen erlauben“, um die Akkulaufzeit zu schonen.

- Schalte „Telefonieren & SMS zulassen“ je nach Bedarf ein oder aus.

- Über „Verfügbare Apps installieren“ kannst du Apps aus dem
  Eigentümerprofil auf das neue Profil übertragen. Ich empfehle dies für
  den Aurora- und F-Droid-Store sowie für deine VPN-App, falls
  vorhanden. Das erspart dir Arbeit.

- Um zwischen Profilen zu wechseln, ziehe das Schnelleinstellungsmenü
  herunter und klicke auf das Benutzersymbol.

- Beende eine Sitzung, indem du auf das Ein-/Ausschalt-Symbol klickst
  und „Sitzung beenden“ auswählst. So wird verhindert, dass das Profil
  im Hintergrund weiterläuft und Ressourcen verbraucht.

- Es macht auch Sinn, das Telefon nach der Nutzung von Profilen komplett
  neu zu starten, um sicherzustellen, dass alles sauber beendet wird.

Im Eigentümerprofil kannst du deine Profile verwalten oder löschen –
besonders nützlich, wenn du dein Gerät in Situationen verwendest, in
denen es möglicherweise beschlagnahmt wird, beispielsweise bei
Grenzkontrollen. So kannst du ungenutzte Profile löschen und später aus
einem Backup wiederherstellen.

Es ist jedoch wichtig zu beachten, dass diese Profile auch
Einschränkungen haben. Obwohl Apps und Daten in jedem Profil isoliert
sind, teilen sie sich dennoch dieselben Standortdaten (sofern
aktiviert), die Internetverbindung, die Telefonnummer sowie GPS,
Bluetooth und die Hardware-Identifizierung. Nutzerprofile können somit
zur Verbesserung der Privatsphäre beitragen, jedoch gibt es auch
Grenzen.

## Installieren von Apps

Im Unterschied zu anderen Betriebssystemen wirst du schnell feststellen,
dass auf deinem Smartphone kein App-Store vorinstalliert ist – weder der
Google Play Store noch eine Alternative. Das bedeutet, dass du selbst
für die Installation von Apps verantwortlich bist. Den Google Play Store
solltest du von Anfang an meiden, da er Unmengen an Daten über die von
dir genutzten Apps sowie über die Zeiten und die Dauer ihrer Nutzung
sammelt. Zudem benötigst du einen Google-Account, um Apps
herunterzuladen oder zu aktualisieren. Obwohl der Google Play Store bei
Android-Systemen weit verbreitet ist, gibt es bessere Alternativen, die
wir uns näher ansehen werden.

Die erste Anlaufstelle ist der **F-Droid-Store**. F-Droid ist eine freie
und Open-Source-Plattform für Android-Apps. Sie ist gemeinnützig, und
alle Apps dort sind kostenlos, wobei die Möglichkeit besteht, den
Entwicklern zu spenden. Du kannst Apps direkt über F-Droid suchen,
herunterladen und installieren, ohne ein Konto erstellen zu müssen.

Der Vorteil: Rund 95 % der Apps im F-Droid-Store sind Open Source und
enthalten keine Tracker. Das macht F-Droid zur besten Wahl für den
Anfang. Lass uns also zuerst den F-Droid-Store herunterladen.

- Öffne den Vanadium-Browser und gehe auf die Webseite  
  f-droid.org.

- Klicke auf „Download F-Droid“ und bestätige den Download im Pop-up mit
  „Herunterladen“.

- Öffne die heruntergeladene Datei. Nun erscheint ein Pop-up, das
  bestätigt, dass du Apps aus dem Vanadium-Browser installieren willst.

- Klicke auf „Einstellungen“ im Pop-up und aktiviere „Dieser Quelle
  vertrauen“.

- Klicke im nächsten Pop-up auf „Installieren“, um die Installation von
  F-Droid abzuschließen.

- Öffne die App. Sie aktualisiert sich kurz, und dann kannst du direkt
  mit dem Installieren von Apps loslegen.

- Um neue Apps zu installieren, suche sie in F-Droid (mit der Lupe unten
  links) und klicke auf „Installieren“, – und schon ist sie auf deinem
  Gerät.

Jetzt hast du einen App-Store, der vollständig ohne Google funktioniert
und dir den Zugang zu zahlreichen Open-Source-Apps ermöglicht, ohne dass
eine Anmeldung erforderlich ist. Allerdings wirst du schnell
feststellen, dass einige gewünschte Apps fehlen. Dies liegt daran, dass
F-Droid etwa 3.000 Apps anbietet, während der Google Play Store über 3
Millionen verfügt. Um dennoch Zugriff auf die meisten Apps zu erhalten,
installieren wir zusätzlich den Aurora Store.

- Öffne den F-Droid-Store, klicke auf die Lupe unten links und suche
  nach „Aurora Store“.

- Wähle den Aurora Store aus und klicke auf „Installieren“.

- Wie zuvor musst du auch dem F-Droid-Store erlauben, Apps
  herunterzuladen. Klicke dafür auf „Einstellungen“ und aktiviere
  „Dieser Quelle vertrauen“.

- Klicke abschließend im Pop-up auf „Installieren“, um die Installation
  abzuschließen.

Der Aurora Store ist ein kostenloses, inoffizielles Front-End für den
Google Play Store. Er ermöglicht es Nutzern, Apps aus dem Play Store
herunterzuladen, ohne ein Google-Konto erstellen zu müssen und ohne
dabei getrackt zu werden. Zudem informiert der Aurora Store darüber,
welche Apps Tracker verwenden und welche nicht.

- Öffne nach der Installation den Aurora Store und klicke auf „Weiter“.

- Klicke bei „Installation unbekannter Apps.“ auf „Erlauben“ und
  aktiviere „Dieser Quelle vertrauen“.

- Klicke bei „Speicherverwaltung…“ auf „Erlauben“, wähle den „Aurora
  Store“ aus und aktiviere „Zugriff zum Verwalten aller Dateien
  zulassen“.

- Gehe zurück und klicke auf „Weiter“.

- Klicke bei „play.google.com“ auf „Aktivieren“, dann auf „Link
  hinzufügen“ und wähle „play.google.com“ aus und füge dies hinzu.

- Gehe zurück und klicke auf „Fertig“.

- Wähle „Anonym“ beim Öffnen der App, um Apps herunterzuladen, ohne dich
  mit einem Google-Account anzumelden.

Jetzt haben wir sowohl den F-Droid-Store als auch den Aurora Store
installiert. Beide ermöglichen es uns, Apps ohne Anmeldung
herunterzuladen. Zwar kann der Installationsprozess etwas Zeit in
Anspruch nehmen, aber das musst du nur einmal machen.

Bei der Suche nach neuen Apps solltest du immer zuerst im F-Droid-Store
nachsehen und den Aurora Store nur nutzen, wenn du dort nichts Passendes
findest.

Die meisten Apps, die wir herunterladen, sind kostenlos und Open Source.
Dennoch müssen Entwickler von etwas leben, daher sind Spenden eine
Möglichkeit, ihre Arbeit zu unterstützen.

Wenn dir eine App gefällt und du sie regelmäßig nutzt, solltest du dem
Entwicklerteam etwas spenden – es muss nicht viel sein, aber es zeigt
Wertschätzung und hilft, Projekte zur Wahrung der Privatsphäre zu
fördern.

Die Links zu den Spendenseiten von Apps, die hier empfohlen sind,
findest du auf privatopia.de/open-source-spenden.

## Apps

Es mag verlockend sein, sofort alle Apps herunterzuladen, die du zuvor
auf deinem Smartphone hattest. Ich empfehle jedoch, dies zu vermeiden.
Wer ernsthaft seine Privatsphäre schützen möchte, sollte sein Smartphone
auf seine grundlegende Funktion – die Kommunikation – beschränken. Viele
Menschen installieren Dutzende Apps, die sie nur einmal nutzen und dann
vergessen. Diese Apps verfügen oft über umfangreiche Berechtigungen,
sammeln Daten und sind häufig mit Trackern ausgestattet. Daher ist es
ratsam, die Anzahl der installierten Apps auf ein Minimum zu reduzieren.

In den kommenden Kapiteln werde ich Empfehlungen für häufig genutzte
Apps sowohl für Computer als auch für Smartphones geben. Jeder hat
unterschiedliche Bedürfnisse und verwendet verschiedene Apps. Ich
empfehle dir daher, regelmäßig alle installierten Apps zu überprüfen und
diejenigen zu deinstallieren, die du nicht mehr nutzt.

Ein zusätzlicher Browser kann ebenfalls von Vorteil sein. GrapheneOS hat
den Vanadium-Browser vorinstalliert, der bereits sehr gut ist, aber ich
möchte dich dazu anregen, noch einen Schritt weiterzugehen.

- Installiere den „DuckDuckGo Browser“ über den F-Droid-Store.

- Nach dem Öffnen wirst du gebeten, DuckDuckGo als Standard-Browser
  festzulegen. Bestätige dieses Pop-up.

- Gehe in die Einstellungen, indem du auf die drei Punkte oben rechts
  klickst.

- Deaktiviere unter „Allgemeines“ und „Passwörter“ alle Optionen.

- Gehe zu „Fire Button“ und wähle bei „Automatisches Löschen von“ die
  Option „Tabs und Daten“. Stelle bei „Löschen“, „Beim Verlassen der
  App, 1 Stunde lang inaktiv“ ein.

DuckDuckGo löscht automatisch alle Browserdaten, Suchanfragen und
Verläufe, sobald du die App schließt oder länger als eine Stunde inaktiv
bist. Für schnelle Suchanfragen, z. B. zum Wetter oder zu Nachrichten,
nutzen wir DuckDuckGo und können sicher sein, dass danach keine Daten
gespeichert werden. Da DuckDuckGo unser Standardbrowser ist, werden alle
Links darüber geöffnet und alle Daten anschließend gelöscht.

Ich persönlich verwende den DuckDuckGo-Browser für etwa 90 % meiner
Internetnutzung. Für die verbleibenden 10 % nutze ich den
Vanadium-Browser, und zwar ausschließlich für Seiten, auf denen ich
meine Anmeldedaten speichern möchte – z. B. für den Zugriff auf
ProtonMail, um meine E-Mails zu überprüfen. So kann ich sicherstellen,
dass keine Verbindung zwischen den beiden Browsern besteht und meine
Privatsphäre gewahrt bleibt.

## Backups

Nachdem wir GrapheneOS eingerichtet haben, ist es wichtig, regelmäßig
Backups zu erstellen. Dienste wie Google Drive und iCloud bieten zwar
automatische Backup-Lösungen an, jedoch oft auf Kosten unserer
Privatsphäre. Ich empfehle, einmal im Monat ein Backup deiner
Einstellungen und Anpassungen auf einem USB-Stick zu erstellen. Ein
SanDisk Dual Drive USB-Stick mit 128 GB ist dafür ideal und kostet etwa
15 €.

- Gehe dafür in die „Einstellungen“, wähle „System“ und dann „Sicherung“
  aus.

- Wähle den USB-Stick aus und warte kurz, bis das Backup startet.

- Das Backup ist durch einen Wiederherstellungscode geschützt, den du
  benötigst, um darauf zugreifen zu können. Klicke deshalb auf
  „Wiederherstellungscode“ und speichere die Wörter sicher, z. B. in
  einem Passwortmanager.

- Aktiviere unter „Meine Apps sichern“ und „App-Sicherung“ beide
  Optionen.

- Jedes Mal, wenn du ein Backup machen möchtest, musst du den USB-Stick
  anschließen, oben rechts auf die drei Punkte tippen und „Jetzt
  sichern“ auswählen.

Solltest du dein Handy verlieren oder sollte es gestohlen werden, kannst
du deine alten Daten problemlos auf einem neuen Gerät wiederherstellen.

Ich verwalte meine Fotos lieber auf dem Laptop und nutze das Handy
hauptsächlich als Kamera. Daher übertrage ich meine Fotos und Videos
monatlich auf den Laptop, wobei ich einen USB-Stick als Zwischenspeicher
verwende.

- Öffne dafür die „Dateien-App“ und stecke den USB-Stick ins Handy.

- Tippe oben links auf die drei Striche und wähle „Bilder“ aus.

- Markiere alle Ordner durch längeres Drücken.

- Klicke oben rechts auf die drei Punkte und wähle „Kopieren nach …“
  aus.

- Tippe wieder oben links auf die drei Striche, wähle den USB-Stick aus
  und klicke auf „KOPIEREN“.

- Wiederhole dieselben Schritte für die Videos.

- Verbinde danach den USB-Stick mit dem Laptop, um die Fotos zu
  übertragen.

Nach der Sicherung auf dem Laptop besteht die Möglichkeit, die Fotos vom
Handy zu löschen, wobei dieser Schritt optional ist. So haben wir ein
monatliches Backup unserer Fotos und Videos und verlieren im schlimmsten
Fall nur die neuesten Aufnahmen.

## Updates

Ein bedeutender Vorteil von GrapheneOS im Vergleich zu anderen
Betriebssystemen sind die regelmäßigen Sicherheits- und
Software-Updates, die etwa alle ein bis zwei Wochen bereitgestellt
werden. Im Gegensatz dazu erhalten andere Systeme oft nur alle ein bis
zwei Monate Updates. Dadurch bleibt dein Gerät stets auf dem neuesten
Stand und optimal geschützt. Sobald ein Update verfügbar ist, erhältst
du eine Benachrichtigung, um es herunterzuladen. Der anschließende
Neustart des Handys verläuft reibungslos und unkompliziert.

## Berechtigungen

Es ist ratsam, regelmäßig zu überprüfen, welche Berechtigungen du den
Apps gewährt hast und ob diese tatsächlich erforderlich sind. Oftmals
erteilen wir mehr Berechtigungen als nötig, da dies schnell über ein
Pop-up erledigt wird. Daher nehme ich mir mindestens einmal im Monat die
Zeit, um überflüssige Berechtigungen zu entziehen.

- Gehe in die „Einstellungen“ und suche nach „Berechtigungsmanager“.

Hier kannst du einsehen, welche Berechtigungen jede App benötigt, und
diese nach Bedarf entziehen. Mit GrapheneOS hast du zudem die
Möglichkeit, Apps den Internetzugang vollständig zu verwehren, und zwar
unter dem Punkt „Netzwerk“. So kannst du sicherstellen, dass die
eigenständig gesammelten Daten nicht übertragen werden können.

### Storage Scopes

GrapheneOS bietet eine praktische Funktion, mit der du den Zugriff von
Apps auf Dateien gezielt einschränken kannst. So kannst du die App
weiterhin nutzen, ohne dass sie Zugriff auf persönliche Daten erhält.
Diese Funktion nennt sich Storage Scopes. Wenn eine App Zugriff auf
Dateien anfordert, stehen dir drei Optionen zur Verfügung: „Erlauben“,
„Nicht zulassen“ und „Storage Scopes einrichten“.

- Um Storage Scopes zu aktivieren, wähle „Setup Storage Scopes“ und dann
  „Enable Storage Scopes“.

- Jetzt kannst du einen Ordner, eine Datei oder ein Bild auswählen, auf
  die die App Zugriff erhalten soll.

- Ich wähle immer Ordner aus. Dafür auf „Add Folder“ klicken, einen
  neuen Ordner erstellen (idealerweise mit dem Namen der App) und auf
  „Diesen Ordner verwenden“ klicken.

Die App hat jetzt nur Zugriff auf einen spezifischen Ordner und kann
dort Dateien lesen, bearbeiten oder speichern. Es wird der Eindruck
erweckt, dass die App Zugriff auf alle Dateien hat, während deine Daten
geschützt bleiben. Ich nutze Storage Scopes für fast alle Apps, die
Speicherzugriff benötigen, z. B. für den E-Book-Reader Librera FD. Ich
habe einen Ordner mit dem Namen „LibreraFD“ erstellt und alle meine
E-Book-Dateien dort abgelegt. So kann ich die E-Books lesen, ohne dass
die App über Zugriff auf meine anderen Daten hat.

### Contact Scopes

Genau wie beim Speicher bietet GrapheneOS auch die Möglichkeit, den
Zugriff auf Kontakte einzuschränken. Wenn eine App Zugriff auf deine
Kontakte anfordert, kannst du mit Contact Scopes steuern, welche
Kontakte angezeigt werden. Da Kontakte äußerst sensible Informationen
enthalten, verwende ich stets Contact Scopes.

- Um Contact Scopes zu aktivieren, wähle „Setup Contact Scopes“ und dann
  „Enable Contact Scopes“.

- Jetzt kannst du zwischen „Label“, „Contact“, „Number“ und „E-Mail“
  auswählen.

Mit „Label“ kannst du Kontaktgruppen wie „privat“ oder „beruflich“
auswählen. Die App sieht dann nur die Kontakte dieser Gruppe, allerdings
mit allen Informationen (Telefonnummer, Geburtstag, E-Mail usw.). Mit
„Contact“ wählst du manuell einzelne Kontakte aus, allerdings werden
auch hier alle Informationen angezeigt. Mit „Number“ sieht die App nur
den Namen und die Telefonnummer, der Rest bleibt verborgen – meine
bevorzugte Einstellung. Mit „E-Mail“ ist es ähnlich, hier werden nur der
Name und die E-Mail-Adresse angezeigt.

## WiFi Calling

Eine weitere Möglichkeit, deine Privatsphäre zu schützen, ist „WiFi
Calling“. Viele Mobilfunkanbieter bieten diesen Service an. Anstatt
ständig mit Mobilfunkmasten verbunden zu sein, kannst du im Flugmodus
über WLAN telefonieren und SMS versenden. Dies schützt dich vor der
kontinuierlichen Standortüberwachung durch Mobilfunkmasten.

- Gehe zum Aktivieren in die Einstellungen und wähle „Netzwerk &
  Internet“ aus.

- Wähle „SIM-Karten“ und dann deine gewünschte SIM-Karte.

- Scrolle bis zum Punkt „WLAN-Telefonie“.

- Aktiviere „WLAN-Telefonie verwenden“ und stelle bei „Bevorzugte
  Anrufeinstellung“ auf „Anruf über WLAN“ um.

Jetzt kannst du über WLAN telefonieren und SMS empfangen, ohne auf
Mobilfunkmasten angewiesen zu sein. Der Flugmodus sorgt nicht nur für
mehr Privatsphäre, sondern schont auch den Akku, da das ständige Suchen
nach Mobilfunkmasten entfällt. Ich habe festgestellt, dass mein Akku im
Flugmodus zwei bis drei Tage hält, während er ohne diesen oft nur einen
Tag durchhält.

### VoIP

> VoIP (Voice over IP) funktioniert ähnlich wie WiFi Calling, jedoch ist
> hierfür keine SIM-Karte erforderlich. Alle Anrufe und SMS werden über
> einen Anbieter abgewickelt und können über eine Open-Source-App
> verwaltet werden.
>
> Der Vorteil von VoIP im Vergleich zu WiFi Calling liegt in der
> größeren Flexibilität. Du kannst mehrere kostengünstige Rufnummern
> einrichten, ähnlich wie bei E-Mail-Adressen, sodass du für
> unterschiedliche Zwecke verschiedene Nummern nutzen kannst. Zudem ist
> es möglich, Anrufe direkt über den Computer zu empfangen, sodass das
> Handy ausgeschaltet bleiben kann.

VoIP bietet ein hohes Maß an Privatsphäre, richtet sich jedoch eher an
fortgeschrittene Nutzer. Da dies den Rahmen dieses Buches überschritte,
werde ich hier nicht weiter darauf eingehen.

## Faraday-Taschen

Früher war es einfach: Um sicherzustellen, dass das Handy weder zuhört
noch geortet werden kann, genügte es, die Batterie zu entfernen.
Heutzutage ist das bei den meisten Smartphones jedoch nicht mehr
möglich, da die Rückseite nicht mehr geöffnet werden kann. Flugmodus und
ähnliche Einstellungen versprechen zwar, die Verbindung zu kappen, doch
letztlich handelt es sich dabei um Softwarelösungen.

Daher kann man nie zu 100 % sicher sein, dass das Gerät keine Daten
sendet oder empfängt. Hier kommen Faraday-Taschen ins Spiel. Diese
speziellen Taschen, benannt nach dem Wissenschaftler Michael Faraday,
blockieren alle elektromagnetischen Wellen, sodass keine Signale hinein-
oder hinausgelangen.

Das bedeutet: Du kannst dein Handy bei dir tragen, ohne befürchten zu
müssen, getrackt zu werden. Zudem schützt du dich auch unterwegs oder zu
Hause vor den potenziell schädlichen Strahlungen des Geräts.

Es gibt viele Anbieter von Faraday-Taschen in unterschiedlichen Designs
und Größen. Allerdings solltest du sicherstellen, dass die Tasche auch
tatsächlich funktioniert. Ich habe selbst schon Taschen gehabt, die
Signale durchgelassen haben. Daher ist es ratsam, regelmäßig zu testen,
ob deine Tasche ihren Zweck erfüllt.

Die einfachste Testmethode: Stecke dein Handy in die Faraday-Tasche und
versuche dann, es mit einem anderen Gerät anzurufen. Diese Methode hat
jedoch ihre Tücken: Geht der Anruf durch, funktioniert die Tasche
definitiv nicht. Wenn der Anruf jedoch nicht durchkommt, könnte das auch
an anderen Faktoren wie dem Mobilfunknetz oder deinem Standort liegen.

Eine bessere Testmethode besteht darin, zu überprüfen, ob die Tasche
Bluetooth-Signale blockiert. Bluetooth ist stabiler und weniger
fehleranfällig. Verbinde dein Handy mit einem Bluetooth-Lautsprecher,
starte die Musik und stecke das Handy in die Faraday-Tasche. Stoppt die
Musik, war der Test erfolgreich. Läuft die Musik weiter, blockiert die
Tasche nicht richtig und sollte nicht verwendet werden.

## Mikrofon und Kamera

Viele Apps verlangen Zugriff auf Mikrofon und Kamera, oft um ihre
Funktionen überhaupt anbieten zu können. Leider nutzen viele von ihnen
diese Berechtigungen auch, um Daten zu sammeln – beispielsweise für
personalisierte Werbung. Zudem besteht immer das Risiko, dass Malware
auf das Gerät gelangt und uns überwacht. Früher war es noch möglich, die
Hardware selbst zu deaktivieren. Heute ist das, wie bereits erwähnt,
leider nicht mehr möglich. Auf Geräten mit GrapheneOS kannst du Mikrofon
und Kamera zwar auf Softwareebene blockieren, was besser ist als nichts,
aber Software allein ist nie zu 100 % sicher. Daher empfehle ich, so
weit wie möglich eine physische Deaktivierung vorzunehmen.

Die Kamera lässt sich relativ einfach absichern: Klebe einfach alle
Kameras mit undurchsichtigen Stickern ab. Wenn du die Kamera dann doch
einmal brauchst, kannst du die Abdeckung problemlos abnehmen und später
wieder anbringen.

Beim Mikrofon gestaltet sich die Absicherung komplizierter. Früher
reichte es, Mikrofone abzudecken, um Tonaufnahmen zu stören. Moderne
Smartphones verfügen jedoch über mehrere Mikrofone an verschiedenen
Stellen, sodass diese Methode nicht mehr effektiv ist. Doch genau dies
können wir uns zunutze machen: Wenn das Smartphone erkennt, dass ein
Mikrofon (z. B. der Kopfhörer) angeschlossen ist, nutzt es nur dieses.
Funktioniert das angeschlossene Mikrofon nicht, kann das Handy keine
Aufnahmen machen. Mikrofon-Blocker nutzen dieses Prinzip. Diese kleinen
Geräte täuschen vor, ein Mikrofon zu sein, funktionieren jedoch nicht.
Sie sorgen dafür, dass das Handy keine Aufnahmen machen kann.
Mikrofon-Blocker sind für USB-C-, Lightning- und AUX-Anschlüsse
erhältlich, sodass sie mit fast jedem Gerät kompatibel sind.

Perfekt sind diese Blocker allerdings nicht. Sollte Malware auf dein
Gerät gelangen und alle Mikrofone nutzen, hilft der Blocker nicht. Daher
habe ich zusätzlich auf Softwareebene alle Mikrofone deaktiviert und
verwende den Blocker – so minimiere ich das Risiko.

<span id="_Toc196572873" class="anchor"></span>Abbildung 10 Kamera- und
Mikrofonblocker

Viele von uns möchten sich vor der Überwachung durch Unternehmen und den
Staat schützen, übersehen jedoch oft, dass auch fremde Blicke auf
unseren Bildschirm ein ernstzunehmendes Problem darstellen können. In
öffentlichen Verkehrsmitteln, Cafés oder anderen Orten kommt es häufig
vor, dass Passanten unbewusst einen flüchtigen Blick auf das Handy ihres
Nachbarn werfen. Dabei können sensible Informationen wie Nachrichten,
Passwörter oder Codes mitgelesen werden. Auch wenn dies meist unbewusst
geschieht – unser Gehirn ist ständig auf der Suche nach neuen Reizen.
Wir sollten uns trotzdem aktiv davor schützen.
Privacy-Displayschutzfolien sind hierfür eine ideale Lösung. Diese
Folien werden auf den Bildschirm des Handys aufgebracht und stellen
sicher, dass nur der Benutzer, der direkt auf den Bildschirm schaut, den
Inhalt sehen kann. Aus seitlichem Blickwinkel erscheint der Bildschirm
lediglich als schwarze Fläche. Darüber hinaus bieten diese Folien auch
Schutz vor Kratzern und Stößen, sodass du deinen Bildschirm gleichzeitig
vor unerwünschten Blicken und Beschädigungen bewahrst – so schlägst du
zwei Fliegen mit einer Klappe.

## Handy-Nutzung

Alle zuvor beschriebenen Maßnahmen können deine Privatsphäre erheblich
optimieren, bringen jedoch wenig, wenn du dein Handy unachtsam nutzt.
Hier sind einige wichtige Punkte, auf die du achten solltest:

**WLAN und Bluetooth:** Viele Menschen lassen WLAN und Bluetooth ständig
aktiviert, weil es bequem ist, sich automatisch mit dem Heimnetzwerk
oder dem Auto zu verbinden. Allerdings verbindet sich das Handy nicht
nur mit diesen Netzwerken. Es sendet ständig Daten an WLAN-Netze in der
Umgebung, um mögliche Verbindungen zu prüfen.

Einkaufszentren und Geschäfte nutzen dies, um die Bewegungen von Kunden
zu verfolgen und analysieren. Über öffentliche WLANs kann auch
Unternehmen und Insitutionen darauf zugreifen, um Analysen
durchzuführen. Daher: Schalte WLAN und Bluetooth immer aus, wenn du sie
nicht benötigst. Aktiviere am besten auch den Flugmodus, wenn möglich.

**Flugmodus:** Der Flugmodus blockiert alle Signale zu Mobilfunkmasten.
Dies ist bei allen Smartphones weltweit möglich. Auch wenn diese
Blockierung nur auf Softwareebene erfolgt, hilft sie enorm, um dich vor
dem Tracking durch Mobilfunkanbieter zu schützen. Ich habe den Flugmodus
zu Hause fast immer aktiviert (ich nutze stattdessen WLAN für Anrufe)
und schalte ihn nur selten unterwegs aus, wenn ich Nachrichten lesen
oder kommunizieren möchte.

**Apps:** Wie bereits erwähnt, solltest du dein Handy insgesamt weniger
nutzen. Smartphones sind die am stärksten getrackten Geräte, und eine
vollständige Vermeidung von Tracking ist kaum möglich. Der beste Schutz
besteht darin, sie weniger zu nutzen und dem Tracking keine Gelegenheit
zu geben.

**Accounts:** Ein großer Vorteil von GrapheneOS besteht darin, dass du
keinen Account benötigst, um das Handy vollumfänglich zu nutzen. Das
bedeutet, dass deine Daten nicht mehr einem zentralen Google- oder
Apple-Konto zugeordnet werden. Nutze diese Freiheit und verknüpfe dein
Handy niemals mit einem persönlichen Google- oder Apple-Konto.

•   •   •

In diesem Kapitel haben wir ein sicheres und privates Handy
eingerichtet. Wir können jetzt alle Funktionen und Apps nutzen, ohne uns
jemals mit einem Google- oder Apple-Konto verbinden zu müssen. Auch
unser Betriebssystem sammelt keine Daten mehr über und gibt auch keine
mehr weiter. Mit WiFi Calling können wir den Flugmodus dauerhaft
aktivieren, wenn wir zu Hause sind, sodass auch die Mobilfunkmasten
keine Informationen über uns erfassen. Zudem haben wir die Möglichkeit,
sowohl softwareseitig als auch physisch das Mikrofon zu deaktivieren,
Kameras auszuschalten und alle Signale zu blockieren. Jetzt sind wir
bereit, im nächsten Kapitel zu entdecken, welche Apps wir benötigen, um
das Beste aus unseren Geräten herauszuholen und dennoch gleichzeitig
unsere Privatsphäre zu schützen.
