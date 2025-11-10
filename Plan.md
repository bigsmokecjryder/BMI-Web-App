BMI Web App — Plan

1) Ziel & Scope

Eine kleine, modulare Web‑App zum Erfassen von Körperdaten (Gewicht & Größe), zur BMI‑Berechnung, Zielverfolgung und Visualisierung der Entwicklung

Out‑of‑scope v1: Benutzerverwaltung/Accounts, Synchronisation über Geräte, medizinische Beratung.

2) Kernfunktionen

Formular (Eingabe)
    Felder: Datum (default heute), Gewicht (kg), Größe (cm) [optional fix pro Nutzer], Notiz (optional).

    BMI direkt berechnet und angezeigt

    Validierung: Pflichtfelder, Bereichsprüfung (z. B. 30–300 kg, 120–230 cm), Nummernformat, leere Notizen erlaubt

    UX: Sofort‑Feedback, Fehlerhinweise, Tastatur‑/Enter‑Submit, Loader/Disable während Save

Ziele (Tabellen‑Ansicht)

    Anlegen eines Zielgewichts mit Stichtag

    Status/Progress (Gewicht, verbleibende Tage, Ampel‑Indikator)

    CRUD: Ziel erstellen/ändern/löschen, jeweils mit Bestätigung

Graphen (Kurven)

    Liniengraph Gewicht über Zeit; optional zweite Achse mit BMI‑Kurve.

    Aggregationen: letzte 7/30/90 Tage; Durchschnitt, Min/Max, Trendlinie.


Dashboard

    Kacheln: Aktuelles Gewicht, aktueller BMI + Kategorie (Untergewicht/Normal/Über/Adipositas), Veränderung nach 7 Tagen