# Automatisierung-eines-Sammelbeckens

Dieses Projekt wurde im Rahmen eines Hochschulprojekts im Team (2 Personen) entwickelt und umfasst die Planung, Programmierung und Umsetzung eines automatisierten Sammelbecken-Systems.

---

### Meine Aufgaben

- Entwicklung der SPS-Logik in Siemens TIA Portal (SCL)
- Umsetzung der Steuerung für Füll- und Entleerprozesse
- Implementierung der Motorsteuerung (Stern-Dreieck)
- Erstellung der HMI-Visualisierung
- Analyse und Test des Systems unter realitätsnahen Bedingungen

---

### Systembeschreibung

Das System steuert ein Sammelbecken mithilfe von Sensoren zur Füllstandserkennung sowie Ventilen und einem Motor zur Regelung des Wasserflusses.

Die Steuerung umfasst:
- Automatisches Befüllen und Entleeren
- Zustandsüberwachung über HMI
- Motorsteuerung mit Stern-Dreieck-Umschaltung
- Sicherheitslogik für den Betrieb

---

### Technologien

- Siemens TIA Portal (S7, SCL)
- HMI (Siemens Panel)
- EPLAN Electric P8

---

### HMI Visualisierung

**Simulation (TIA Portal):**

![HMI Simulation](image/hmi_simulation_1.jpg)

**Reales System (Siemens HMI):**

![HMI Real](image/hmi_real_1.png)
![HMI Real](image/hmi_real_2.png)

---

### Code (Auszug)

![Code Main OB](image/code_1_Main_OB.png)
![Code Stern-Dreieck](image/code_2_Stern_Dreieck_Umschaltung.png)

---

### Dokumentation

- EPLAN Schaltplan: `docs/EPLAN Schaltplan.pdf`
- Stückliste: `docs/bill_of_materials.pdf`
- Produktionskosten: `docs/Produktionskosten.pdf`

---

### Hinweis

Dieses Repository zeigt die wesentlichen Bestandteile des Projekts.  
Der vollständige SPS-Code ist projektbedingt nicht vollständig enthalten.
