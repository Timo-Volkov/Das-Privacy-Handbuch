# Kapitel 3 Anonym surfen

„Wenn Privatsphäre zu einer knappen Ressource wird, wird die Überwachung
zur Macht.“ *~ Shoshana Zuboff*

Nachdem wir nun ein sicheres und privates Handy sowie einen geschützten
Computer eingerichtet haben, sind wir bereits zwei wesentliche Schritte
in Richtung Privatsphäre und Sicherheit gegangen. Um uns jedoch effektiv
vor staatlicher Überwachung, Datensammlern und unerwünschtem Zugriff zu
schützen, gibt es noch viel mehr zu beachten. Die nächsten Kapitel
bieten eine detaillierte Anleitung, wie wir sicher und privat im
Internet unterwegs sein und uns von Google sowie anderen Datenkraken
lösen können. Diese Kapitel verdienen es deswegen, mehrfach
durchgearbeitet zu werden.

Ich stelle hier verschiedene Tools und Softwarelösungen vor, von denen
die meisten kostenfrei sind. Diese Empfehlungen sind jedoch nicht als
endgültige Vorgaben zu verstehen – jeder sollte nach eigener Recherche
entscheiden, welches Programm am besten den eigenen Anforderungen
entspricht. Wichtig ist, dass die grundlegenden Prinzipien qualitativ
hochwertiger Programme beachtet werden.

| Open Source |
|----|
| Viele dieser Programme sind Open Source, was bedeutet, dass sie nicht von großen Unternehmen unterstützt werden, sondern meist freiwillig von Entwicklern aus der ganzen Welt betreut werden. Dies ist ein positiver Aspekt, da Open-Source-Software tendenziell transparenter ist und weniger kommerziellen Interessen unterliegt. |

Da diese Entwickler oft nicht durch Sponsoren gefördert werden und auf
Einnahmequellen wie den Verkauf von Daten oder Werbung verzichten, ist
es sinnvoll, sie durch Spenden zu unterstützen. Damit fördern wir nicht
nur das Entwicklerteam, sondern auch die gesamte Privacy-Bewegung, die
auf solche finanzielle Unterstützung angewiesen ist. Wenn dir ein
Programm gefällt, du es nutzt und es kostenfrei ist, spende bitte an das
Entwicklerteam. Links zu den Spendenseiten findest du auf
privatopia.de/open-source-spenden.

## Was macht ein gutes Programm aus?

Jeder hat individuelle Anforderungen an die Programme, die auf dem
Computer oder Handy genutzt werden. Es ist unmöglich, auf alle
Bedürfnisse einzugehen und für jedes Szenario eine Empfehlung
auszusprechen. Daher ist es wichtiger, die Kriterien zu verstehen, die
ein Programm erfüllen sollte, um Privatsphäre und Sicherheit zu
gewährleisten.

Grundsätzlich sollten wir, wenn möglich, auf die Installation von Apps
verzichten, sofern eine Webseite die gewünschten Funktionen bietet. Im
nächsten Schritt richten wir einen sicheren und privaten Browser ein,
der uns eine relativ hohe Sicherheit vor Tracking und Datensammlung
durch Unternehmen bietet.

Wenn jedoch eine Anwendung heruntergeladen wird, sei es auf das Handy
oder den Computer, erhält dieses Programm umfangreiche Rechte und
Zugriff auf zahlreiche Daten. Daher sollten wir immer die Webseite
bevorzugen, wenn diese die gleichen Funktionen bietet.

Es gibt beispielsweise keinen offensichtlichen Vorteil, Spotify als
Anwendung zu nutzen, wenn es auch über den Browser funktioniert. Es gibt
einige Kriterien, auf die man achten sollte bei der Auswahl eines
Programms für unsere Privatsphäre.

**Open Source:** Der Quellcode sollte öffentlich zugänglich sein. Dies
ist eines der wichtigsten Kriterien, da viele Menschen den Code auf
Schwachstellen, Probleme und versteckte Tracking-Software überprüfen
können. Selbst wenn wir den Code nicht vollständig verstehen, sorgt die
Gemeinschaft für die notwendige Kontrolle und Transparenz.

**Unternehmen:** Wer steht hinter dem Produkt, und welche Philosophie
verfolgt dieses Unternehmen? Handelt es sich um ein Unternehmen wie
Google, dessen Hauptgeschäft das Sammeln von Daten und Werbung ist, oder
um ProtonMail, das sich auf Datenschutz spezialisiert hat? Die
Unternehmensethik spielt eine entscheidende Rolle.

**Geschäftsmodell:** Wie finanziert sich das Unternehmen? Wenn Werbung
die Hauptquelle der Einnahmen ist, steigt das Risiko, dass Daten
gesammelt werden, um gezielte Werbung effektiver zu gestalten.
Idealerweise sollte sich das Produkt durch direkte Zahlungen der Nutzer
finanzieren.

**Erfahrungen und Vertrauenswürdigkeit:** Programme, die bereits länger
existieren, bieten mehr Sicherheit, da Schwachstellen eher entdeckt und
behoben werden konnten. Ein Programm, das zwar Open Source ist, aber
erst seit Kurzem existiert, ist möglicherweise noch nicht lange genug
auf dem Markt, um umfassend geprüft zu werden.

**Standort des Unternehmens:** Wo ist das Unternehmen ansässig? Befindet
es sich in den USA oder der EU, wo Regierungen und Gerichte über
umfangreiche Zugriffsrechte auf Daten verfügen? Oder hat es seinen Sitz
in einem Land, das neutral ist oder sogar in Gegensatz zu westlichen
Regierungen steht, wie die Schweiz, Russland oder ein südamerikanisches
Land? Dies könnte den Schutz der Daten vor staatlichem Zugriff erhöhen.

**Nutzerkontrolle über Daten:** Haben wir die Möglichkeit, selbst zu
entscheiden, welche Daten geteilt werden und welche nicht?
Beispielsweise bietet Apple viele Einstellungen, die es ermöglichen,
wichtige Aspekte der Privatsphäre zu kontrollieren, während Windows von
Microsoft in dieser Hinsicht kaum Wahlmöglichkeiten lässt.

Wenn du diese Punkte beachtest, kannst du selbst überprüfen, ob das
gewünschte Programm deine Privatsphäre schützt oder eher von deinen
Daten profitiert.

In diesem Kapitel schauen wir uns an, wie wir sicher und privat im
Internet surfen können. Dazu richten wir gleich einen sicheren Browser
ein und kümmern uns anschließend um eine sichere und private Verbindung
durch ein VPN und ein DNS. Am Ende dieses Kapitels kannst du dann
bedenkenlos im Internet surfen, ohne Werbung und ohne Tracking.

## Webbrowser LibreWolf

Bevor du mit dem Surfen im Internet beginnst oder Software installierst,
ist es wichtig, einen sicheren Browser zu verwenden. Ich empfehle dir
den LibreWolf-Webbrowser, den ich selbst jederzeit nutze.

LibreWolf ist ein sogenannter Fork von Firefox. Das bedeutet einfach
nur, dass ein Entwicklerteam den Code von Firefox genommen, ihn ein
wenig modifiziert und dann unter einem anderen Namen veröffentlicht hat.
Das ist bei Open-Source-Programmen üblich und passiert ziemlich oft.

Im ersten Entwurf des vorliegenden Buches hatte ich den Firefox Browser
direkt empfohlen – mit angepassten Einstellungen für maximale Sicherheit
und Privatsphäre.

Jedoch hat Firefox im Februar 2025 seine Nutzungsbedingungen geändert –
zum Nachteil der Nutzer. Konkret ging es um eine Klausel, die Mozilla
eine „nicht-exklusive, gebührenfreie, weltweite Lizenz“ zur Nutzung von
Daten einräumte, die Nutzer in Firefox eingeben oder hochladen. Zwar
würden laut Mozilla Firefox diese Daten nur für die Verbesserung von
Firefox genutzt und die Klausel sei schlecht formuliert, das Vertrauen
ist damit jedoch trotzdem in gewisser Weise gebrochen. Deswegen empfehle
ich den LibreWolf-Browser, der genauso wie der Firefox-Browser aufgebaut
ist, nur ohne diese Klausel und von Anfang an mit optimalen
Einstellungen zum Schutz von Privatsphäre und Sicherheit.

Die Frage nach dem richtigen Browser nehmen manche sehr persönlich und
man liest und hört ziemlich viele Empfehlungen im Internet dazu – ein
sehr häufig empfohlener Browser neben LibreWolf (Firefox) ist der Brave
Browser.

Der Brave Browser verfügt über eine Menge Features und Optionen für
Privatsphäre und Sicherheit – es gibt einen integrierten Werbeblocker,
Schutz vor Tracking und vieles mehr. Der einzige Nachteil besteht darin,
dass dieser auf Google Chrome aufbaut. Zwar hat man auch hier so gut wie
möglich alle Tracker und Verbindungen zu Google entfernt, die Grundbasis
bleibt jedoch trotzdem bei Google. Das ist aber nicht sehr gravierend,
du kannst also durchaus den Brave Browser verwenden, wenn du diesen
bevorzugst. Denn ein Vorteil ist sicherlich der, dass die Bedienung sehr
derjenigen des Google-Chrome-Browsers ähnelt. Vorliegendes Buch
fokussiert sich allerdings auf den LibreWolf-Browser, da dieser Firefox
als Basis hat und wirklich überhaupt keine Verbindungen zu Google
aufweist.

Bei allen Betriebssystemen ist ein Browser bereits vorinstalliert. Bei
Linux ist es Firefox, bei Apple Safari und bei Windows Edge. Safari und
Edge sind Teil des jeweiligen Ökosystems und tragen dazu bei, dass
Unternehmen ein noch genaueres Profil von dir erstellen können –
deswegen rate ich von deren Verwendung ab.

- Um LibreWolf zu installieren, rufe die Webseite
  librewolf.net/installation auf und installiere LibreWolf auf deinem
  Betriebssystem.

- Nach der Installation von LibreWolf solltest du dann alle
  Verknüpfungen und Referenzen zu Edge, Safari oder Firefox entfernen,
  um nicht versehentlich den „falschen“ Browser zu öffnen.

- LibreWolf ist von Grund auf sehr hinsichtlich Privatsphäre und
  Sicherheit optimiert, weswegen man hier Einstellungen nur noch minimal
  ändern muss. Klicke oben rechts auf das Menü (drei Striche) und wähle
  dort den Punkt „Einstellungen“ aus.

- Aktiviere unter „Allgemein den Punkt „Tab-Umgebungen aktivieren“.
  Klicke rechts auf „Einstellungen“ und aktiviere unten das Häkchen
  (dazu gleich mehr).

- Deaktiviere die Optionen „Erweiterungen während des Surfens empfehlen“
  und „Funktionen während des Surfens empfehlen“, indem du die Häkchen
  entfernst.

- Wähle im Menü links „Startseite“. Und setzte bei „Startseite und neue
  Fenster“ sowie „Neue Tabs“ die Option auf „Leere Seite“.

- Deaktiviere alle Inhalte der Startseite.

- Wähle im Menü links „Suche“. Hier ist DuckDuckGo als
  Standartsuchmaschine festgelegt, diese kannst du nun ändern, falls du
  eine andere möchtest.

- Lege „DuckDuckGo“ als Standard-Suchmaschine fest.

- Deaktiviere alle Optionen unter „Suchvorschläge“ und „Adressleiste“,
  um zu verhindern, dass Anfragen direkt an Google weitergeleitet werden
  und um die Google-API für Suchvorschläge zu blockieren.

- Wähle im Menü links „Datenschutz & Sicherheit“:

- Aktiviere den Haken unter „Datenschutzeinstellungen für Websites“.

- Setzte ein Häkchen bei „Cookies und Website-Daten beim Beenden
  löschen“ (dies bewirkt, dass alle gespeicherten Daten beim Schließen
  von LibreWolf gelöscht werden; Ausnahmen kannst du unter „Ausnahmen
  verwalten“ hinzufügen, z. B. für proton.me, um eine erneute Anmeldung
  bei E-Mails zu vermeiden).

- Deaktiviere alle Optionen unter „Passwörter“ und „Automatisch
  ausfüllen“.

- Unter „Chronik“ deaktiviere alles außer „Die Chronik löschen, wenn
  Firefox geschlossen wird“.

- Aktiviere den „Nur-HTTPS-Modus in allen Fenstern“.

LibreWolf bietet bereits von Haus aus ein hohes Maß an Sicherheit und
Privatsphäre. Im nächsten Abschnitt präsentiere ich
Browser-Erweiterungen, die zusätzlichen Schutz und Komfort bieten.

### uBlock Origin

Das erste unverzichtbare Add-on, das ich auf jedem Computer installiere,
ist uBlock Origin. Dieses Tool blockiert nicht nur Werbung, sondern auch
zahlreiche Tracking-Skripte sowie andere potenziell schädliche Software.
Es schützt dich effektiv vor Tracking, bösartigem Code und dem Senden
von Standortdaten sowie vor vielen weiteren Prozessen, die deine
Privatsphäre und Sicherheit gefährden könnten. uBlock Origin ist
kostenlos, vollständig Open Source und bietet umfangreiche
Anpassungsmöglichkeiten. Bereits mit den Standardeinstellungen
gewährleistet es ein hohes Maß an Privatsphäre und Sicherheit. Es ist
zwar möglich, erweiterte Funktionen zu deaktivieren, jedoch kann dies
dazu führen, dass bestimmte Webseiten nicht mehr korrekt funktionieren.

Das gute bei LibreWolf ist, dass uBlockOrigin von Anfang an installiert
ist, das heißt, du musst hier keine weiteren Einstellungen vornehmen.

### Container Tabs

Ein weiteres unverzichtbares Plugin, das täglich nutzen solltest, ist
Multi-Account Containers. Auch dieses Plugin ist LibreWolf von Anfang an
installiert bei. Dieses Plugin ermöglicht es dir, Tabs im Browser zu
isolieren, ohne den Browser neu starten oder alle Daten löschen zu
müssen. Aber warum ist das wichtig?

Jedes Mal, wenn du eine Webseite öffnest und dich möglicherweise
anmeldest, werden Daten gespeichert – häufig in Form von Cookies. Selbst
wenn du alle Cookies ablehnst, sammeln Webseiten dennoch eine Vielzahl
von Informationen.

Das größte Problem dabei ist, dass verschiedene Webseiten diese Daten
untereinander austauschen, um dir gezielte Werbung anzuzeigen. So kann
es beispielsweise passieren, dass du auf Facebook Werbung für
Kaffeemaschinen siehst, nachdem du bei Amazon nach Kaffeemaschinen
gesucht hast, ohne das es irgendeine Verbindung zwischen den Accounts
gibt.

Multi-Account Containers löst dieses Problem, indem es dir ermöglicht,
unterschiedliche Tab-Umgebungen zu erstellen, die nicht miteinander
kommunizieren. So kannst du im „Shopping“-Tab nach Kaffeemaschinen
suchen, ohne dass der im „SocialMedia-Container“ geöffnete Facebook-Tab
davon Kenntnis erhält.

Dazu erlaubt dir das Plugin, verschiedene Konten in unterschiedlichen
Containern gleichzeitig zu verwenden. So können z.B. die Anmeldedaten
von Twitter-Account #1 im Container #1 gespeichert werden, während die
Daten von Twitter-Account #2 in Container #2 abgelegt werden. Dies
ermöglicht es dir, mit zwei Twitter-Tabs parallel zu arbeiten, ohne dich
jedes Mal neu anmelden zu müssen.

Immer wenn du einen neuen Tab öffnen möchtest, wirst du gefragt, welche
Umgebung du öffnen möchtest. Die Standardauswahl enthält Container wie
Freizeit oder Arbeit, kann aber individuell angepasst werden. Ich selbst
verwende zehn Tabs, die von 01 bis 10 nummeriert sind. In den
Einstellungen unter „Allgemein“ und „Tab-Umgebungen aktivieren“ kannst
du neue Container-Tabs erstellen, bearbeiten oder löschen.

### Yandex

Nachdem wir nun einen sicheren Browser eingerichtet haben und DuckDuckGo
als Suchmaschine verwenden, möchte ich dir eine weitere Option
vorstellen: Yandex. Bei der Erwähnung von Yandex, oft als das „russische
Google“ bezeichnet, denken viele möglicherweise sofort an potenzielle
Risiken und schrecken zurück. Doch Yandex bietet einige interessante
Vorteile – insbesondere, weil es in Russland ansässig ist. Im Gegensatz
zu DuckDuckGo, das in den USA beheimatet ist, eröffnet Yandex den Zugang
zu einer völlig anderen Informationswelt: Es zeigt Suchergebnisse an,
die auf anderen Plattformen oft nicht zu finden sind.

Wie steht es jedoch um den Schutz der Privatsphäre bei Yandex? Yandex
schützt unsere Privatsphäre nicht. Ähnlich wie Google und Meta sammelt
auch Yandex Nutzerdaten und gibt diese weiter. Der Unterschied besteht
jedoch darin, dass Yandex die Daten nicht mit westlichen Regierungen
oder Geheimdiensten teilt, sondern mit russischen. In bestimmten
Situationen kann dies ein akzeptabler Kompromiss sein, da eigene
Regierungen unter Umständen mehr Schaden anrichten können als eine
externe wie die russische. Zudem ist es wahrscheinlich, dass Yandex auf
Anfragen westlicher Behörden nicht reagieren wird.

Dennoch würde ich nicht empfehlen, Yandex als tägliche Suchmaschine zu
verwenden. Es kann jedoch sinnvoll sein, Yandex als zusätzliches
Werkzeug zu nutzen, um Suchergebnisse zu finden, die andernorts
möglicherweise blockiert sind.

### Cookies

Cookies sind kleine Dateien, die auf deinem Gerät gespeichert werden,
während du im Internet surfst. Sie sammeln Informationen über die
besuchten Webseiten und deine Vorlieben und können ein digitales Profil
von dir erstellen. Man könnte sie als einen Fingerabdruck betrachten,
den du im Netz hinterlässt. Einerseits speichern Cookies nützliche Daten
wie deine Anmeldedaten, sodass du dich nicht ständig neu anmelden musst.
Andererseits ermöglichen sie es Webseiten, deine Surfgewohnheiten zu
verfolgen und gezielte Werbung anzuzeigen.

Um deine Privatsphäre besser zu schützen, gibt es seitens der EU eine
Regelung, die Webseiten verpflichtet, dich über die Verwendung von
Cookies zu informieren. Allerdings ist diese Maßnahme oft weniger
effektiv als erhofft. Viele Nutzer akzeptieren die Cookies einfach, ohne
darüber nachzudenken. Selbst wenn man Cookies ablehnt, gibt es häufig
„essenzielle“ Cookies, die dennoch Daten sammeln.

Um zu verhindern, dass diese Informationen dauerhaft auf deinen Geräten
gespeichert bleiben, empfehle ich, den Browser auf deinem Handy
(DuckDuckGo) und deinem PC (Librewolf) so einzustellen, dass alle
Cookies beim Schließen automatisch gelöscht werden. Falls du dies nicht
bereits getan hast, ist es sinnvoll, regelmäßig manuell die Cookies zu
löschen. So verhinderst du, dass Webseiten langfristig detaillierte
Profile über dich erstellen können.

## Tor-Browser

Viele haben sicherlich schon vom „Darknet“ gehört, das oft mit dem
Schutz der Privatsphäre und Anonymität in Verbindung gebracht wird. Der
Tor-Browser ist ein hervorragendes Tool für unsere Privatsphäre, auch
wenn er einige Einschränkungen mit sich bringt. Besonders beliebt ist er
bei politischen Aktivisten und Journalisten, die sich vor Überwachung
durch autoritäre Regierungen schützen möchten. Generell nutzen ihn
Menschen, die Zensur umgehen oder ihre Privatsphäre wahren wollen.

Um zu verstehen, wie der Tor-Browser funktioniert, schauen wir uns
zunächst an, was er eigentlich ist. Der Tor-Browser leitet automatisch
alle Anfragen durch das anonyme Tor-Netzwerk, das aus verschiedenen
Knotenpunkten weltweit besteht – ähnlich dem Netzwerk von Bitcoin. Der
Browser isoliert jede geöffnete Webseite, sodass kein Austausch von
Cookies oder anderen Informationen zwischen gleichzeitig geöffneten
Seiten möglich ist. Beim Schließen des Tor-Browsers werden alle Daten
automatisch gelöscht. Darüber hinaus ermöglicht der Tor-Browser den
Zugriff auf „Onion-Webseiten“, die nur über Tor erreichbar sind und als
Teil des sogenannten „Darkweb“ gelten.

Im Kern ist der Tor-Browser eine angepasste Version von Mozilla Firefox,
ähnlich zu LibreWolf. Er basiert auf einem speziellen Sicherheitssystem,
das ursprünglich von der US Navy entwickelt wurde, um ihre Kommunikation
zu schützen. Alle Daten, die über den Tor-Browser gesendet werden, sind
verschlüsselt und werden mehrfach über das sogenannte
„Onion-Router-Netzwerk“ aus Knotenpunkten geleitet, das aus Tausenden
von freiwillig zur Verfügung gestellten Servern besteht. Diese
Verschlüsselung und die Weiterleitung der Browserdaten sorgen dafür,
dass niemand herausfinden kann, welche Webseiten besucht werden oder
welche Aktivitäten dort stattfinden.

Ein weiterer Vorteil ist, dass alle Nutzer gleich aussehen, was eine
Identifikation praktisch unmöglich macht. Das Einzige, was erkennbar
ist, ist die Nutzung des Tor-Browsers. Zwischen unserem Computer und den
Webseiten, die wir besuchen, liegen also mehrere Knotenpunkte. Um auch
diesen nicht vertrauen zu müssen, verwendet Tor die „Onion-Strategie“.
Dabei „schält“ jeder Knotenpunkt eine Schicht der Verschlüsselung ab,
die nur den nächsten Knotenpunkt enthüllt. Wenn die letzte Schicht des
Datenpakets erreicht wird, haben wir die Webseite erreicht. Dadurch
bleibt der Absender anonym, da jeder Knotenpunkt nur seinen Vorgänger
und den Nachfolger kennt—dies wird auch als „Forward Privacy“
bezeichnet.

Das Ganze klingt vielleicht etwas kompliziert und führt auch zu einer
Verlangsamung der Internetgeschwindigkeit, da alle Anfragen und Daten
erst durch die Knotenpunkte geleitet sowie mehrfach verschlüsselt und
entschlüsselt werden müssen. Daher ist die Geschwindigkeit eine der
größten Herausforderungen. Jede neue Seite, die geladen wird, und jede
Nutzeraktion, die wir normalerweise innerhalb von Millisekunden
erwarten, kann Sekunden bis Minuten dauern. Aus diesem Grund ist Tor
nicht als täglicher Browser geeignet.

Du solltest den Tor-Browser auch nicht ständig verwenden, da seine
Nutzung Aufmerksamkeit erregen kann—sowohl von deinem
Internetdienstanbieter (ISP-Internetserviceprovider) als auch von den
Webseiten selbst. Obwohl der ISP nicht sehen kann, welche Webseiten du
besucht hast, erkennt er die Nutzung des Tor-Browsers, was zu
verstärkter Überwachung führen kann. Um dies zu vermeiden, ist es
ratsam, vor der Nutzung des Tor-Browsers ein VPN zu verwenden. Auch
Webseiten erkennen den Zugriff über den Tor-Browser und assoziieren das
Tor-Netzwerk oft mit illegalen Aktivitäten. Das kann zu zusätzlichen
Sicherheitsabfragen wie Google Captchas, zur Sperrung von Konten oder
sogar zur Blockierung von Zahlungen führen. Deshalb solltest du den
Tor-Browser nicht als alltäglichen Browser verwenden, sondern nur in
bestimmten Situationen. Für den täglichen Gebrauch eignet sich LibreWolf
besser.

**Onion:** Wie bereits erwähnt, ermöglicht der Tor-Browser den Zugriff
auf „ .onion-Adressen“. Diese sind Webseiten, die nur im Darknet
vorhanden sind. Um diese Seiten zu besuchen, ist die Nutzung des
Tor-Browsers erforderlich.

**Reisen:** In einigen Ländern, in denen die Zensur strenger ist als in
Deutschland, kann der Tor-Browser besonders hilfreich sein. Russland
blockiert beispielsweise ProtonMail, und in anderen Ländern sind
Verbindungen über VPNs generell nicht erlaubt. In solchen Fällen kann
der Tor-Browser eine Lösung sein, um dennoch auf die gewünschten Seiten
zugreifen zu können.

**Öffentliche WLANs:** Auch in Deutschland gibt es viele Orte, an denen
der Zugriff auf bestimmte Webseiten eingeschränkt ist – z. B. bei
öffentlichen Netzwerken von Bibliotheken, Universitäten oder
Arbeitsplätzen. Hier bietet der Tor-Browser ebenfalls eine Möglichkeit,
diese Beschränkungen zu umgehen.

Um den Tor-Browser für Mac und Windows zu installieren, folge einfach
den Anweisungen auf www.torproject.org/download/.

Für Linux kannst du den Tor-Browser über das Terminal installieren,
indem du die entsprechenden Befehle eingibst.

> sudo add-apt-repository ppa:micahflee/ppa
>
> sudo apt update
>
> sudo apt install torbrowser-launcher

## VPN

VPNs (Virtual Private Networks) stellen ein bedeutendes Thema im
Internet dar, und viele Webseiten bieten Vergleiche an, um die besten
Dienste zu empfehlen – jedoch nur mit dem Ziel, Provisionen zu
verdienen. Viele VPN-Anbieter versprechen mehr, als sie tatsächlich
halten können. Bevor du dich von solchen Versprechungen blenden lässt,
ist es wichtig, zu verstehen, was ein VPN tatsächlich leistet.

Ein VPN ermöglicht eine sichere Verbindung zu einem anderen Netzwerk
über das Internet. Vereinfacht gesagt: Es verbindet dein Gerät (z. B.
Laptop) mit einem Server irgendwo auf der Welt und verbirgt somit deine
Internetaktivitäten.

Statt deines Geräts wird der VPN-Server als Absender im Internet
wahrgenommen. Wenn der Server sich in einem anderen Land befindet,
scheint es, als würdest du dich von dort aus verbinden. Der VPN-Server
fungiert also als Schutzschicht, die deine Online-Aktivitäten
verschleiert.

<span id="_Toc196572874" class="anchor"></span>Abbildung 11VPN

**Schutz in öffentlichen WLANs:** Ein VPN schützt deine Daten, wenn du
öffentliche WLANs nutzt. Ohne VPN könnte der Betreiber des WLANs sehen,
welche Webseiten du besuchst, was du herunterlädst und in einigen Fällen
sogar deine Passwörter abfangen.

**Privatsphäre im Heimnetzwerk:** Auch zu Hause kann dein
Internetanbieter (ISP = Internet Service Provider) nachvollziehen,
welche Seiten du besuchst. Viele ISP speichern diese Informationen, um
sie weiterzuverkaufen. Mit einem VPN sieht der ISP lediglich, dass du
einen VPN verwendest – deine genauen Aktivitäten bleiben jedoch
verschlüsselt.

**Zensur umgehen:** In Ländern mit strenger Internetzensur, wie China
nutzen viele Menschen VPNs, um gesperrte Webseiten zu erreichen. Auch in
anderen Ländern kannst du auf diese Weise blockierte Inhalte
freischalten.

**Anonymität:** Deine IP-Adresse wird durch die Nutzung eines VPNs
verschleiert. Diese Adresse verrät deinen ungefähren Standort und kann
Hinweise auf dein Suchverhalten geben. Ein VPN sorgt dafür, dass deine
IP-Adresse anonym bleibt.

**Schutz vor Tracking:** Webseiten können dich anhand deiner IP-Adresse
identifizieren und personalisierte Werbung schalten. Ein VPN verbirgt
deine IP, sodass Webseiten nur den VPN-Server sehen und du schwerer zu
tracken bist.

**Datenlecks:** Bei Datenlecks von Webseiten oder Unternehmen wird oft
auch die IP-Adresse der Nutzer veröffentlicht. Mit einem VPN bleibt
deine tatsächliche IP geschützt, da nur die des VPN-Servers bekannt
wird.

**Geografische Beschränkungen umgehen:** Mit einem VPN kannst du so tun,
als würdest du dich aus einem anderen Land verbinden, um auf Dienste
zuzugreifen, die nur in bestimmten Regionen verfügbar sind. Allerdings
wird dies zunehmend schwieriger, da die meisten Webseiten solche
Versuche blockieren (wie z.B. Netflix).

Du solltest ein ungefähres Bild davon haben, was ein VPN ist und warum
es sinnvoll ist, eines zu nutzen. Für jeden, dem Privatsphäre und
Sicherheit wichtig sind, ist ein VPN eine der besten ersten
Investitionen. Ohne VPN ist es viel einfacher, von Unternehmen, Staaten
oder anderen Parteien getrackt zu werden.

Nun stellt sich die Frage: Welcher VPN-Anbieter ist der richtige für
dich? Ähnlich wie bei Passwortmanagern gibt es viele VPN-Anbieter, und
es ist besser, irgendein VPN zu nutzen als gar keinen. Wenn du bereits
ein VPN hast, den du magst, bleibe gerne dabei. Falls nicht, kannst du
auch einen anderen Anbieter ausprobieren. Hier sind zwei VPN-Anbieter,
die ich dir ans Herz legen möchte.

### Mullvad VPN

Mullvad ist ein schwedischer Anbieter, der besonderen Wert auf
Privatsphäre und Anonymität legt. Bei der Anmeldung erhälst du eine
zufällig generierte Kontonummer – persönliche Daten oder E-Mail-Adressen
sind nicht erforderlich. Mullvad verfolgt eine strikte No-Logs-Politik
und speichert keine Nutzerdaten. Zudem bietet der Anbieter eine
transparente und einfache Preisstruktur ohne versteckte Gebühren.

Es ist zu beachten, dass Mullvad weniger Server als andere Anbieter hat,
was gelegentlich zu langsameren Verbindungen führen kann.

Kosten: 5 € pro Monat

Webseite: mullvad.net/de/vpn

### ProtonVPN

ProtonVPN wurde von den Entwicklern von ProtonMail ins Leben gerufen und
legt großen Wert auf Datenschutz. Der Dienst hat seinen Sitz in der
Schweiz, was bedeutet, dass er strengen Datenschutzgesetzen unterliegt.
ProtonVPN bietet zudem eine kostenlose Version ohne Datenlimit an,
jedoch mit einer eingeschränkten Serverauswahl und nur für ein einzelnes
Gerät.

Nutzer von ProtonMail, die Bedenken haben, all ihre Daten bei einem
Anbieter zu speichern, sollten in Erwägung ziehen, für ProtonVPN einen
separaten Account anzulegen.

Kosten: 3,99 € pro Monat bei einem Jahresvertrag

Webseite: [protonvpn.com](https://protonvpn.com)

Ein wesentlicher Aspekt beim Schutz deiner Privatsphäre ist die Wahl der
Zahlungsmethode für deinen VPN-Dienst. Kreditkartenzahlungen sind nicht
ideal, da dein Name direkt mit deinem VPN-Account verknüpft wird.

Eine bessere Option ist die Verwendung von Bitcoin oder einer anderen
anonymen Zahlungsmethode. Einige VPN-Anbieter wie ProtonVPN und Mullvad
akzeptieren sogar Barzahlungen per Post, was jedoch für die meisten
Nutzer umständlich sein könnte. Ich persönlich empfehle die anonyme
Zahlung mit Bitcoin oder Monero.

Wenn dir Privatsphäre und Anonymität wichtig sind, bieten diese beiden
VPN-Dienste solide Optionen, je nachdem, welche Anforderungen du an
Preis, Geschwindigkeit und Serververfügbarkeit hast. Ich nehme bewusst
keine Affiliate-Deals an, um VPNs aufgrund ihrer Eigenschaften und nicht
aus Profitinteresse zu empfehlen.

| Affiliate Deals |
|----|
| Durch einen Affiliate Deal bekommt die Person, die ein VPN empfiehlt, eine kleine Provision. Das führt dazu, dass VPNs nicht wegen ihrer guten Eigenschaften empfohlen werden, sondern es wird oft das VPN empfohlen, das die höchste Provision zahlt. |

## DNS

Das Domain Name System (DNS) ist ein Dienst, der benutzerfreundliche
Webadressen wie google.de in IP-Adressen übersetzt, die Computer
verstehen (z. B. wird google.de in 173.194.10.100 umgewandelt). Ohne DNS
müssten wir uns die IP-Adressen jeder Webseite merken, was kaum
praktikabel wäre.

Jedes Mal, wenn du eine neue Webseite aufrufst, fragt dein Gerät beim
DNS-Server nach der entsprechenden IP-Adresse, damit die Seite geladen
werden kann. Standardmäßig wird der DNS-Server deines Internetanbieters
verwendet, was jedoch einige Sicherheits- und Privatsphäreprobleme mit
sich bringt.

DNS-Anfragen sind häufig unverschlüsselt und enthalten zusätzliche
Metadaten. Das bedeutet, dass jeder, der Zugriff auf diese Daten hat –
sei es dein Internetanbieter, Hacker oder staatliche Stellen –
nachvollziehen kann, welche Seiten du besuchst, wann du sie besuchst und
von welchem Gerät aus. Deine Internetaktivitäten können somit leicht
überwacht werden, wenn du den Standard-DNS-Server nutzt. Daher ist es
ratsam, einen alternativen DNS-Anbieter in Betracht zu ziehen.

Wenn du ein VPN (Virtuelles privates Netzwerk) verwendest, leitet dieses
in der Regel alle DNS-Anfragen über seinen eigenen DNS-Server, was die
Sicherheit im Vergleich zum Standard-DNS erhöht. Es ist jedoch hier
wichtig, nicht alle Eier in einen Korb zu legen und dem VPN-Anbieter
nicht komplett blind zu vertrauen. Daher empfiehlt es sich, einen
unabhängigen DNS-Dienst zu nutzen und somit VPN und DNS voneinander zu
trennen.

### NextDNS

Ich empfehle NextDNS, da es einfach einzurichten ist, umfassenden Schutz
bietet und sich individuell anpassen lässt.

**Kosten:** Kostenlos für bis zu 300.000 DNS-Anfragen pro Monat (genug
für 99,9% der Benutzer), danach 20 € pro Jahr.

**Einfache Konfiguration:** NextDNS lässt sich schnell und unkompliziert
einrichten.

**Sicherheit und Privatsphäre:** NextDNS unterstützt Technologien wie
„DNS over TLS“ und „DNS over HTTPS“, die sichere DNS-Abfragen
gewährleisten.

**Zusätzliche Optionen:** Du kannst Filterlisten anwenden, Tracker und
Werbung blockieren sowie verschiedene Datenschutzeinstellungen
konfigurieren.

Es gibt zwei Möglichkeiten, NextDNS zu nutzen: Die erste Möglichkeit
besteht darin, einen öffentlichen NextDNS-Server zu verwenden, über den
deine DNS-Anfragen geleitet werden. Deine Anfragen werden dabei nicht
gespeichert und bleiben anonym. Alternativ kannst du ein eigenes Konto
bei NextDNS erstellen. Dadurch erhältst du vollen Zugriff auf eine
Vielzahl von Einstellungen, kannst Tracker blockieren und eigene
Filterlisten konfigurieren.

- Besuche dafür die Webseite auf my.nextdns.io/signup und erstelle dir
  einen Account. Verwende am besten einen E-Mail-Alias (Kapitel 5), um
  anonym zu bleiben.

- Gehe auf den Reiter „Datenschutz“ und füge die „NextDNS Ads & Trackers
  Blockliste“ hinzu. Diese Liste blockiert Werbung und Tracker direkt
  beim Laden der Seite.

- Gehe auf den Reiter „Installation“ und kopiere den Link unter
  „DNS-over-HTTPS“ (der Link sieht etwa aus wie folgt:
  https://dns.nextdns.io/abc123).

- Öffne die Einstellungen von LibreWolf und wähle „Datenschutz &
  Sicherheit“ aus.

- Scrolle bis zu „DNS über HTTPS“ und aktiviere „Maximaler Schutz“.

- Wähle bei „Anbieter auswählen“, „Benutzerdefiniert“ und füge den
  kopierten Link ein.

<span id="_Toc196572875" class="anchor"></span>Abbildung 12 NextDNS
Anfrage

Hier sind alle Anfragen aufgelistet, die in einem kurzen Zeitraum
abgerufen wurden. Dazu gehören die aktiven Suchen bei DuckDuckGo und der
Tagesschau, aber auch andere Webseiten und Tracker, die im Hintergrund
liefen und blockiert wurden.

Um nicht nur die DNS-Anfragen deines Browsers, sondern die aller Apps
über NextDNS zu leiten, kannst du den Dienst für das gesamte Gerät
einrichten.

- Gehe auf den Reiter „Installation“ auf der NextDNS-Seite und kopiere
  die beiden IP-Adressen unter „Verknüpfte IP“ und „DNS-Server“.

- Wenn du ein VPN nutzt, öffne die VPN-Einstellungen und trage die
  IP-Adressen unter „Custom DNS“ ein.

- Falls du kein VPN verwendest, öffne die Netzwerkeinstellungen deines
  Computers und füge die IP-Adressen manuell in den DNS-Bereich ein.
  Detaillierte Anleitungen findest du auf der NextDNS-Seite unter
  „Installation“.

- Führe einen Test durch, indem du eine App mit Internetzugang öffnest
  (z. B. StandartNotes) und überprüfe, ob die Anfragen bei NextDNS unter
  „Protokolle“ angezeigt werden.

Wenn alle Tests erfolgreich abgeschlossen sind und alle Anfragen über
NextDNS laufen, kann du sicherstellen, dass keine Daten gespeichert
werden. Deaktiviere dazu die Protokollierung bei NextDNS.

- Gehe auf den Reiter „Einstellungen“ und schalte unter „Protokolle“ die
  Option „Protokolle aktivieren“ aus.

## Öffentliche WLANs

Öffentliche WLAN-Netzwerke haben in der Privatsphäre-Community einen
schlechten Ruf – und das nicht ohne Grund. In der Vergangenheit gab es
ernstzunehmende Sicherheitsrisiken bei der Nutzung dieser Netzwerke, und
auch heute sind sie nicht völlig risikofrei.

Früher waren Netzwerke generell unsicherer, und öffentliche WLANs wiesen
besonders viele Schwachstellen auf. Oft waren sie gar nicht
verschlüsselt, was bedeutete, dass alle Daten, die zwischen dir und dem
Router übertragen wurden, ungeschützt waren. Jeder mit den passenden
Werkzeugen konnte diese Daten abfangen. Selbst als die ersten
Verschlüsselungsprotokolle eingeführt wurden, hatten sie viele
Sicherheitslücken, die von Hackern ausgenutzt wurden. Dadurch kam es
häufig zu sogenannten Man-in-the-Middle-Angriffen.

| Man-in-the-Middle-Angriff |
|----|
| Bei einem Man-in-the-Middle-Angriff, schaltet sich ein Hacker zwischen dich und den Router und leitet den gesamten Datenverkehr über sich selbst. So kann er sensible Informationen wie Logins oder private Nachrichten mitlesen und abgreifen. |

Zum Glück hat sich die Situation inzwischen verbessert. Die
Verschlüsselung von öffentlichen WLANs ist heute deutlich sicherer und
bietet ein ähnliches Sicherheitsniveau wie private WLANs zu Hause.
Außerdem nutzen die meisten Webseiten mittlerweile HTTPS. Das bedeutet,
dass der Datenverkehr zwischen deinem Browser und der Webseite
verschlüsselt ist, was das Risiko senkt, dass jemand deine Daten
abfängt.

Die Maßnahmen, die in diesem Buch vorgestellt werden, erhöhen deine
Sicherheit erheblich. Mit sicheren Passwörtern und der
Zwei-Faktor-Authentifizierung (Kapitel 4) wird der Schutz deiner Konten
stark verbessert. Zudem nutzt du ein eigenes DNS, wodurch der Anbieter
des öffentlichen WLANs nicht einmal mehr sehen kann, welche Webseiten du
besuchst. Die Verwendung eines VPNs verstärkt diesen Schutz noch weiter.
Deshalb sehe ich kein allzu großes Sicherheitsrisiko mehr bei der
Nutzung öffentlicher WLANs.

Vielleicht hast du, wenn du schon länger ein VPN verwendest,
festgestellt, dass es nicht immer problemlos funktioniert. Viele
Webseiten blockieren den Zugang über VPNs komplett. Andere setzen
endlose Captchas ein, die oft kaum lösbar sind. Manche Seiten verlangen
wiederholt E-Mail- oder SMS-Codes zur Verifizierung und verweigern am
Ende dennoch den Zugriff. Um unsere Sicherheit und Privatsphäre zu
gewährleisten, wollen wir diese Seiten natürlich nicht ohne VPN
besuchen. Hier kommen öffentliche WLANs ins Spiel. Wenn du von deinem
Heimnetzwerk aus auf eine Webseite zugreifst, wird deine IP-Adresse –
und damit dein ungefährer Standort – an die Seite übermittelt. Diese
IP-Adresse wird gespeichert und oft mit deinem Account verknüpft. Nutzt
du jedoch ein öffentliches WLAN, wird eine andere IP-Adresse verwendet –
nämlich die des öffentlichen Netzwerks. Diese wird zwar ebenfalls
gespeichert, zeigt aber lediglich auf das öffentliche WLAN. Wenn du also
auf eine Webseite zugreifen musst, die VPN-Verbindungen blockiert,
kannst du stattdessen öffentliche WLANs in Cafés, Hotels oder
Bibliotheken nutzen, um trotzdem deine Privatsphäre zu wahren.

•   •   •

In diesem Kapitel hast du nun einen sicheren und privaten Browser
eingerichtet, der deine Privatsphäre schützt. Dazu haben wir zwei
Erweiterungen, die diesen Schutz weiter erhöhen. Außerdem haben wir den
Tor-Browser eingerichtet, den du für sensible Angelegenheiten verwenden
kannst. Zusätzlich dazu haben wir ein VPN eingerichtet, das unsere
IP-Adresse vor den Webseiten und unsere Onlineaktivität vor unserem
Internetserviceprovider schützt. Um nicht dem VPN-Anbieter zu viel
Vertrauen zu schenken, haben wir NEXT DNS konfiguriert.

Jetzt bist du unabhängig vom DNS-Server deines Internetanbieters und
kannst sicher und anonym surfen. NextDNS speichert keine Anfragen und
hat nur Zugriff auf deine Alias-E-Mail-Adresse und die aufgerufenen
Webseiten. Selbst dein VPN-Anbieter kann nicht mehr sehen, welche
Webseiten du besuchst. Durch die Kombination von VPN und NextDNS
verbesserst du deine Sicherheit und Privatsphäre erheblich, da du das
Vertrauen auf mehrere Dienste verteilst und Überwachung sowie Tracking
minimierst. Im nächsten Kapitel werden wir uns ansehen, wie wir unsere
Onlineaktivität von den Passwörtern bis hin zur Verschlüsselung sichern
können.
