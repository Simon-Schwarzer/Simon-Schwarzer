Name und Identifikationsnummer

Alarm bei zu hoher Herzfrequenz (UC1.03)
Beschreibung

Ärztliche Untersuchung, ob Patient gesundheitlich geeignet ist + Notiz: Faktoren, die Ergebnis manipulieren könnten
Leiter/in notiert zunächst das Alter der Patient/in und ordnet so die gemessene Herzfrequenz in drei Kategorien ein.
Messung der Herzfrequenz bei einer Versuchsperson
Grüne Zone: unbedenkliche/ gesunde Herzfrequenz;
Orangene Zone: knapp vor kritischer Zone, System gibt Warnung aus
Rote Zone: Test: Schwarze Zone + Notarzt; Alaarmmmm
Anpassung der Zone durch medizinisches Fachpersonal
Beteiligte Akteure

Patienten
Ärztliches Personsal
Interviewer
Versuchsleiter
Verwendete Anwendungsfälle

UC 1.01 Probant/in anlegen
UC 1.02 Leistungstest anlegen
Auslöser

Prüfung der kardialen Beanspruchung
Vorbedingungen

Patient/in ist im System angelegt
Test wurde durchgeführt
Kategorisierung ist erfolgreich durchgeführt worden
Invarianten

Backup auf einer Festplatte
Neustart am Anfang des aktuellen Versuchs, Kontrolle der erhobenen Werte
Nachbedingungen/Ergebnis

Auswertung der drei Zonen

Zone, Alter, Herzfrequenz rote Zone: für alle Alterstufen: unter 60 20, ab 180; 30, ab 171; 40, ab 162; 50, ab 153; 60, ab 144; 70, ab 135;

orange Zone: 20: 150-179; 30: 143-170; 40: 135-161; 50: 128-152; 60: 120-143; 70: 113-134;

grüne Zone: 20: 120-149; 30: 114-142; 40: 108-134; 50: 102-127; 60: 96-119; 70: 90-112;

Standartablauf

Anlegen der Patient/in mit Name, Alter, Patient-ID und Anamnese (+ Versicherungsdaten)
Der Versuchsleiter wählt im System den Leistungstest und Patient/in aus.
Interviewer/in protokolliert Zeitpunkt und Messdaten.
Interviewer/in speichert die Eingabe.
System bestätigt die Speicherung der Werte.
Alternative Ablaufschritte

Fehlermeldung: Probant/in nicht gefunden
Fehlermeldung: ungültiger Wert
Interviewer/in kann Eingabe korrigieren, System overriden (Wert trotzdem speichern; Patient mit angegebenen Daten speichern), Spezialfall eingeben: Erste Hilfe benötigt
Hinweise

keine weiteren Hinweise
Änderungsgeschichte

Version 1
Name der Autor: Simon Schwarzer
Datum: 17.03.2025


