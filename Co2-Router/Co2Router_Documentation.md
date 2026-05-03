# CO₂-Router Dokumentation

## Überblick des Projekts

CO₂-Router ist eine Web-Anwendung zur nachhaltigen Routenplanung. Nutzer definieren Start, Ziel und optionale Zwischenstopps und vergleichen verschiedene Verkehrsmittel nach CO₂-Emissionen, Dauer und Komfort. Die Kernfunktionen sind:

- Intuitive Routenplanung mit Start, Ziel und Checkpoints
- Vergleich von Auto, Zug, Flugzeug, Fahrrad, Fähre und ÖPNV
- Konfiguration von Fahrzeugtyp, Antrieb, Personenzahl und Streckentyp
- Visualisierung von Emissionen, Reisezeit und Strecke

## Benutzeroberfläche

Das Design ist übersichtlich strukturiert. Die Startseite zeigt die Reiseplanung und die wichtigsten Filteroptionen.

![Startseite mit Route-Planning-Interface](images/LandingPage.png)

Die Oberfläche kombiniert Eingabefelder mit Kartenansicht und ermöglicht schnelle Vergleiche zwischen verschiedenen Verkehrsmitteln.

Die Checkpoint-Verwaltung und Vorschlagsfunktionen sind direkt in die UI integriert.

| Checkpoint hinzufügen | Vorschlag-Cache |
|---|---|
| ![Checkpoint hinzufügen](images/CheckpointsHinzugfuegen.png) | ![Vorschlag-Cache](images/SuggestionsCache.png) |

Diese Ansicht zeigt, wie Zwischenstopps hinzugefügt und Vorschläge im Hintergrund zwischengespeichert werden, um Eingaben schneller zu machen.

Die Adresssuche liefert intelligente Vorschläge in mehreren Schritten. Höheorientierte Eingabefelder passen gut nebeneinander.

| PLZ-Vorschläge | Straßenvorschläge |
|---|---|
| ![PLZ-Vorschläge](images/SuggestionsPlzEingegeben.png) | ![Straßenvorschläge](images/SuggestionsStraßeEingegeben.png) |

Diese Screenshots zeigen die inkrementelle Suche für Postleitzahl und Straße sowie das schnelle Auffüllen relevanter Adressdaten.

| Hausnummer-Vorschläge | Cache-Optimierung |
|---|---|
| ![Hausnummer-Vorschläge](images/SuggestionsHausnummerEingegeben.png) | ![Cache-Optimierung](images/SuggestionsCache.png) |

## Routenplanung und Transportwahl

Die Route Berlin–Zürich zeigt Auswahl und Filterung verschiedener Verkehrsmittel.

![Komplette Routendarstellung Berlin–Zürich](images/BerlinToZürich.png)

Hier wird die gesamte Reisestrecke visualisiert und die gewählte Route klar auf der Karte dargestellt.

| Gefilterte Gesamtroute | Autofahrten im Detail |
|---|---|
| ![Gefilterte Gesamtroute](images/BerlinToZürich_Filtered.png) | ![Autofahrten im Detail](images/BerlinToZürich_Filtered_Car.png) |

Fahrzeugkonfiguration wird kompakt dargestellt, auch Elektrofahrzeuge mit mehreren Passagieren.

| Fahrzeugeinstellungen | Elektrofahrzeug für 6 Personen |
|---|---|
| ![Fahrzeugeinstellungen](images/CarSettings.png) | ![Elektrofahrzeug für 6 Personen](images/CarSettings_Electric_6Persons.png) |

Die App zeigt auch Flughafen-Zu-/Abfahrtoptionen und Fähren als Alternativen.

| Flughafen mit Auto | Flughafen mit Bahn |
|---|---|
| ![Flughafen mit Auto](images/PlaneAirportByCar.png) | ![Flughafen mit Bahn](images/PlaneAirportByTrain.png) |

Diese Beispiele zeigen unterschiedliche Zugangsmöglichkeiten zum Flughafen, um die Kosten und Emissionen vorab zu vergleichen.

![Fährenoption als nachhaltige Alternative](images/Fähre.png)

Die Fähre bildet eine umweltfreundliche Option für Strecken, bei denen Wasserwege genutzt werden können.

## Visualisierung

Die Kernanalyse erfolgt über Vergleichsdiagramme, die CO₂-Emissionen, Dauer und Distanz miteinander verbinden.

| Vergleichsdiagramm | Hover-Details |
|---|---|
| ![Vergleichsdiagramm](images/TransportModesComparisonVisualization.png) | ![Hover-Details](images/TransportModesComparisonVisualizationHover.png) |

Die Analyse basiert auf den Kennzahlen CO₂, Dauer, Distanz und Stopps. Diese Werte ermöglichen den Vergleich von Bahn, Auto, Flugzeug, Fahrrad und Fähre.

## Fazit

CO₂-Router bietet eine klare Übersicht für nachhaltige Mobilitätsentscheidungen. Die Kombination aus Routenplanung, dynamischer Vergleichsansicht und Smart-Search hilft Nutzern, Alternativen zu erkennen und ihre Reise umweltfreundlicher zu gestalten.

### Stärken der Anwendung

- Übersichtliche Benutzerführung
- Klare Emissionsvergleiche
- Flexible Checkpoints und Filter
- Beschreibbare Fahrzeugoptionen

### Potentielle Erweiterungen

- Echtzeit-CO₂-Tracking
- Integration in Buchungssysteme
- Ridesharing-Optionen
- Mehr interaktive Karten
