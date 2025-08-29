> [!IMPORTANT]
> **Einstellung des Nowcastings zum 21.06.2023**
> 
> Seit dem `21.06.2023` ist die tägliche Berechnung des Nowcasting und des R-Werts durch das RKI eingestellt. Es erfolgt keine weitere Aktualisierung der Daten.  
> 
> Im [ARE-Wochenbericht](https://influenza.rki.de/Wochenberichte.aspx) des RKI wird weiterhin über die Zirkulation von SARS-CoV-2 im Rahmen der virologischen Surveillance sowie über die Krankheitslast von akuten > Atemwegserkrankungen in der Bevölkerung, im ambulanten sowie im stationären Bereich im Rahmen der syndromischen Surveillance berichtet werden. (Siehe: [ARE-Wochenbericht, Pandemieradar, frühere COVID-19-Wochenberichte](https://edoc.rki.de/handle/176904/39))

---------

<!-- HEADER_START: {"lang": "de"} -->


Dokumentation  
# SARS-CoV-2-Nowcasting und -R-Schaetzung

<br> 
<br> 
<br> 

[**Matthias an der Heiden**](https://orcid.org/0000-0001-5863-4549)&sup1;

<br> 

**Beitragende**   
[Justus Benzler](https://orcid.org/0000-0002-7470-0849)&sup2;, & [Hannes Wünsche](https://orcid.org/0000-0002-8837-0326)&sup3;

&emsp;&emsp;&sup1; [Robert Koch-Institut](https://www.rki.de/) | [Fachgebiet 34](https://www.rki.de/fg34)  
&emsp;&emsp;&sup2; [Robert Koch-Institut](https://www.rki.de/) | [Fachgebiet 32](https://www.rki.de/fg32)  
&emsp;&emsp;&sup3; [Robert Koch-Institut](https://www.rki.de/) | [Fachgebiet MF 4](https://www.rki.de/mf4)

<br> 

**Zitieren**  
an der Heiden, M. (2023). SARS-CoV-2-Nowcasting und -R-Schaetzung [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.8062328](https://doi.org/10.5281/zenodo.8062328)

<br>


**Zusammenfassung**    
Im Datensatz "SARS-CoV-2-Nowcasting und -R-Schätzung" des Robert Koch-Instituts wurden von März 2020 bis Juni 2023 täglich aktualisierte epidemiologische Schätzwerte zur COVID-19-Pandemie in Deutschland bereitgestellt. Ziel war es, auf Basis gemeldeter SARS-CoV-2-Infektionen eine zeitnahe Einschätzung des Infektionsgeschehens sowie der effektiven Reproduktionszahl (R-Wert) zu ermöglichen. Der Datensatz umfasst Schätzwerte zur Anzahl an Neuerkrankungen und zum R-Wert.

<br>

**Inhaltsverzeichnis** 
<!-- TOC_START: {"heading_depth": 2} -->
  - [Informationen zur Studie und zum Forschungskontext](#informationen-zur-studie-und-zum-forschungskontext)
  - [Aufbereitung und Auswertung der Daten](#aufbereitung-und-auswertung-der-daten)
  - [Hinweise zur Nachnutzung der Daten](#hinweise-zur-nachnutzung-der-daten)
<!-- TOC_END -->

<br>

<!-- HEADER_END -->



## Informationen zur Studie und zum Forschungskontext


### Administrative und organisatorische Angaben

Der Datensatz "SARS-CoV-2-Nowcasting und -R-Schätzung" wird vom Robert Koch-Institut im Zusammenhang mit der SARS-CoV-2-Pandemie bereitgestellt. Autor des Datensatzes ist [Matthias an der Heiden](https://orcid.org/0000-0001-5863-4549), wissenschaftlicher Mitarbeiter des [Fachgebiet 34 | HIV/AIDS und andere sexuell oder durch Blut übertragbare Infektionen](https://www.rki.de/fg34) des RKI. Inhaltliche Fragen bezüglich des Nowcastings und der R-Schätzungen können an an das RKI unter [info@rki.de](mailto:info@rki.de) gestellt werden. Das Nowcasting und die R-Schätzung erfolgt seit März 2020 und wird täglich aktualisiert.  
Die Datenkuration sowie das Qualitätsmanagement der (Meta-)Daten erfolgt durch [Justus Benzler](https://orcid.org/0000-0002-7470-0849), [Fachgebiet 32 | FG 32 | Surveillance und elektronisches Melde- und Informationssystem (DEMIS) | ÖGD Kontaktstelle](https://www.rki.de/fg32) und [Hannes Wünsche](https://orcid.org/0000-0002-8837-0326), Fachgebiet [MF 4 | Fach- und Forschungsdatenmanagement](https://www.rki.de/mf4) des RKI. Fragen zum Datenmanagement und zur Publikationsinfrastruktur können an das Open Data Team des Fachgebiets MF4 unter [OpenData@rki.de](mailto:OpenData@rki.de) gerichtet werden.


### Inhalt und Aufbau des Datensatzes

Der Datensatz enthält die epidemiologischen Schätzungen über den Verlauf der SARS-CoV-2-Infektionen in Deutschland und der daraus resultierenden Reproduktionszahl. Weiterhin enthält er grundlegende Metadaten sowie die Datensatzdokumentation und die in ihr zitierten wissenschaftlichen Publikationen. Im Datensatz enthalten sind:  

- Tabelle mit täglichen Fallzahlenschätzungen und R-Wert-Angaben  
- Archiv mit der Sammlung bisheriger Fallzahlenschätzungen und R-Wert-Angaben  
- Lizenz-Datei mit der Nutzungslizenz des Datensatzes in Deutsch und Englisch  
- Datensatzdokumentation und auf den Datensatz bezogene Publikationen in deutscher Sprache  
- Metadaten-Datei zum Import in Zenodo  


## Aufbereitung und Auswertung der Daten

Es besteht ein großes Interesse daran, das aktuelle Infektionsgeschehen und die zeitliche Entwicklung der Zahlen von SARS-CoV-2-Infektionen und Covid-19-Erkrankungsfällen in Deutschland zeitnah darzustellen und zu verstehen. Aufgrund unvermeidbarer Verzüge kann niemand die tatsächliche Anzahl der heute oder in der vergangenen Woche erfolgten Infektionen genau wissen oder bestimmen. Erst wenn die betroffenen Personen positiv getestet wurden, kann deren Anzahl in einem Erhebungssystem erfasst und analysiert werden.  
Ganz allgemein gilt jedoch, dass nicht alle infizierten Personen Symptome entwickeln, dass nicht alle, die Symptome entwickeln, eine Arztpraxis aufsuchen, dass nicht alle, die zum Arzt gehen, getestet werden, und dass nicht alle, die positiv getestet werden, auch in einem Erhebungssystem erfasst werden. Außerdem vergeht zwischen all diesen einzelnen Schritten eine gewisse Zeit, so dass kein Erhebungssystem, und sei es noch so gut, ohne zusätzliche Annahmen und Berechnungen eine Aussage über das aktuelle Infektionsgeschehen machen kann.  
In Deutschland werden gemäß der Meldepflicht nach Infektionsschutzgesetz (IfSG) Infektionen mit SARS-CoV-2 von den diagnostizierenden Ärzten und Laboren an die zuständigen Gesundheitsämter gemeldet und von diesen über die zuständigen Landesbehörden an das Robert Koch-Institut übermittelt.  

### Methoden, Instrumente und Verlauf der Datengenerierung

Grundlage der Berechnungen des Nowcastings und der R-Schätzungen sind die aktuellen, durch die Gesundheitsämter an des Robert Koch-Institut gemeldeten, SARS-CoV-2-Infektionen in Deutschland. Die öffentlich zur Verfügung gestellten Daten der Infektionsmeldungen sind im [SARS-CoV-2 Daten-Dashboard des RKI](https://npgeo-corona-npgeo-de.hub.arcgis.com/datasets/dd4580c810204019a7b8eb3e0b329dd6_0/data), auf  [GitHub](https://github.com/robert-koch-institut/SARS-CoV-2_Infektionen_in_Deutschland) und in [Zenodo](https://doi.org/10.5281/zenodo.4681153) abrufbar. Auf Basis der gemeldeten SARS-CoV-2-Infektionen erfolgen die Fallzahlenschätzungen und die R-Wert-Berechnung in folgenden Schritten:   

1. Multiple Imputation fehlender Information zum Erkrankungsbeginn von COVID-19-Fällen unter einer Missing-at-Random-Annahme 
2. Korrektur der Anzahl von Neuerkrankungen für den Diagnose-, Melde- und Übermittlungsverzug mittels des Nowcasting-Verfahrens
3. Berechnung der zeitlich variierenden Reproduktionszahl unter der Annahme einer Generationszeit von 4 Tagen 

Eine detaillierte Beschreibung der Methoden, Instrumente und des Verlaufs der Datengenerierung findet sich in folgenden Publikationen, die ebenfalls im Datensatz enthalten sind:

>an der Heiden, M; Hamouda, O (2020): Schätzung der aktuellen Entwicklung der SARS-CoV-2-Epidemie in Deutschland – Nowcasting. Epid Bull, S.10–16. [DOI: 10.25646/6692.4](http://dx.doi.org/10.25646/6692.4)

>Robert Koch-Institut (2020): Erläuterung der Schätzung der zeitlich variierenden Reproduktionszahl R. RKI. [DOI:10.25646/8164](https://doi.org/10.25646/8164)



### Daten und Datenaufbereitung

Der Datensatz enthält die Tabelle mit dem Nowcasting der aktuellen Infektionen und der sich daraus ergebenden R-Werte. Diese sind im Hauptverzeichnis unter "Nowcast_R_aktuell.csv" abrufbar und werden täglich überschrieben. Im Archivordner sind das Nowcasting und die R-Schaetzung unter den Dateinamen "Nowcast_R_JJJJ-MM-TT.csv" enthalten. Im Dateinamen repräsentiert die Sequenz "JJJJ-MM-TT" das Erstellungsdatum der Datei und damit gleichzeitig das Datum des enthaltenen Datenstands. "JJJJ" steht dabei für das Jahr, "MM" für den Monat und "TT" für den Tag der Erstellung bzw. des enthaltenen Datenstands.   

>Nowcast_R_aktuell.csv  
>Archiv/Nowcast_R_JJJJ-MM-TT.csv  

Die Tabelle des Nowcastings und der R-Schätzung wurden täglich um die Zeile der Daten des vergangenen Tages erweitert. Die Fallzahlenschätzungen und R-Wert-Angaben bilden einen tagesaktuellen Stand (00:00 Uhr) des Publikationsdatums ab.  
Die Schätzwerte zur Anzahl von Neuerkrankungen und der R-Schätzung zu früheren Tagen können von den Angaben in früheren Versionen der Tabelle abweichen, weil täglich der Gesamtverlauf, aufgrund der aktuell verfügbaren Daten, neu geschätzt wird.

#### Variablen des Nowcastings und der R-Schätzung 

Drei zentrale Variablen sind im Nowcasting und in der R-Schätzung für jeden Tag JJJJ-MM-TT abgebildet:

- Punktschätzer der Anzahl an Neuerkrankungen (ohne Glättung)
    - ohne Glättung: ohne Bildung eines gleitenden Mittelwerts
- Punktschätzer der Anzahl an Neuerkrankungen (mit Glättung)
    - mit Glättung: unter Bildung eines gleitenden Mittelwerts über 4 Tage
    - jeder Wert mit den Werten der 3 vorhergehenden Tage gemittelt
- Punktschätzer des 7-Tage-R-Werts

Zu jeder dieser Variablen ist darüber hinaus das 95%-Prädiktionsintervall mit einer Ober- und einer Untergrenze angegeben.

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Nowcast_R_aktuell", "lang": "de"} -->

Die Datei [Nowcast_R_aktuell.csv](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/blob/main/Nowcast_R_aktuell.csv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_Nowcast_R_aktuell.json](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/blob/main/Metadaten/schemas/tableschema_Nowcast_R_aktuell.json) hinterlegt:
> [tableschema_Nowcast_R_aktuell.json](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/blob/main/Metadaten/schemas/tableschema_Nowcast_R_aktuell.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable               | Typ     | Ausprägungen         | Beschreibung                                                                                                                                              |
|:-----------------------|:--------|:---------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Datum                  | date    | Format: `YYYY-MM-DD` | Datum (im Format JJJJ-MM-TT) der geschätzten Neuinfektionen und der sich ergebenden R-Werte. JJJJ entspricht der Jahreszahl, MM dem Monat und TT dem Tag. |
| PS_COVID_Faelle        | integer | Werte: `≥0`          | Punktschätzer der Anzahl an Neuerkrankungen (ohne Glättung)                                                                                               |
| UG_PI_COVID_Faelle     | integer | Werte: `≥0`          | Untere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (ohne Glättung                                                                  |
| OG_PI_COVID_Faelle     | integer | Werte: `≥0`          | Obere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (ohne Glättung)                                                                  |
| PS_COVID_Faelle_ma4    | integer | Werte: `≥0`          | Punktschätzer der Anzahl an Neuerkrankungen (mit Glättung)                                                                                                |
| UG_PI_COVID_Faelle_ma4 | integer | Werte: `≥0`          | Untere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (mit Glättung)                                                                  |
| OG_PI_COVID_Faelle_ma4 | integer | Werte: `≥0`          | Obere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (mit Glättung)                                                                   |
| PS_7_Tage_R_Wert       | number  | Werte: `≥0`          | Punktschätzer des 7-Tage-R-Werts                                                                                                                          |
| UG_PI_7_Tage_R_Wert    | number  | Werte: `≥0`          | Untere Grenze des 95%-Prädiktionsintervalls des 7-Tage-R-Werts                                                                                            |
| OG_PI_7_Tage_R_Wert    | number  | Werte: `≥0`          | Obere Grenze des 95%-Prädiktionsintervalls des 7-Tage-R-Werts                                                                                             |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->


#### Formatierung der Nowcasting-und-R-Schätzung-Tabelle 

Das Nowcasting und die R-Schätzung sind im Datensatz als kommaseparierte .csv-Datei enthalten. Der verwendete Zeichensatz der .csv-Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Komma ",". Datumsangaben sind im ISO-8601-Standard formatiert.

* Zeichensatz: UTF-8  
* Datumsformat: ISO 8601  
* .csv-Trennzeichen: Komma ","  


<!-- FOOTER_START: {"lang": "de"} -->



### Metadaten  

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:  

> [Metadaten/](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/tree/main/Metadaten/) 

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/blob/main/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.
 
> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/blob/main/Metadaten/zenodo.json)  

In der zenodo.json ist neben dem Publikationsdatum (`"publication_date"`) auch der Datenstand in folgendem Format enthalten (Beispiel):  

```
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Collected",
      "description": "Date when the Dataset was created"
    }
  ],
```    


Zusätzlich beschreiben wir tabellarische Daten mithilfe des [Data Package Standards](https://datapackage.org/).
Ein Data Package ist eine strukturierte Sammlung von Daten und zugehörigen Metadaten, die den Austausch und die Wiederverwendung von Daten erleichtert. Es besteht aus einer datapackage.json-Datei, die zentrale Informationen wie die enthaltenen Ressourcen, ihre Formate und Schema-Definitionen beschreibt.

Der Data Package Standard wird von der [Open Knowledge Foundation](https://okfn.org/) bereitgestellt und ist ein offenes Format, das eine einfache, maschinenlesbare Beschreibung von Datensätzen ermöglicht.

Die Liste der in diesem Repository enthaltenen Daten ist in folgender Datei hinterlegt:

> [datapackage.json](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/tree/main/datapackage.json)

Für tabellarische Daten definieren wir zusätzlich ein [Table Schema](https://datapackage.org/standard/table-schema/), das die Struktur der Tabellen beschreibt, einschließlich Spaltennamen, Datentypen und Validierungsregeln. Diese Schema-Dateien finden sich unter:

> [Metadaten/schemas/](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/tree/main/Metadaten/schemas) 



## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:  

- https://zenodo.org/communities/robertkochinstitut  
- https://github.com/robert-koch-institut  
- https://gitlab.opencode.de/robert-koch-institut  
- https://edoc.rki.de/  
 
### Lizenz  

Der Datensatz "SARS-CoV-2-Nowcasting und -R-Schaetzung" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/blob/main/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/SARS-CoV-2-Nowcasting_und_-R-Schaetzung/blob/main/LIZENZ) Datei des Datensatzes.  
<!-- FOOTER_END -->