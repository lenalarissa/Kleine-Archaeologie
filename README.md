<img width="8206" height="4898" alt="Projektstudium_Kleine Archäologie_Dokumentation (verschoben) 2" src="https://github.com/user-attachments/assets/48da9755-0147-4a7c-926f-3b32f4d11b6c" />

---

**HTW Berlin – Fachbereich 4: Informatik in Kultur und Gesundheit**  
**Projektstudium Sommersemester 2023**  
Dozenten: Julien Letellier, Prof. Dr. Dr. Jürgen Sieck  

Projektteam: Lena Heisel, Lennart Kaul, Christopher Kohardjo, Zidanie Mazamo,  
Merveille Nguetsa, Laurie Njonkoe, Hien Tran, Johanna Winkens  

---

## Überblick

**Kleine Archäologie** ist eine Augmented-Reality-Anwendung für das  
**Archäologische Landesmuseum Brandenburg**.  
Das Projekt wurde im Rahmen des Projektstudiums an der HTW Berlin entwickelt und richtet sich an Kinder ab 9 Jahren.  
Ziel ist es, spielerisch Interesse an Archäologie zu wecken und Wissen über Objekte aus der Steinzeit zu vermitteln.

Die Anwendung verbindet **Gamification** mit **Augmented Reality (AR)**:  
Kinder bewegen sich durch die Ausstellung, suchen bestimmte Objekte mithilfe von Hinweisen und scannen sie, um sie als interaktive 3D-Modelle zu erleben.

---
<img width="3772" height="1727" alt="bilder" src="https://github.com/user-attachments/assets/d0e12bc7-21a4-4260-9a73-7c5f01e1db12" />

---

## Zielsetzung

- Förderung des Interesses von Kindern an Geschichte und Archäologie  
- Digitale Erweiterung der Dauerausstellung des Museums  
- Vereinfachter Zugang zu Wissen über Exponate  
- Verbindung von Lernen und Spiel durch AR-Technologie  

---

## Konzept

- **Technologie:** Augmented Reality (AR) auf iPads  
- **Inhaltlicher Fokus:** Steinzeit (Alt-, Mittel- und Jungsteinzeit)  
- **Spielprinzip:**  
  - Die Kinder bewegen sich mit einem Tablet durch die Ausstellung.  
  - Sie erhalten Tipps, um ein Objekt zu finden.  
  - Nach dem erfolgreichen Scan erscheint das Objekt als 3D-Modell im Raum.  
  - Über eine interaktive Szene erfahren sie mehr über das Objekt.  

**Beispielhafte Objekte:**
- Backenzahn eines Wollhaarmammuts  
- Lochstab mit Zickzacklinien  
- Mahl- und Läuferstein  

---

## Anwendung und Ablauf

1. Start der App mit Begrüßungsbildschirm  
2. Auswahl der Sprache (Deutsch/Englisch)  
3. Spielerische Navigation über ein Spielfeld (Top-Down-Perspektive)  
4. Tippbasiertes Suchsystem (3 Hinweise pro Objekt)  
5. Scan des Museumsobjekts per Kamera  
6. Anzeige eines 3D-Scans in der AR-Szene  
7. Rückkehr zum Spielfeld, um weitere Objekte zu entdecken  
8. Abschlussbildschirm nach erfolgreicher Suche aller Objekte  

---

## Zielgruppe und Nutzungsszenarien

- Kinder ab 9 Jahren als Hauptzielgruppe  
- Eltern und Lehrkräfte als Begleitende  
- Museumspersonal zur Unterstützung pädagogischer Führungen  

**Anwendungsbeispiele:**
- Museumsbesuch mit Familien  
- Schulklassenführungen mit digitalen Aufgaben  
- Edutainment-Angebot zur Steigerung der Attraktivität des Museums  

---

## Verwendete Technologien

- **Unity (2021.3.25f1)** – Hauptentwicklungsumgebung  
- **AR Foundation (ARKit 5.0.7)** – Framework für AR-Entwicklung auf iOS  
- **Xcode** – Kompilierung und Deployment auf iPads  
- **LeanTouch** – Implementierung von Touch-Interaktionen (Drehen, Skalieren, Verschieben)  
- **Polycam** – 3D-Scans der Museumsobjekte (Photogrammetrie)  
- **Git & GitHub** – Versionskontrolle  
- **Figma & Miro** – Wireframes und Projektorganisation  
- **Vektornator** – Erstellung von UI-Elementen und Icons  

---

## Technische Umsetzung

- **Objekterkennung:**  
  - Marker-Tracking mit ARKit und Unity  
  - Erstellung von `.arobject`-Dateien als Referenzobjekte  
  - Einsatz von iPhone und iPad Pro für das Scannen  

- **AR-Integration:**  
  - Platzierung und Interaktion mit 3D-Modellen im Raum  
  - Nutzung von Touch-Gesten für Zoom, Rotation und Bewegung  

- **Spielfeld & Gamification:**  
  - Top-Down-Spielbrett mit Aktionsfeldern  
  - Bewegliche Spielfigur  
  - Fortschrittssystem und Siegesszene  
  - Rückkehr zu gelösten Aufgaben möglich  

- **Datenmanagement:**  
  - Persistenz über ein Singleton-Pattern  
  - Speicherung des Spielfortschritts und der Aktionsfelder  

---

## Evaluation

Die Anwendung wurde mehrfach im **Archäologischen Landesmuseum Brandenburg** getestet.  
Die Tests erfolgten mit Museumsmitarbeitenden und externen Personen nach der **Think-Aloud-Methode**.

**Wichtigste Erkenntnisse:**
- Anleitung zu textlastig → künftig animierte Anleitungen  
- Interaktion mit „Gefunden“-Szene und AR-Szene optimierungsbedürftig  
- Hohe Begeisterung für die 3D-Objekte und AR-Erlebnisse  

---

## Ergebnisse

- Voll funktionsfähige AR-Anwendung für das Museum  
- 3D-Scans der Objekte als digitale Assets verfügbar  
- Erweiterbare Anwendung: neue Objekte und Räume leicht integrierbar  
- Positive Rückmeldungen von Museum und Testpersonen  

---

## Ausblick

- Erweiterung um weitere Zeitabschnitte (Bronze-, Eisen-, Slawenzeit)  
- Animierte Tutorials für Scannen und AR-Interaktion  
- Erweiterte Mehrsprachigkeit (weitere Sprachen)  
- Implementierung eines Inventars und einer Mini-Map  
- Integration einer Content-Management-Funktion für das Museum  
- Fortlaufende Evaluation mit der Zielgruppe (Kinder)  

---

## Teamorganisation

Das Projektteam arbeitete in drei Untergruppen:

| Team | Aufgabenbereich |
|------|------------------|
| **Marker-Team** | Objekterkennung, Marker-Scans |
| **Scan-Team** | Erstellung und Aufbereitung der 3D-Scans |
| **Unity-Team** | AR-Implementierung, Spielfeld, UI, Spielmechanik |

Organisationstools: Discord (Kommunikation), Miro (Kanban-Board, Planung)

---

## Quellen (Auswahl)

- Mehler-Bicher, A. & Steiger, L. (2014): *Augmented Reality: Theorie und Praxis.* De Gruyter.  
- Afshar, J. (2023): *Hands-On Augmented Reality Development with Meta Spark Studio.* Apress.  
- Apple Developer Docs: *Scanning and detecting 3D objects.*  
- Autodesk: *Photogrammetrie-Software – Fotos in 3D-Scans.*  
- LeanTween (2021): *Use touch to scale, rotate and drag AR objects.*  
- UsabilityHome: *Thinking-Aloud Protocol.*
