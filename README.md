# Rahmenbedingungen

-	Sie erhalten **2 Aufgaben**
-	Ihnen stehen **90 Minuten** zur Erarbeitung einer Lösung **für beide Aufgaben** zur Verfügung
-	Stefan Flury steht jederzeit für Verständnisfragen zur Verfügung
-	Ihr Laptop mit WLAN ist zur freien Verfügung
-	Danach **Präsentation** beider Lösungen in **30 Minuten** mit anschliessender Diskussion

# Aufgabe 1: Adressdaten

**a)**	Modellieren Sie Schweizer Postadressen von Gebäuden (ohne Personen) als Entity-Relationship-Diagramm (ERD). Normalisieren Sie dabei so weit als möglich und sinnvoll.

**b)**	Legen Sie die Datentypen und Wertebereiche fest.

**c)**	Ergänzen sie die so entstandenen Tabellen mit deren Geometrie.

**d)**	Welche topologischen Regeln gelten zwischen den einzelnen Geometrien?


**Unterlagen und Hilfsmittel:**
- Informationsebene «Gebäudeadressen» der Amtlichen Vermessung
https://www.cadastre.ch/de/manual-av/topic/address.html

- Erklärungen bezüglich dem Datenmodell der Amtlichen Vermessung. Siehe Kapitel 19 PLZ Ortschaft und Gebäudeadressen Seiten 35-40
https://www.cadastre.ch/content/cadastre-internet/de/home/meta/law/law-54/_jcr_content/contentPar/downloadlist/downloadItems/97_1489420054485.download/DM-01-AV-CH-Erklärungen-de.pdf

- Überblick über Topologien: auf Papier

# Aufgabe 2: Inkrement
Swisstopo führt ein Strassennetz im Produkt swissTLM3D nach. Dieses Netz besteht aus Kanten (Strassenstücken) und Knoten (Kreuzungen). Ein Kunde A bestellt bei swisstopo das Strassennetz Version T0 und integriert es in seine Infrastruktur. Nach einem Jahr will der Kunde seine Version T0 auf die neue Version T1 des Strassennetzes von swisstopo updaten. Dazu erwartet er als Lieferung die Veränderungen zwischen T0 und T1, da dadurch die Integration in sein System einfacher wird.

**a)**	Was ist eine Veränderung. Wie würden Sie Veränderungen beschreiben/modellieren. Welche Arten/Typen von Veränderungen gibt es?

**b)**	Wie würden Sie Veränderungen beschreiben/modellieren.

**c)**	Wie könnte eine Web Service Schnittstelle aussehen, die Inkremente eines Datensatzes zur Verfügung stellt. Welche Endpoints gibt es, welche Parameter könnten wünschenswert sein, welche Antworten könnte ein solche Schnittstelle liefern?

**d)**	Kennen Sie andere Einsatzgebiete/System an denen Inkremente gebildet werden?
Wenn ja, beschreiben sie ein entsprechendes Konzept und zeigen sie wie sie das auf unseren Fall übertragen würden.

**e)**	Gibt es Bedingungen die die Daten erfüllen müssen, damit Ihr Konzept erfüllbar ist? Gibt es Anforderungen welche bei der Nachführung eines Datensatzes mit Inkrementen zwingend berücksichtigt werden müssen.

**f)**	Könnten über Inkremente auch dezentral Daten nachgeführt und später in einer zentralen Datenbank aktualisiert werden? Gibt es Grenzen? Was sind mögliche Konflikte und wie könnten diese gelöst werden?

**g)**	In wie fern kann die Versionierung einer ESRI-Geodatabase dies unterstützen? Wo liegen die Grenzen?


**Unterlagen und Hilfsmittel**
- zu g), Was ist eine Version 
http://desktop.arcgis.com/de/arcmap/latest/manage-data/geodatabases/what-is-a-version.htm

- zu g), Terminologie im Zusammenhang mit Versionierung
http://desktop.arcgis.com/de/arcmap/latest/manage-data/geodatabases/versioning-terms.htm
