# Beschreibe dein Projekt kurz. (100w)

Das keypeer Projekt ist ein Schlüssel dienst, im Sinne von API (Application Programming Interface) Schlüssel, keys.

Entwickler von Free Open Source Software (FOSS) ermöglicht keeypeer einen abgabenpflichtigen Dienst in der eigenen App einzubinden und bei einem Nutzer frei zu schalten der Bezahlt hat ohne Geschäftsbeziehung und ohne Personen Daten zu speichern. Nutzern ermöglicht keypeer dritt Anbieter Diensten in Apps zu unterstützen.

keypeer selbst nimmt keine Bezahlung entgegen sondern registriert nur einen Anonymen Nutzer Schlüssel und verbindet die mit einem dritt Service API key. Zahlungen werden von einem Verein mittels https://opencollective.com/europe angenommen und ausgegeben.

#  Welche gesellschaftliche Herausforderung willst du mit dem Projekt angehen? * (175w)

Als Beispiel, viele FOSS/OSS Kartendienste bieten neben einer Basis wie Openstreetmaps, Kacheln (eg. Satelliten Bilder) von dritten an die ab einer gewissen Anzahl von Nutzern/Abrufe kostenpflichtig sind. Mapbox, zum Beispiel. keypeer wäre die Schnittstelle, der Service, der es dem Nutzer ermöglicht ein Beitrag zu leisten und dafür Schlüssel für einen oder mehrere dritt Anbieter Dienste in Apps zu bekommen. Mittels keypeer kann ein Nutzer auch mehrere Projekte gleichzeitig unterstützen.

Mittels keypeer wird eine Nutzer<->App Marke erzeugt. Der Nutzer gibt diese bei Bezahlung an, zum Beispiel https://opencollective.com/europe. Diese wird beim keypeer registriert und die App kann das Nutzen vom dritt Dienst freischalten. Bezahlungen werden verwaltet von einem Verein, in einer kollektiven Kasse.  Dieser Verein veranlaßt nur Zahlungen aus dem kollektivem Konto an  dritt Anbieter, bzw. Mapbox. Der Verein https://sailmates.net hat sich bereit erklärt die Prototype-phase zu begleiten.

Ziel ist das bündeln von Nutzer Zahlungen um den dritt Dienst zu Zahlen, was der Entwickler oder das Projekt nicht leisten könnte.

Als transparente finanzielle Vermittlungsstelle soll, bzw.,  https://opencollective.com/europe dienen.

# Wie willst du dein Projekt technisch umsetzen? * (175w)

Der Server besteht aus einem Web Service ( REST API ), eine frei erreichbare Schnittstelle die Entwickler einbinden können um Nutzer Tokens/Marken anonyme von keypeer zu prüfen. Wurde bei keypeer die Marke als bezahlt (Turnus gemäß) registriert, kann ein zusätzlicher Dienst eingeschaltet werden. Diese REST API wird mittels Flask in Python als Prototype entwickelt.

Anvisiert ist eine Zero Proof Datenbank, basierend auf Circuitree, https://ieeexplore.ieee.org/document/9718332 zu nutzen.

Während der Prototype-phase werden Javascript und C++ Clients die Schnittstelle testen. Als erstes, die Mapping Anwendung Puremaps https://github.com/rinigus/pure-maps

#  Hast du schon an der Idee gearbeitet? Wenn ja, beschreibe kurz den aktuellen Stand und erkläre die geplanten Neuerungen. * (100w)

Bis jetzt wurde diskutiert und die ersten API Entwürfe skizziert, https://github.com/poetaster/keypeer.org/blob/main/doc/api-rest.md Impulsgeber is der rinigus,https://github.com/rinigus/pure-maps.  Unter anderem wird mit Ruben De Smet, https://ieeexplore.ieee.org/document/9718332 , ein Zero Knowledge Ansatz der Nutzer Verifikation diskutiert.


#  Welche ähnlichen Ansätze gibt es schon und was wird dein Projekt anders bzw. besser machen? * (60w)

Keine.

# Wer ist die Zielgruppe und wie soll dein Projekt sie erreichen? * 

Sowohl App Endnutzer als Entwickler. Die Anzahl an Anwendung die API keys brauchen wächst stetig und betrifft alle möglichen Bereiche von Gesundheit zur Bildung, Navigation bis zur Geology. In erster Linie geht es um Entwicklung von FOSS Anwendungen dem sonst die Mittel fehlen zu unterstützen und dem Nutzer die Wahl alternativer Apps.

Die Prototyp Phase wird mit Puremaps, die Karten Anwendung, realisiert da es hier schon eine Kollaboration statt findet und der Entwickler von Puremaps auch mit anderen Karten Anwendungs- Entwickler in Kontakt steht. Wir streben auch Finanzierung zwischen Projekten an.

# An welchen Software-Projekten hast du / habt ihr bisher gearbeitet? Bei Open-Source-Projekten bitte einen Link zum Repository angeben

https://github.com/poetaster/fahrplan (Entwickler Team, Maintainer)
https://github.com/poetaster/tomservice (Entwickler, Maintainer)
https://github.com/poetaster/tidings (Entwickler Team, Maintainer)

# Erfahrung, Hintergrund, Motivation, Perspektive: Was sollen wir über dich (bzw. euch) wissen und bei der Auswahl berücksichtigen? * 

Auf die Prototypefund bin ich gekommen da ich eine Anwendung vor 2 Jahr entwickelte die den Brightsky API nutzt. https://github.com/jdemaeyer/brightsky/ In gewisser Hinsicht hat auch Brightsky ein ähnliches ziel wie ich. Das vereinfachen des Nutzen von APIs.

Ich bin seit Anfang der 1990er Jahre involviert in FOSS/OSS Projekten. Sowohl als Entwickler als auch im Bereich Gesellschaftlicher Entwicklung. Als mit Inhaber der Newthinking Communications GmbH habe ich die Gründung der https://re-publica.com und https://netzpolitik.org mit getragen. Weitere bestehende Projekte die wir aufgebaut haben sind https://berlinbuzzwords.de und die https://foss-backstage.de . Bis ende 2022 war ich noch bei netzpolitik.org angestellt.

Als Technische Leitung und Programmierer bin ich an verschiedenen FOSS orientierten Initiativen  beteiligt. Seit etwa 2018 bin ich zunehmend an der Entwicklung von alternativen mobilen Plattformen, insbesondere SailfishOs, beteiligt. Bis jetzt habe ich mich hauptsächlich um den Erhalt von Anwendungen und neu Entwicklung von Apps bemüht, mit Schwerpunkt Media. Bild, Video und Ton Bearbeitungs- Apps sind Schwerpunkte aus Leidenschaft.

Durch Eigenentwicklung und im Gespräch mit weiteren Entwickler wurde mir klar das wir was unternehmen können um die Kaufkraft von FOSS Unterstützer für viele interagierenden Projekten zu bündeln. Ich sehe es auch als eine Art 'Crowd Funding Model'.





