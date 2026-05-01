# Automatisierung eines Sammelbeckens

Dieses Projekt wurde im Rahmen eines Hochschulprojekts im Team (2 Personen) entwickelt und umfasst die Planung, Programmierung und Umsetzung eines automatisierten Sammelbecken-Systems.

---

### Meine Aufgaben

* Entwicklung der SPS-Logik in Siemens TIA Portal (SCL)
* Umsetzung der Steuerung für Füll- und Entleerprozesse
* Implementierung der Motorsteuerung (Stern-Dreieck)
* Erstellung der HMI-Visualisierung
* Elektroplanung und Schaltplanerstellung mit EPLAN Electric P8
* Analyse und Test des Systems unter realitätsnahen Bedingungen

---

### Systemübersicht

Das System steuert ein Sammelbecken mithilfe von Sensoren zur Füllstandserkennung sowie Ventilen und einem Motor zur Regelung des Wasserflusses.

Funktionen:

* Automatisches Befüllen und Entleeren
* Zustandsüberwachung über HMI
* Motorsteuerung mit Stern-Dreieck-Umschaltung
* Sicherheitslogik für den Betrieb

---

### EPLAN – Leistungsteil

![Leistungsteil](image/eplan_power.png)

Darstellung des Leistungsstromkreises inklusive Motoransteuerung und Schutzkomponenten.

---

### EPLAN – Steuerung & HMI

![Steuerung](image/eplan_control.png)

Integration von SPS (Siemens S7-1200), HMI und Ein-/Ausgangssignalen.

---

### Schaltschrankaufbau

![Schaltschrank](image/cabinet_layout.png)

Mechanischer Aufbau und Anordnung der Komponenten im Schaltschrank.

---

### HMI Visualisierung

Simulation (TIA Portal):

![HMI Simulation](image/hmi_simulation_1.jpg)

Reales System:

![HMI Real](image/hmi_real_1.png)
![HMI Real](image/hmi_real_2.png)

---

### Code (Auszug)

![Main OB](image/code_1_Main_OB.png)

Ablaufsteuerung des Systems im Hauptprogramm.

![Stern-Dreieck](image/code_2_Stern_Dreieck_Umschaltung.png)

Motorsteuerung mit Stern-Dreieck-Umschaltung.

---

### Dokumentation

#### EPLAN Schaltplan

[PDF öffnen](docs/EPLAN%20Schaltplan.pdf)

Übersicht über den vollständigen elektrischen Aufbau und die Verdrahtung.

---

#### Stückliste (BOM)

[PDF öffnen](docs/bill_of_materials.pdf)

Alle verwendeten Komponenten und Materialien im System.

---

#### Produktionskosten

[PDF öffnen](docs/Produktionskosten.pdf)

![Kosten Vorschau](image/cost_preview.png)

Kalkulation der Material- und Herstellungskosten.

---

### Hinweis

Dieses Repository zeigt die wesentlichen Bestandteile des Projekts.
Der vollständige SPS-Code ist projektbedingt nicht vollständig enthalten.

---

### Autor

Ayoub Khichi
Elektrotechnik (B. Eng.)
Hochschule Koblenz
