from datetime import date


 

versuchsleiter: str = "Simon Schwarzer"

erstellungsdatum: str = date.today().isoformat()

first_experiment_id: int = 100

experimente: list[dict] = []

 

# Schleife zum Erstellen der 10 Experimente

for i in range(10):

experiment: dict = {

"ID_Nummer": first_experiment_id + i,

"Versuchsleiter": versuchsleiter,

"Erstellungsdatum": erstellungsdatum,

"Testname": f"Leistungstest {i+1}",

"Beschreibung": f"Durchführung von Leistungstest {i+1} zur Bewertung der Leistungsfähigkeit."

}

experimente.append(experiment)

 

# Zweite Schleife zum Anzeigen der ersten fünf Experimente

print("\nDie ersten fünf Experimente:")

for experiment in experimente[:5]:

print(experiment)

 

# Schleife zum Zählen und Anzeigen der Experimente mit einer geraden ID

print("\nExperimente mit einer geraden ID:")

for experiment in experimente:

if experiment["ID_Nummer"] % 2 == 0:

print(experiment) # Gibt das Experiment mit einer geraden ID aus
