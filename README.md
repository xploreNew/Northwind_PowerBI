

<h2>📊 Power BI Projektbericht – Northwind Trader.</h2>

Im Rahmen meines Lernprozesses mit Power BI habe ich eine Reihe interaktiver Dashboards basierend auf dem fiktiven Northwind Trader-Datensatz erstellt. Ziel war es, zu verstehen, wie man Rohdaten in aussagekräftige Erkenntnisse umwandeln kann – mithilfe von Datenmodellierung, Visualisierung und den interaktiven Funktionen von Power BI. Nachfolgend eine Übersicht über jedes Dashboard und die gewonnenen Erkenntnisse.

<h4>Dashboard 1 – Verkaufsanalyse & Logistikübersicht:</h4>
<h5>Dieses Dashboard liefert eine allgemeine Übersicht zu Umsatz und Logistik:</h5>



<ul>
  <li><b>Nettoumsatz & Verkaufsmenge:</b> Der Nettoumsatz beträgt $77,92K bei insgesamt 4,26K verkauften Einheiten.</li>
  <li><b>Meistverkaufte Waren:</b>Getränke (14 Stück),Trockenfrüchte & Nüsse (9 Stück),gefolgt von Backwaren & Süßigkeiten.</li>
  <li><b>Weniger verkaufte Waren:</b>Öl, Getreide und Obst- & Gemüsekonserven.</li>
  <li><b>Leistung nach Mitarbeiter:</b> Das Kreisdiagramm zeigt die Verkaufsverteilung nach Vertriebsmitarbeitern.</li>
  <li><b>Versandkosten nach Lieferort:</b>Höchste Versandkosten gab es nach Milwaukee ($104) und Denver ($103,5).</li>
  <li><b>Kundenstandorte:</b> Eine interaktive Karte zeigt die geografische Verteilung der Kunden in den USA.</li>
</ul>
<p align="center">
<img src="https://github.com/user-attachments/assets/163a3948-cebb-44ff-945c-b97913568928" width=500 height=500>
</p>
![image](https://github.com/user-attachments/assets/163a3948-cebb-44ff-945c-b97913568928)
<!--🎯 Slide 1: Verkaufsanalyse & Logistikübersicht-->


🧠 <b>Key Learnings:</b>
<li>Wenige Mitarbeiter generieren den Großteil des Umsatzes → gezielte Förderung sinnvoll.</li>
<li>„Getränke“ sind sowohl beim Absatz als auch Umsatz führend → wichtigster Produktbereich.</li>
<li>Andere Top-Verkaufskategorien erzielen nicht den höchsten Umsatz → Preisanalyse & Margenstrategie notwendig.</li>
<li>Hohe Versandkosten in Städten wie Milwaukee und Denver → Optimierungspotenzial in der Logistik.</li>
<li>Kunden geografisch weit verteilt → Einfluss auf Lieferkosten und Servicequalität.</li>

Das Dashboard kann Drilldown zu Vergleichsansicht der meistverkauften Waren aus drei Perspektiven: nach Mitarbeiter, Position und Produktkategorie. Diese Ansicht ermöglicht es, den Zusammenhang zwischen Vertriebspersonal, ihrer Rolle im Unternehmen und den am häufigsten verkauften Produkten besser zu verstehen. 

![image](https://github.com/user-attachments/assets/01941ab1-4fa9-4cb7-b7da-7815d5082f9c)




<h4>Dashboard 2 – Umsatzanalyse nach Kategorie, Bundesland & Kunden</h4>

Dieses Dashboard fokussiert sich auf die finanzielle Performance nach Produktkategorie, Bundesland und Kundenunternehmen:
Dieses Dashboard zeigt, wie sich der Umsatz je nach Region und Kundenstruktur unterscheidet.

<ul>
  <li><b>Nettoumsatz nach Kategorie:</b>Getränke erzielen mit Abstand den höchsten Umsatz.</li>
  <li><b>Nettoumsatz nach Bundesland:</b>Die umsatzstärksten Bundesländer sind Tennessee (TN) und Idaho (ID).
  Weniger Umsatz wurde in Illinois (IL) und Kalifornien (CA) erzielt.</li>
  <li><b>Nettoumsatz pro Kundenfirma:</b>Firma BB und Firma G sind für über 60 % des Umsatzes verantwortlich.</li>
</ul>
<p align=center>
  <img src=https://github.com/user-attachments/assets/1fc8140c-88ae-4a54-a7f8-ccf6e49b0e59 width=500 height=400>
</p>
![image](https://github.com/user-attachments/assets/1fc8140c-88ae-4a54-a7f8-ccf6e49b0e59)



<b>🧠 Key Learnings:</b>
<ul>
  <li>Umsatz ist stark auf wenige Bundesländer (TN, ID) konzentriert → regionales Wachstumspotenzial identifizieren.</li>
  <li>Nur wenige Kundenfirmen (BB, G) tragen den Großteil des Umsatzes → Risiko & Bindungsstrategien prüfen.</li>
  <li>Produktabsatz steht nicht immer im Verhältnis zum Umsatz → Fokus auf margenstärkere Produkte lohnenswert.</li>
  <li>Große Unterschiede zwischen Regionen → gezieltes regionales Marketing und Preismodelle denkbar.</li>
</ul>

Ein interessanter Befund aus den Dashboards 1 und 2 zeigt, dass die meistverkauften Produkte – mit Ausnahme von „Getränke“ – nicht gleichzeitig die umsatzstärksten Kategorien sind. Das deutet darauf hin, dass eine hohe Verkaufsmenge nicht zwingend zu einem hohen Nettoumsatz führt, was insbesondere bei Produkten mit geringem Stückpreis erkennbar wird.

<h4>Dashboard 3 – Versand & Transaktionsarten:</h4>
Diese Ansicht konzentriert sich auf logistische und operative Kennzahlen:

<ul>
  <li><b>Versandkosten nach Lieferort:</b>Höchste Kosten gab es in Milwaukee, Denver und Salt Lake City.</li>
  <li><b>Durchschnittliche Lieferzeit (in Tagen):</b>Durchschnittliche Lieferdauer beträgt 3,43 Tage, was einen effizienten Ablauf zeigt.</li>
  <li><b>Waren nach Transaktionsart:</b>Produkte sind in Verkauft, Gekauft und Zurückgehalten unterteilt.</li>
  <li><b>Bestellte Waren:</b>Insgesamt wurden 102 Bestellungen registriert.</li>
  <li><b>Top-Produkte:</b>Getränke bleiben die meistbestellte Kategorie.
      Durchschnittliche Lieferzeit von 3,43 Tagen deutet auf effiziente Prozesse hin.
      Nur 10 Zurückgehalten Produkte zeigen 90% Umsatz!</li>
</ul>
<p align=center>
  <img src="https://github.com/user-attachments/assets/bc850989-240a-4463-857d-cd2c92b21ba3" width=500 heing=500>
</p>
![image](https://github.com/user-attachments/assets/bc850989-240a-4463-857d-cd2c92b21ba3)

  <b>🧠 Key Learnings:</b>
<ul>
 <li>Versandkosten stark ortsabhängig → Möglichkeit zur Optimierung oder Kostenverlagerung.</li>
 <li>„Getränke“ weiterhin Top-Performer → konsistentes Ergebnis über alle Metriken hinweg.</li>
 
</ul>
<br><br>



<b>💡 Fazit:</b>
Dieses Power BI-Projekt zeigt, wie sich verschiedene Geschäftsdimensionen (Produkt, Geografie, Mitarbeitende, Kunden) mithilfe von intuitiven Dashboards analysieren und darstellen lassen. Es war eine wertvolle Übung in Datenvisualisierung, Business Intelligence und Storytelling mit Daten.


Durch dieses Projekt konnte ich praktische Erfahrungen mit … 
<ul>
  <li>Einsatz von Power Query zur Datenbereinigung und -transformation.</li>
 <li>Erstellung von Datenmodellen mit Beziehungen zur dynamischen Filterung.</li>
 <li>Nutzung von DAX-Formeln zur Berechnung individueller KPIs (z. B. Nettoumsatz, Bruttoumsatz).</li>
 <li>Integration von interaktiven Visualisierungen wie Karten, Donut-Charts und Slicern für eine benutzerfreundliche Analyse.</li>
</ul>
sammeln
