<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Dieser Implementation Guide beschreibt die strukturierte 
Erfassung von Arzneimittelallergien in einer Hausarztpraxis. 
Die dokumentierten Informationen sollen einer Notfallstation 
ermöglichen, bekannte Allergien, deren Kritikalität und 
mögliche Reaktionen zuverlässig auszuwerten.

### Scope

Der Implementation Guide basiert auf CH Core 
AllergyIntolerance und definiert ein Profil für 
Arzneimittelallergien.

Der Fokus liegt auf:
- Der Beschränkung auf Arzneimittelallergien.
- Der verpflichtenden Angabe des klinischen Status.
- Der Verwendung der Schweizer Allergieliste.
- Der Dokumentation der Kritikalität und des Allergiebeginns.
- Der Erfassung der verantwortlichen Ärztin oder des verantwortlichen Arztes.
- Der Dokumentation möglicher allergischer Reaktionen.

### Artefakte

TODO: Ergänzt pro Artefakt einen Satz, wofür es da ist.

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Definiert ein Profil zur strukturierten Erfassung von Arzneimittelallergien auf Basis von CH Core AllergyIntolerance.
* [Titel eures Beispiels](AllergyIntolerance-PenicillinAllergieAnna.html): Zeigt ein Beispiel einer bestätigten Penicillinallergie mit hoher Kritikalität und dokumentierter allergischer Reaktion.

<!-- TODO_Name ist der Name hinter "Instance:" in beispiele.fsh,
     z. B. AllergyIntolerance-PenicillinAllergieAnna.html -->

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

TODO: Mia Sollberger

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
