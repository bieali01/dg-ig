<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Hausarztpraxis erfasst Arzneimittelallergien ihrer Patientinnen und Patienten mithilfe eines standardisierten FHIR-Profils. Die Informationen werden von Ärztinnen und Ärzten dokumentiert und können von einer Notfallstation zuverlässig ausgewertet werden. Dadurch stehen wichtige Angaben zu Allergien und möglichen Reaktionen zur Verfügung.


### Scope

Dieses Implementation Guide beschreibt die strukturierte Erfassung von Arzneimittelallergien auf Basis von CH Core AllergyIntolerance. Es legt Anforderungen an den klinischen Status, die verwendeten Codes, die Kritikalität, den Beginn der Allergie, die erfassende Fachperson und mögliche Reaktionen fest.

Andere Allergiearten, beispielsweise Lebensmittel- oder Umweltallergien, sind nicht Bestandteil dieses IG.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): FHIR-Profil zur standardisierten Dokumentation von Arzneimittelallergien.
* [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten Penicillinallergie mit dokumentierter Hautreaktion.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Alisha Bieli

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
