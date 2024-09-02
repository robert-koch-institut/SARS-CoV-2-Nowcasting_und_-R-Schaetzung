### Variable specification for data file `frictionless_data_schema_Nowcast_R_aktuell`

| Variable               | Typ     | Ausprägungen       | Beschreibung                                                                                                                                              |
|:-----------------------|:--------|:-------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Datum                  | date    | Format: `%Y-%m-%d` | Datum (im Format JJJJ-MM-TT) der geschätzten Neuinfektionen und der sich ergebenden R-Werte. JJJJ entspricht der Jahreszahl, MM dem Monat und TT dem Tag. |
| PS_COVID_Faelle        | integer | Minimum: 0         | Punktschätzer der Anzahl an Neuerkrankungen (ohne Glättung)                                                                                               |
| UG_PI_COVID_Faelle     | integer | Minimum: 0         | Untere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (ohne Glättung                                                                  |
| OG_PI_COVID_Faelle     | integer | Minimum: 0         | Obere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (ohne Glättung)                                                                  |
| PS_COVID_Faelle_ma4    | integer | Minimum: 0         | Punktschätzer der Anzahl an Neuerkrankungen (mit Glättung)                                                                                                |
| UG_PI_COVID_Faelle_ma4 | integer | Minimum: 0         | Untere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (mit Glättung)                                                                  |
| OG_PI_COVID_Faelle_ma4 | integer | Minimum: 0         | Obere Grenze des 95%-Prädiktionsintervalls der Anzahl an Neuerkrankungen (mit Glättung)                                                                   |
| PS_7_Tage_R_Wert       | number  | Minimum: 0         | Punktschätzer des 7-Tage-R-Werts                                                                                                                          |
| UG_PI_7_Tage_R_Wert    | number  | Minimum: 0         | Untere Grenze des 95%-Prädiktionsintervalls des 7-Tage-R-Werts                                                                                            |
| OG_PI_7_Tage_R_Wert    | number  | Minimum: 0         | Obere Grenze des 95%-Prädiktionsintervalls des 7-Tage-R-Werts                                                                                             |


