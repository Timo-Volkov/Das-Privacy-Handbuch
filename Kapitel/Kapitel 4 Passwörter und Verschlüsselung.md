# Kapitel 4 Passwörter und Verschlüsselung

„Jemand, der seine Daten schützen will, hat nichts zu verbergen. Er hat
etwas zu bewahren.“ *~ Max Schrems*

Konten und Passwörter sind aus unserer digitalen Welt nicht mehr
wegzudenken – nahezu jede Anwendung und jeder Online-Dienst verlangt
nach ihnen. Leider sind die meisten Passwörter, die von der breiten
Bevölkerung verwendet werden, nicht sicher genug, was das Risiko eines
Angriffs erheblich erhöht. Aus diesem Grund widme ich diesem Thema ein
ganzes Kapitel.

Darüber hinaus werden wir einen Blick auf Verschlüsselungen und Backups
werfen. Diese Themen werden oft ignoriert oder aufgeschoben, können
jedoch erhebliche Probleme verursachen, wenn man plötzlich ein Backup
benötigt.

## Sichere Passwörter

Bevor wir uns damit beschäftigen, einen Passwortmanager zu verwenden und
alle Passwörter zu ändern, ist es wichtig, zu verstehen, was ein
sicheres Passwort ausmacht und auf welche Punkte man bei der
Passwortauswahl achten muss.

Um diese Frage zu klären, sollten wir zunächst die Sicherheitsprobleme
betrachten und verstehen, wie Passwörter in die Hände von Hackern oder
unbefugten Dritten gelangen können. Der klassische Ansatz, um an ein
Passwort zu gelangen, ist die Brute-Force-Attacke. Dabei versucht ein
Computer in rasanter Geschwindigkeit, unzählige Passwortkombinationen
auszuprobieren, bis das richtige gefunden ist. Ein leistungsstarker
Computer kann dabei bis zu 10 Milliarden Passwörter pro Sekunde testen.
Um uns vor solchen Angriffen zu schützen, sind zwei Faktoren
entscheidend: die Länge des Passworts und die Vielfalt der verwendeten
Zeichen.

**Länge:** Jedes zusätzliche Zeichen, das wir einem Passwort hinzufügen,
erhöht die Dauer einer Brute-Force-Attacke exponentiell. Daher empfehle
ich eine Mindestlänge von 16 Zeichen.

**Variation:** Je mehr unterschiedliche Zeichenarten in unserem Passwort
enthalten sind, desto sicherer wird es. Statt allein Zahlen zu verwenden
(die nur 10 verschiedene Möglichkeiten pro Stelle bieten), sollte eine
Mischung aus Zahlen, Groß- und Kleinbuchstaben sowie Sonderzeichen
verwendet werden, die mehr als 90 verschiedene Möglichkeiten pro Stelle
bietet.

Eine weitere Möglichkeit, in einen Account einzudringen, besteht darin,
dass das Passwort bereits bekannt ist. Wenn du für alle deine Accounts
dasselbe Passwort verwendest und eines dieser Passwörter bei einem
Datenleck offengelegt wird, können Angreifer problemlos auch auf alle
anderen Accounts zugreifen. Daher ist es wichtig, für jeden Account ein
einzigartiges, noch nie verwendetes und nicht ähnliches Passwort zu
wählen.

Viele Menschen, die sich dieses Problems bewusst sind, verwenden für
jede Webseite ein ähnliches Passwort, das sie nur geringfügig abändern.
Diese Methode scheint zunächst praktisch, da sie leicht umzusetzen ist
und für jeden Account ein anderes Passwort bereitstellt. Allerdings ist
diese Vorgehensweise nicht optimal. Bei Datenlecks versuchen Angreifer
nicht nur, alle bekannten Passwörter für andere Accounts zu verwenden,
sondern setzen auch Algorithmen ein, um solche Variationen zu erkennen.
So können sie die Regel, nach der du deine Passwörter erstellst,
entschlüsseln und damit Zugang zu all deinen Accounts erlangen.

| Achtung: Ein schlechtes Beispiel |
|----|
| Wenn als Hauptpasswort „privacy!“ gewählt wird und für jede Webseite drei Zeichen angehängt werden, die von der jeweiligen Seite abhängen, z. B. „goo“ für Google oder „you“ für YouTube, entstehen Passwörter wie „privacy!you“ oder „privacy!goo“. Diese Methode ist jedoch schnell durchschaubar und daher unsicher. |

Die sichere Verwaltung der zahlreichen Passwörter, die wir heute
benötigen, ist nahezu unmöglich, wenn man sich auf das eigene Gedächtnis
verlässt. Die beste Möglichkeit hier ist ein Passwortmanager der sichere
Passwörter erstellt und diese dann sicher abspeichert. Solltest du bei
Passwortmanagern ein schlechtes Gefühl haben kannst du auch physisch du
alle Passwörter in einem analogen Notizbuch notieren (Ich empfehle eins
mit A-Z Sortierung zum einfachen Wiederfinden.) ­ für maximalen Schutz
sollte ein Passwortmanger jedoch die erste Wahl sein.

## Passwortmanager

Jedes Jahr gibt es Hunderte von Datenlecks, durch die Milliarden von
Passwörtern in die Hände von Hackern gelangen. Viele Menschen verwenden
dasselbe Passwort für verschiedene Konten oder haben ihre Passwörter
seit Jahren nicht geändert. Daher ist es ratsam, davon auszugehen, dass
alle deine Passwörter potenziell kompromittiert sind und aktualisiert
werden müssen. Der erste Schritt besteht darin, die wichtigsten Konten
zu identifizieren und sichere, einzigartige Passwörter für jedes
einzelne zu erstellen. Ein Passwortmanager ist hierfür die beste Lösung.

Man unterscheidet allgemein zwischen Online- und
Offline-Passwortmanagern. Bei Online-Managern werden die Daten
verschlüsselt auf Servern gespeichert, was den Vorteil bietet, dass du
von überall auf deine Passwörter zugreifen kannst.
Offline-Passwortmanager hingegen erfordern eine manuelle Synchronisation
zwischen den Geräten und regelmäßige Backups. Der Vorteil dieser
Variante liegt in der erhöhten Sicherheit, da die Passwörter
ausschließlich auf deinem eigenen Gerät gespeichert werden. Wenn du
diese Option bevorzugst, empfehle ich KeePassXC.

Es gibt viele Diskussionen darüber, welcher Passwortmanager der beste
ist, und ich möchte diese hier vermeiden. Ich präsentiere dir Bitwarden,
da es sich hervorragend für den Einstieger eignet. Natürlich steht es
dir frei, ein anderes Programm zu nutzen, wenn du bereits eines im
Einsatz hast oder ein anderes bevorzugst.

### Bitwarden

Bitwarden ist ein Open-Source-Online-Passwortmanager, der für alle
Betriebssysteme verfügbar ist. Die kostenlose Version bietet bereits für
die meisten Nutzer umfassende Funktionen, kann jedoch bei Bedarf durch
die kostenpflichtige Version für 10 € pro Jahr erweitert werden.
Bitwarden kannst du unter bitwarden.com/download/ installieren.

- Öffne die Anwendung und klicke unten in der Mitte auf „Create
  Account“.

- Gib deine E-Mail-Adresse ein (falls du noch keine sichere private
  E-Mail-Adresse habt, kannst du im Kapitel 5 nachschlagen) und lege ein
  Masterpasswort fest.

Das Masterpasswort fungiert als Schlüssel für den Zugriff auf den
Passwortmanager. Jeder, der dieses Passwort kennt, hat uneingeschränkten
Zugriff auf alle gespeicherten Passwörter – sofern keine
Zwei-Faktor-Authentifizierung (2FA) eingerichtet ist. Daher sollte das
Masterpasswort besonders sicher sein und aus mindestens 16 Zeichen
bestehen, wobei es noch nie zuvor verwendet worden sein darf. Sollte der
Zugriff auf dieses Passwort verloren gehen, ist auch der Zugang zu den
gespeicherten Passwörtern und damit zu den entsprechenden Konten nicht
mehr möglich. Es ist daher von größter Bedeutung, das Masterpasswort
sicher aufzubewahren.

- Du kannst optional einen Hinweis für das Masterpasswort hinterlassen,
  der bei Bedarf an die angegebene E-Mail-Adresse gesendet wird. Ich
  würde diese Funktion überspringen.

- Setzte das Häkchen bei den Nutzungsbedingungen („TOS“) und klicke auf
  „Submit“.

Der Passwortmanager ist nun einsatzbereit. Um den Zugriff auf die
Passwörter während des Surfens im Internet zu erleichtern, kann später
eine Browser-Erweiterung installiert werden. Als Nächstes erstellen wir
einen neuen Testeintrag um zu sehen wie der Passwortmanager funktioniert
und wie man neue Einträge zu Webseiten und Passwörtern erstellen kann.

- Gib auf der Anmeldeseite deine E-Mail-Adresse ein und klicke auf
  „Continue“. Optional kannst du das Häkchen bei „Remember E-Mail“
  setzen, um bei zukünftigen Anmeldungen nur noch das Passwort eingeben
  zu müssen.

- Gib dann dein Passwort ein und klicke auf „Log in with“.

- Um einen neuen Eintrag zu erstellen, klicke oben links auf „File“ und
  anschließend auf „New Login“.

- Bei „Name“ kannst du einen Namen für den Eintrag angeben, meistens
  eignet sich hier der Name der Webseite.

- Gebe bei „Username“ den Benutzernamen für die Anmeldung ein, häufig
  ist das die E-Mail-Adresse.

- Bei „Password“ wird das Passwort gespeichert. Da davon ausgegangen
  wird, dass bisherige Passwörter unsicher sind, sollte immer ein neues
  Passwort erstellt werden.

- Klicke dazu auf die zwei Pfeile, die im Kreis aufeinander zeigen,
  wodurch der Passwortgenerator geöffnet wird. Ein Passwort wird direkt
  vorgeschlagen, es lohnt sich jedoch, einige Anpassungen vorzunehmen,
  um die Sicherheit zu erhöhen.

- Durch Klicken auf „Options“ kannst du weitere Einstellungen vornehmen.

- Wähle bei „Length“ die Länge auf 20 Zeichen fest.

- Setzte das Häkchen für Sonderzeichen.

- Gebe unten bei „Minimum numbers“ und „Minimum special“ jeweils „3“
  ein, um sicherzustellen, dass mindestens drei Zahlen und drei
  Sonderzeichen im generierten Passwort enthalten sind.

- Bestätige die Auswahl mit dem Haken unten links, und schon ist ein
  neues sicheres Passwort für den Account erstellt.

- Weiter unten besteht die Möglichkeit, durch Klicken auf „New URI“ eine
  Webseite hinzuzufügen. Dies ist nur nützlich, wenn eine
  Browser-Erweiterung verwendet wird, da die Anmeldedaten (Benutzername
  und Passwort) dann automatisch für diese Seite ausgefüllt werden
  können.

Jetzt wurde ein sicheres, zufälliges und einzigartiges Passwort für den
ersten Account erstellt. Es mag zwar schwer zu merken sein, aber genau
dafür ist der Passwortmanager da – zur sicheren Aufbewahrung aller
Passwörter. Es wäre unrealistisch, alle Passwörter auf einmal zu ändern.
Daher empfiehlt es sich, immer dann, wenn du eine Webseite besuchst, bei
der ein altes Passwort verwendet wird, dieses zu aktualisieren. So wird
schrittweise jedes Passwort gesichert, ohne dass du stundenlang daran
arbeiten musst. Bei jeder Anmeldung mit einem neuen Passwort sollte der
Passwortmanager verwendet werden. Auf diese Weise bleiben die Accounts
auch dann geschützt, wenn eines der Passwörter durch ein Datenleck
veröffentlicht wird.

Da Bitwarden ein Online-Passwortmanager ist, sind regelmäßige Backups
unerlässlich. Sollte es jemals zu einer Abschaltung der
Bitwarden-Server, einer Kontosperrung oder einem blockierten Zugriff
kommen, könnten alle Passwörter verloren gehen. Ein Backup,
beispielsweise alle zwei Wochen, ist daher sehr empfehlenswert.

- Klicke dafür oben links auf „File“ und anschließend auf „Export
  Vault“.

- Wähle unter „File-Format“ die Option „json (Encrypted)“ und
  „Passwortgeschützt“ aus und gib das Passwort ein, das diese Datei
  verschlüsseln soll.

- Bestätige den Vorgang mit dem Masterpasswort.

- Wähle den Speicherort aus und speichere die Datei ab.

Es ist wichtig zu beachten, dass Browsererweiterungen und mobile Apps
optional sind und stets ein gewisses Risiko mit sich bringen. Bitwarden
ist zwar ein leistungsstarker Passwortmanager, jedoch werden die
Passwörter in der Cloud gespeichert, was ein Restrisiko mit sich bringt.
Die Passwörter werden zwar auf dem Gerät des Nutzers verschlüsselt und
entschlüsselt, sodass Bitwarden-Mitarbeiter keinen Zugriff darauf haben,
dennoch bleibt die Gefahr eines Hacks höher als bei einem
Offline-Passwortmanager wie KeePassXC. Jeder sollte individuell abwägen,
welches Abwägung von Sicherheit und Benutzerfreundlichkeit für ihn
angemessen ist. Mit Sicherheit ist jeder Passwortmanager besser als
keiner. Es ist ratsam, alle Passwörter schrittweise durch sichere, neu
generierte Passwörter zu ersetzen. Dabei sollte man mit den wichtigsten
Konten beginnen, beispielsweise mit dem E-Mail-Konto oder Bankkonten.
Zudem ist es entscheidend, einen sicheren Computer zu verwenden, denn
wenn auf einem älteren Windows-PC ein Keylogger installiert ist, nützt
die Änderung der Passwörter wenig, da diese sofort ausgelesen und
gespeichert werden könnten. Auch sollte das Netzwerk sicher sein; daher
niemals in einem öffentlichen WLAN.

## 2FA (Zwei-Faktor-Authentifizierung)

Mit der Erstellung sicherer und einzigartiger Passwörter für alle Konten
haben wir bereits ein hohes Maß an Sicherheit erreicht. Dennoch schützt
dies unsere Konten nicht vollständig. Wie bereits erwähnt, werden
jährlich Millionen von Daten geleakt, und es ist unmöglich zu wissen, ob
jemand eines unserer Passwörter besitzt und nur darauf wartet, sich
damit anzumelden.

- Persönliche Informationen zu verkaufen,

- Zugang zu Geldkonten zu erhalten oder

- unsere allgemeine Sicherheit zu gefährden.

Um unbefugten Zugriff zu verhindern, sind zwei wesentliche Maßnahmen zu
beachten: die Zwei-Faktor-Authentifizierung (2FA) und Benachrichtigungen
über Account-Zugriff.

Die 2FA hast du sicherlich schon einmal genutzt, beispielsweise wenn
deine Bank nach den Anmeldedaten einen sechsstelligen Code anfordert
hat, der dir per E-Mail oder SMS zugesendet worden ist. Das ist die
Zwei-Faktor-Authentifizierung. Überall, wo es möglich ist, solltest du
2FA aktivieren.

Mit aktivierter 2FA verlangt das System zusätzlich zu deinen
Anmeldedaten eine weitere Verifizierung. Es gibt verschiedene Formen der
2FA, etwa SMS-Benachrichtigungen, Apps auf deinem Smartphone oder
spezielle USB-Sticks. In der Regel wird ein zeitlich begrenzter Code
(One-Time-Password) bei der Anmeldung zusammen mit deinen Anmeldedaten
eingegeben. Dies erhöht die Sicherheit erheblich. Selbst wenn ein
Angreifer deine Anmeldedaten erlangt hat, benötigt er zusätzlich den
Code, der nur dir (z. B. auf deinem Handy) zugänglich ist. Der Prozess
funktioniert wie folgt.

- Der Benutzer gibt seinen Benutzernamen und sein Passwort ein.

- Die Plattform fordert zur Eingabe eines Einmalpassworts (z. B. den an
  das Handy gesendeten Code) auf.

- Nach Eingabe dieses Codes erhält der Benutzer Zugang zu seinem
  Account.

### Verschiedene Arten von 2FA

**SMS- oder E-Mail-2FA:** Diese Methode ist zwar die am häufigsten
verwendete, jedoch auch die unsicherste. Wenn ein Programm nur SMS oder
E-Mail als 2FA-Option anbietet (wie es bei vielen Bankanwendungen der
Fall ist), solltest du diese Methode dennoch nutzen, auch wenn das
Sicherheitsrisiko höher ist als bei anderen Varianten. In diesem Fall
kann es sinnvoll sein, eine separate Telefonnummer (siehe Kapitel 5,
„Telefonnummern“) ausschließlich für diesen Zweck zu verwenden, um dich
gegen SIM-Swapping-Angriffe abzusichern.

**Hardware-Token:** Dies ist ein kleines Gerät in Form eines USB-Sticks,
das als 2FA-Methode dient. Bei der Anmeldung muss der Stick physisch
berührt werden, um die Authentifizierung zu bestätigen. Ohne Zugriff auf
dieses Gerät kann sich niemand in die geschützten Konten einloggen.
Diese Methode bietet die höchste Sicherheit, erfordert jedoch, dass das
Gerät immer griffbereit ist. Wenn du es vergisst, kann der Zugriff auf
dein Konto gesperrt sein. Die genaue Anleitung zur Einrichtung eines
YubiKey (einem gängigen Hardware-Token) variiert je nach Programm und
wird regelmäßig aktualisiert. Eine Anleitung findest du auf der
Yubico-Website: www.yubico.com

**Software-Token:** Wenn ein Hardware-Token nicht gewünscht ist oder ein
Programm es nicht unterstützt, ist dies die zweite Option. Ich empfehle
die App EnteAuth. Unabhängig davon, welche 2FA-App du wählst, ist diese
Option besser als keine, da auch hier der physische Zugriff auf das
Gerät erforderlich und das Auslesen des Codes durch Malware wesentlich
schwieriger ist als bei der Verwendung einer E-Mail oder SMS. Die App
zeigt dir dann einen sechsstelligen Code an, der sich alle 30 Sekunden
ändert und den du bei der Anmeldung manuell eingeben musst.

### EnteAuth

EnteAuth ist eine Open-Source-2-Faktor-Authentifizierungs-App, die für
alle Betriebssysteme verfügbar ist und auf der Webseite ente.io/auth
heruntergeladen werden kann. Nach dem Download hast du die Möglichkeit,
dich anzumelden. Mit einer Anmeldung kannst du deine 2FA-Codes
verschlüsselt zwischen verschiedenen Geräten synchronisieren. Ich
bevorzuge jedoch die lokale Variante. Klicke dafür auf „Use without
backups“. Anschließend kannst du sofort mit dem Hinzufügen neuer Codes
beginnen.

Da sich bei jedem Accouunt die Einstellung von 2FA ein wenig
unterscheidet, werde ich beispielhaft Bitwarden und ProtonMail
aufzeigen. Die Einstellungen werden zwar in Abhängigkeit von den
verschiedenen Programmen variieren, der grundlegende Prozess bleibt
jedoch gleich.

**ProtonMail:**

- Wähle in den Einstellungen links „Konto und Passwort“ aus.

- Aktiviere das Häckchen bei „Authenticator app“, scanne mit der
  EnteAuth App den QR-Code und gib den sechsstelligen Code ein, der in
  der App angezeigt wird.

**Bitwarden:**

- Klicke auf der Webseite auf „Einstellungen“, dann auf „Security“ und
  oben auf „Two-Step login“ oder öffne diesen Link:
  vault.bitwarden.com/#/settings/security/two-factor

- Wähle die „Authenticator app“ aus und klicke auf „Manage“.

- Scanne den QR-Code mit der App und gib den sechsstelligen Code ein,
  der in EnteAuth angezeigt wird.

EnteAuth generiert für jeden Account alle 30 Sekunden einen neuen
sechsstelligen Code. Bei der Anmeldung bei ProtonMail oder anderen
Programmen mit aktivierter Zwei-Faktor-Authentifizierung (2FA) wird
neben dem Benutzernamen und Passwort auch dieser Code abgefragt. Ohne
diesen Code hast du keinen Zugriff auf deinen Account.

EnteAuth speichert keine Account-Details der jeweiligen Programme,
sondern lediglich die zufällig generierten Codes. Um den Zugang zu
deinen Accounts nicht zu verlieren, sind regelmäßige Backups besonders
wichtig. Ich empfehle, nach jedem neuen Eintrag ein Backup zu erstellen,
um sicherzustellen, dass du bei Verlust des Geräts weiterhin Zugriff auf
deine 2FA-Codes hast.

- Öffne dafür EnteAuth, klicke oben links auf die drei Striche und wähle
  „Datei“ aus.

- Wähle den Unterpunkt „Codes exportieren“ und klicke auf
  „Verschlüsselt“.

- Gebe in das Pop-up-Fenster das Passwort, ein mit dem diese Datei
  verschlüsselt werden soll und bestätige mit „Export“

- Klicke auf „Speichern“ – kannst du den Speicherort auswählen. Ich
  speichere die Datei direkt auf einen USB-Stick, um sie auf meinen
  Laptop zu übertragen.

Diese Datei wird mit dem von dir gewählten Passwort verschlüsselt,
sodass du damit alle deine 2FA-Codes wiederherstellen kannst.

### Probleme ohne 2FA

Neben den Sicherheitsrisiken, die ohne 2FA bestehen, gibt es auch ein
weiteres Problem, das von den Unternehmen selbst ausgehen kann. Im Jahr
2021 führten viele Online-Dienste die verpflichtende Nutzung von 2FA für
ihre Kunden ein. Auf den ersten Blick mag dies sinnvoll erscheinen, doch
oft verbirgt sich dahinter das Bestreben, noch mehr Kundendaten zu
sammeln.

Ich hatte einen anonymen Google-Account, den ich häufig nutzte. Eines
Tages, als ich mich anmelden wollte, forderte Google einen Einmalcode
per SMS an. Da ich nie eine Telefonnummer angegeben hatte, verlangte
Google, dass ich eine Nummer hinzufüge; andere Optionen gab es nicht.
Andernfalls würde der Zugriff auf meinen Account komplett blockiert.

Hier kommt die proaktive 2FA ins Spiel. Hätte ich bei diesem Account
einen 2FA-Code über eine Authentifizierungs-App wie EnteAuth verwendet,
hätte Google niemals nach einer Telefonnummer gefragt. Daher empfehle
ich, jeden Account, der 2FA anbietet, damit zu sichern. Dies erhöht
nicht nur die Sicherheit erheblich, sondern verhindert auch, dass man
von seinen Accounts ausgeschlossen wird, wenn man keine Telefonnummer
angeben möchte.

### Benachrichtigungen für Account-Zugriff

Seit 2016 hat Google eine Funktion eingeführt, die bei jeder Anmeldung
eine E-Mail und eine Push-Benachrichtigung versendet. Diese Maßnahme
dient dazu, die Nutzer darüber zu informieren, wer sich wann und wo in
ihrem Konto anmeldet. Obwohl ich Google wegen seiner Eingriffe in die
Privatsphäre kritisch betrachte, muss man ihre Sicherheitsvorkehrungen
als erstklassig anerkennen.

Diese Funktion ist besonders wichtig, um zu überwachen, ob Konten
gehackt wurden. Viele Online-Dienste haben dies mittlerweile als
Standard übernommen, während andere es als optionale Einstellung
anbieten. Auch wenn diese Benachrichtigungen manchmal lästig sein
können, erhöhen sie die Sicherheit erheblich, da man sofort auf
unautorisierte Logins reagieren kann, indem man das Passwort und die
2FA-Einstellungen ändert. Daher sollten Login-Benachrichtigungen immer
aktiviert sein, wenn der Dienst dies ermöglicht. Überprüfe dazu die
entsprechenden Sicherheitseinstellungen.

## Verschlüsselte Backups und USB-Sticks

Die effektivste Methode, um sensible Daten vor unerwünschtem Zugriff zu
schützen, ist die Verschlüsselung. Dabei werden deine Daten mithilfe
eines geheimen Schlüssels in unleserlichen „Datenmüll“ umgewandelt. Nur
mit diesem Schlüssel können sie wieder in lesbare Informationen
zurückverwandelt werden.

Ein bewährtes Tool zur Verschlüsselung ist VeraCrypt, ein
Open-Source-Programm, das Festplatten, USB-Sticks und einzelne Dateien
schützt. VeraCrypt basiert auf dem früheren Programm TrueCrypt, das auch
von Edward Snowden verwendet wurde. Die Verschlüsselung erfolgt ohne
spürbare Verzögerung und ist benutzerfreundlich.

VeraCrypt ist für die Betriebssysteme Linux, Windows und MacOS
verfügbar. Diese kannst du unter
[veracrypt.eu/en/Downloads.html](https://veracrypt.eu/en/Downloads.html)
herunterladen (Siehe Kapitel 1 für die Linux-Installation).

- Öffne VeraCrypt nach dem Herunterladen. Danach kannst du direkt mit
  der Verschlüsselung beginnen.

- Klicke auf „Create Volume“ in der Mitte links.

- Nun stehen dir zwei Optionen zur Verfügung:

- „Create an encrypted file container“: Erstelle einen verschlüsselten
  Container, der als virtueller Ordner genutzt werden kann.

- „Encrypt a non-system partition/drive“ verschlüsselt eine gesamte
  Partition, z. B. einen USB-Stick.

- Für dieses Tutorial wählen wir die erste Option.

- Wähle im nächsten Schritt „Standard VeraCrypt volume“ aus.

- Lege bei „Select File“ den Speicherort fest, beispielsweise den
  Desktop oder einen USB-Stick, und gib dem Container einen Namen wie
  „Backup“ oder „VeraCrypt“.

- Bei den „Encryption Options“ kannst du die Standardeinstellungen
  beibehalten.

- Lege unter „Volume Size“ die gewünschte Größe des verschlüsselten
  Containers fest. Für Textdokumente sind oft 5 GB ausreichend; für
  vollständige Backups deines Computers oder Handys benötigst du jedoch
  mehr Speicherplatz.

- Wenn der USB-Stick ausschließlich für die Verschlüsselung verwendet
  werden soll, kannst du einen Container in voller Größe erstellen.

- Gib im nächsten Schritt ein sicheres, langes Passwort ein. Hierfür
  kannst du den zuvor eingerichteten Passwortmanager nutzen. Klicke
  danach auf „Next“.

- Überspringe die nächsten drei Seiten jeweils mit „Next“.

- Bewege die Maus innerhalb des Fensters auf der Seite „Volume Format“,
  um die Verschlüsselung weiter zu verstärken. Deine manuell
  hinzugefügten Bewegungen werden genutzt, um die Zufälligkeit zu
  erhöhen und somit die Sicherheit der Verschlüsselung zu verbessern.

- Sobald die Anzeige „Randomness collected from mouse movements“ voll
  ist, klicke auf „Format“, um den Container zu verschlüsseln.

- Nach erfolgreicher Verschlüsselung kannst du das Fenster schließen.

Nun hast du einen verschlüsselten Container auf deinem Computer oder
USB-Stick erstellt, auf den ohne das Passwort kein Zugriff möglich ist.
Um den Container zu verwenden, muss er zunächst gemountet werden.
Hierfür brauchst du dann dein zuvor ausgewähltes Passwort.

| Mounten |
|----|
| Bei VeraCrypt bedeutet „Mounten“, dass das verschlüsselte Volumen (die zuvor erstellte Datei) in das System eingebunden wird, um auf die darin gespeicherten Daten zugreifen zu können. Erst nach dem Mounten und der Eingabe des richtigen Passworts wird das Volume wie ein normaler Datenträger angezeigt und kann genutzt werden. |

- Öffne dafür VeraCrypt, klicke auf „Select File“ in der Mitte rechts
  und wähle den zuvor erstellten Container aus.

- Klicke unten links auf „Mount“, gib das Passwort ein und bestätige,
  falls gefragt, auch das Passwort des Computers.

- Der Container wird nun gemountet und als zusätzliches Laufwerk
  angezeigt. Du kannst Dateien nach Belieben hinein- oder
  herauskopieren. Um den Container wieder zu verschlüsseln, klicke
  einfach auf „Dismount All“.

### Welche Daten sollten verschlüsselt werden?

**Sensible Informationen:** Dazu zählen Kontaktdaten, Dokumente wie
Ausweise und Pässe sowie alles, was nicht für die Öffentlichkeit
bestimmt ist. Ein kleiner Container mit 10 GB auf dem Laptop ist oft
ausreichend, um diese Daten sicher zu speichern.

**Backups:** Eine zuverlässige Backup-Strategie sollte immer eine
Verschlüsselung beinhalten. Zwar bieten Microsoft, Apple und Linux
eigene Backup-Programme an, ich empfehle jedoch eine Open-Source-Lösung
wie FreeFileSync. Dieses Programm unterstützt dich dabei, Dateien, die
noch nicht gesichert wurden, zu identifizieren und in den erstellten
verschlüsselten Container zu kopieren.

- Lade dafür FreeFileSync von der Webseite
  [freefilesync.org/](https://freefilesync.org/) herunter und öffne es.

- Wähle links deinen Home-Ordner aus und rechts den VeraCrypt-Ordner auf
  dem USB-Stick. (1)

- Klicke oben rechts auf das Zahnrad und wähle „Update“ aus. (2)

- Klicke oben links auf „Compare“. (3)

- Nach Abschluss des Vergleichs klicke oben rechts auf „Synchronize“.
  (4)

<span id="_Toc196572876" class="anchor"></span>Abbildung
13FreeFileSync-Synchronisation

Jetzt beginnt die Synchronisation. Zu Beginn kann es etwas länger
dauern, da alle Dateien gesichert werden müssen. Bei zukünftigen Backups
erfolgt die Übertragung schneller, da nur noch neue und geänderte
Dateien gesichert werden.

Es ist empfehlenswert, regelmäßige Backups auf einem verschlüsselten
USB-Stick zu erstellen. Sollte dieser verloren gehen oder gestohlen
werden, brauchst du dir keine Sorgen zu machen, da der Inhalt durch die
Verschlüsselung unzugänglich bleibt. Eine effektive Backup-Strategie
lässt sich mithilfe der 3-2-1-Regel umsetzen:

- **3 Kopien:** Du solltest mindestens drei Backups deiner Daten haben.

- **2 verschiedene Speichermedien:** Nutzte mindestens zwei
  unterschiedliche Speichermedien, z. B. USB-Sticks und externe
  Festplatten.

- **1 Kopie an einem anderen Ort:** Bewahre eine Kopie an einem anderen
  Ort auf.

Sollte ein Backup verloren gehen, gestohlen oder zerstört werden,
bleiben die anderen beiden verfügbar. Selbst im schlimmsten Fall, wenn
dein Haus abbrennt, hast du immer noch ein Backup an einem anderen Ort.

Das erste der drei Backups befindet sich auf deinem verschlüsselten
Computer. Für die anderen beiden Backups eignen sich USB-Sticks mit
jeweils 512 GB (je nach Bedarf auch mehr oder weniger) und einem
VeraCrypt-Container. Backups sollten in Abhängigkeit davon erstellt
werden, wie viele neue Dateien seit dem letzten Backup hinzugekommen
sind – mindestens jedoch einmal im Monat. Auf Reisen, wenn das Risiko
eines Diebstahls höher ist, sind häufigere Backups sinnvoll.

Einer der beiden USB-Sticks sollte zu Hause aufbewahrt werden, um
regelmäßig Backups erstellen zu können. Den zweiten Stick kannst du
sicher bei Freunden oder Familienmitgliedern aufbewahren. Sollten dein
Laptop und der erste USB-Stick gestohlen werden, kannst du durch einen
kurzen Anruf darum bitten, dass dir die Daten vom zweiten USB-Stick
geschickt werden. So kannst du auf einem anderen Gerät deine Daten
entschlüsseln und weiterhin darauf zugreifen.

Da du nicht immer Zugriff auf diesen Stick hast, sind Backups nicht so
oft möglich wie auf dem ersten. Dennoch sollte dieser Stick mindestens
alle zwei Monate aktualisiert werden.

Backups in der Cloud, wie sie von OneDrive oder Apple iCloud angeboten
werden, solltest du vermeiden. Da sie jedoch einfacher zu handhaben
sind, wäre ein Kompromiss, dein Backup in einem VeraCrypt-Container zu
verschlüsseln und dann nur diesen hochzuladen. Am besten verwendest du
dafür die ProtonCloud.

•   •   •

In diesem Kapitel haben wir unsere Accounts mit sicheren Passwörtern
sowie der Zwei-Faktor-Authentifizierung (2FA) gesichert. Das heißt das
vor jedem Account ein einzigartiges, zufällig generiertes Passwort ist
sowie eine 2FA durch EnteAuth. Damit ist die Angriffsfläche enorm
minimiert. Darüber hinaus haben wie verschiedene verschlüsselte Backups
wichtiger Daten erstellt, auf dem Computer sowie auch auf anderen
Speichermedien. Im Notfall können wir darauf zugreifen, während sie
gleichzeitig vor unbefugtem Zugriff geschützt sind. Im nächsten Kapitel
geht es dann um einen weiteren unverzichtbaren Bereich in unserem
digitalen Alltag ­ sichere und private Kommunikation.
