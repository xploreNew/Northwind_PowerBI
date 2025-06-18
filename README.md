
📊 Power BI Projektbericht – Northwind Trader.

Im Rahmen meines Lernprozesses mit Power BI habe ich eine Reihe interaktiver Dashboards basierend auf dem fiktiven Northwind Trader-Datensatz erstellt. Ziel war es, zu verstehen, wie man Rohdaten in aussagekräftige Erkenntnisse umwandeln kann – mithilfe von Datenmodellierung, Visualisierung und den interaktiven Funktionen von Power BI. Nachfolgend eine Übersicht über jedes Dashboard und die gewonnenen Erkenntnisse.

Dashboard 1 – Verkaufsanalyse & Logistikübersicht
![image](https://github.com/user-attachments/assets/163a3948-cebb-44ff-945c-b97913568928)

Dieses Dashboard liefert eine allgemeine Übersicht zu Umsatz und Logistik:

Nettoumsatz & Verkaufsmenge: Der Nettoumsatz beträgt $77,92K bei insgesamt 4,26K verkauften Einheiten.

Meistverkaufte Waren:

Getränke (14 Stück),

Trockenfrüchte & Nüsse (9 Stück),

gefolgt von Backwaren & Süßigkeiten.

Weniger verkaufte Waren:

Öl, Getreide und Obst- & Gemüsekonserven.

Leistung nach Mitarbeiter: Das Kreisdiagramm zeigt die Verkaufsverteilung nach Vertriebsmitarbeitern.

Versandkosten nach Lieferort: Höchste Versandkosten gab es nach Milwaukee ($104) und Denver ($103,5).

Kundenstandorte: Eine interaktive Karte zeigt die geografische Verteilung der Kunden in den USA.
🎯 Slide 1: Verkaufsanalyse & Logistikübersicht
🧠 Key Learnings:

Wenige Mitarbeiter generieren den Großteil des Umsatzes → gezielte Förderung sinnvoll.

„Getränke“ sind sowohl beim Absatz als auch Umsatz führend → wichtigster Produktbereich.

Andere Top-Verkaufskategorien erzielen nicht den höchsten Umsatz → Preisanalyse & Margenstrategie notwendig.

Hohe Versandkosten in Städten wie Milwaukee und Denver → Optimierungspotenzial in der Logistik.

Kunden geografisch weit verteilt → Einfluss auf Lieferkosten und Servicequalität.

![image](https://github.com/user-attachments/assets/01941ab1-4fa9-4cb7-b7da-7815d5082f9c)
Das Dashboard kann Drilldown zu Vergleichsansicht der meistverkauften Waren aus drei Perspektiven: nach Mitarbeiter, Position und Produktkategorie. Diese Ansicht ermöglicht es, den Zusammenhang zwischen Vertriebspersonal, ihrer Rolle im Unternehmen und den am häufigsten verkauften Produkten besser zu verstehen.


Dashboard 2 – Umsatzanalyse nach Kategorie, Bundesland & Kunden
![image](https://github.com/user-attachments/assets/1fc8140c-88ae-4a54-a7f8-ccf6e49b0e59)

Dieses Dashboard fokussiert sich auf die finanzielle Performance nach Produktkategorie, Bundesland und Kundenunternehmen:

Nettoumsatz nach Kategorie:

Getränke erzielen mit Abstand den höchsten Umsatz.

Nettoumsatz nach Bundesland:

Die umsatzstärksten Bundesländer sind Tennessee (TN) und Idaho (ID).

Weniger Umsatz wurde in Illinois (IL) und Kalifornien (CA) erzielt.

Nettoumsatz pro Kundenfirma:

Firma BB und Firma G sind für über 60 % des Umsatzes verantwortlich.

Dieses Dashboard zeigt, wie sich der Umsatz je nach Region und Kundenstruktur unterscheidet.
Ein interessanter Befund aus den Dashboards 1 und 2 zeigt, dass die meistverkauften Produkte – mit Ausnahme von „Getränke“ – nicht gleichzeitig die umsatzstärksten Kategorien sind. Das deutet darauf hin, dass eine hohe Verkaufsmenge nicht zwingend zu einem hohen Nettoumsatz führt, was insbesondere bei Produkten mit geringem Stückpreis erkennbar wird.

🧠 Key Learnings:

Umsatz ist stark auf wenige Bundesländer (TN, ID) konzentriert → regionales Wachstumspotenzial identifizieren.

Nur wenige Kundenfirmen (BB, G) tragen den Großteil des Umsatzes → Risiko & Bindungsstrategien prüfen.

Produktabsatz steht nicht immer im Verhältnis zum Umsatz → Fokus auf margenstärkere Produkte lohnenswert.

Große Unterschiede zwischen Regionen → gezieltes regionales Marketing und Preismodelle denkbar.

Beobachtung: Außer „Getränke“ gehören die meistverkauften Produkte nicht zu den Kategorien mit dem höchsten Nettoumsatz. Dies weist darauf hin, dass ein hoher Absatz nicht zwangsläufig mit hohem Umsatz einhergeht.


Dashboard 3 – Versand & Transaktionsarten
![image](https://github.com/user-attachments/assets/bc850989-240a-4463-857d-cd2c92b21ba3)

Diese Ansicht konzentriert sich auf logistische und operative Kennzahlen:

Versandkosten nach Lieferort:

Höchste Kosten gab es in Milwaukee, Denver und Salt Lake City.

Durchschnittliche Lieferzeit (in Tagen):

Durchschnittliche Lieferdauer beträgt 3,43 Tage, was einen effizienten Ablauf zeigt.

Waren nach Transaktionsart:

Produkte sind in Verkauft, Gekauft und Zurückgehalten unterteilt.

Bestellte Waren:

Insgesamt wurden 102 Bestellungen registriert.

Top-Produkte (Bestätigung aus Dashboard 1):

Getränke bleiben die meistbestellte Kategorie.

Durchschnittliche Lieferzeit von 3,43 Tagen deutet auf effiziente Prozesse hin.

Unterschiedliche Transaktionstypen (Verkauft, Gekauft, Zurückgehalten) zeigen operative Komplexität → Analysepotenzial.

Versandkosten stark ortsabhängig → Möglichkeit zur Optimierung oder Kostenverlagerung.

„Getränke“ weiterhin Top-Performer → konsistentes Ergebnis über alle Metriken hinweg.

🎯 Lernziele & Erkenntnisse:
Einsatz von Power Query zur Datenbereinigung und -transformation.

Erstellung von Datenmodellen mit Beziehungen zur dynamischen Filterung.

Nutzung von DAX-Formeln zur Berechnung individueller KPIs (z. B. Nettoumsatz, Bruttoumsatz).

Integration von interaktiven Visualisierungen wie Karten, Donut-Charts und Slicern für eine benutzerfreundliche Analyse.

💡 Fazit:
Dieses Power BI-Projekt zeigt, wie sich verschiedene Geschäftsdimensionen (Produkt, Geografie, Mitarbeitende, Kunden) mithilfe von intuitiven Dashboards analysieren und darstellen lassen. Es war eine wertvolle Übung in Datenvisualisierung, Business Intelligence und Storytelling mit Daten.
