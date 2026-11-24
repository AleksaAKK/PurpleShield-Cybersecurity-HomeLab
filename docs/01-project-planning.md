# 01 | Projektplanung

**Projekt:** PurpleShield – Cybersecurity HomeLab  
**Projektart:** Eigenständiges IT-Lernprojekt  
**Projektbeginn:** November 2026  
**Status:** In Bearbeitung  

---

## 1. Ausgangssituation (IST-Analyse)

Im Rahmen meiner Umschulung zur Fachinformatikerin für Systemintegration möchte ich meine theoretischen Kenntnisse durch praktische IT-Projekte erweitern.

Hierfür wird eine virtuelle Laborumgebung aufgebaut, in der unterschiedliche Betriebssysteme installiert, vernetzt, administriert und auf Sicherheitsaspekte untersucht werden können.

Die Laborumgebung ermöglicht kontrollierte Sicherheitstests innerhalb einer eigenen Infrastruktur.

## 2. Zielsetzung (SOLL-Konzept)

Ziel des Projekts ist der Aufbau einer funktionsfähigen, erweiterbaren und abgesicherten virtuellen IT-Infrastruktur.

Die Umgebung soll folgende Möglichkeiten bieten:

- Installation und Administration virtueller Maschinen
- Kommunikation zwischen unterschiedlichen Linux-Systemen
- Aufbau eines privaten Overlay-Netzwerks
- Sicherer Remote-Zugriff mittels SSH
- Analyse von Netzwerkdiensten und offenen Ports
- Durchführung autorisierter Sicherheitstests
- Systematische Fehleranalyse
- Technische Dokumentation aller Projektschritte

## 3. Hardware-Ressourcen

| Komponente | Spezifikation |
|---|---|
| Prozessor | Intel Core i7-10700 |
| Arbeitsspeicher | 16 GB DDR4 |
| Grafikkarte | NVIDIA GeForce RTX 3060 |
| Datenträger | SSD |
| Host-Betriebssystem | Windows 11 Pro |

Die vorhandene Hardware ermöglicht den parallelen Betrieb mehrerer virtueller Maschinen.

## 4. Software-Ressourcen

| Software | Verwendungszweck |
|---|---|
| VirtualBox | Virtualisierung |
| Kali Linux | Sicherheitsanalyse |
| Ubuntu Desktop | Linux-Testsystem |
| NetBird | Privates Overlay-Netzwerk |
| OpenSSH | Remote-Administration |
| Nmap | Netzwerk- und Portanalyse |
| Bash | Administration und Automatisierung |
| GitHub | Versionsverwaltung und Dokumentation |

## 5. Funktionale Anforderungen

| ID | Anforderung |
|---|---|
| FA-01 | Virtuelle Maschinen erstellen und betreiben |
| FA-02 | Netzwerkkommunikation zwischen den Systemen ermöglichen |
| FA-03 | Privates Overlay-Netzwerk einrichten |
| FA-04 | SSH-Zugriff mittels Schlüsselauthentifizierung ermöglichen |
| FA-05 | Netzwerkdienste und offene Ports analysieren |
| FA-06 | Netzwerkprobleme erkennen und beheben |
| FA-07 | Projektergebnisse dokumentieren |

## 6. Nichtfunktionale Anforderungen

| ID | Anforderung |
|---|---|
| NFA-01 | Sicherheit der Laborumgebung |
| NFA-02 | Nachvollziehbare Konfiguration |
| NFA-03 | Erweiterbarkeit der Infrastruktur |
| NFA-04 | Effiziente Ressourcennutzung |
| NFA-05 | Schutz personenbezogener und sensibler Daten |
| NFA-06 | Reproduzierbarkeit der Projektschritte |

## 7. Technische Konzeption

Die Laborumgebung basiert auf einem Windows-Host mit VirtualBox.

Innerhalb der Virtualisierungsplattform werden zwei Linux-Systeme betrieben:

- Kali Linux als System für Netzwerk- und Sicherheitsanalysen
- Ubuntu Desktop als Administrations- und Testsystem

NetBird stellt eine private Netzwerkverbindung zwischen den virtuellen Maschinen bereit.

Der Remote-Zugriff erfolgt über SSH mit Public-Key-Authentifizierung.

## 8. Projektphasen

| Phase | Tätigkeit | Status |
|---|---|---|
| 01 | Projektplanung | Abgeschlossen |
| 02 | Virtualisierung | Abgeschlossen |
| 03 | Netzwerkkonfiguration | Abgeschlossen |
| 04 | NetBird-Integration | Abgeschlossen |
| 05 | SSH-Konfiguration | Abgeschlossen |
| 06 | Netzwerkanalyse | Abgeschlossen |
| 07 | Fehleranalyse und Dokumentation | In Bearbeitung |
| 08 | System Hardening | Geplant |
| 09 | Firewall und Netzwerksegmentierung | Geplant |
| 10 | Security Monitoring | Geplant |

## 9. Risikoanalyse

| Risiko | Gegenmaßnahme |
|---|---|
| Fehlerhafte Netzwerkkonfiguration | Systematische Netzwerkdiagnose |
| Ressourcenüberlastung | Angepasste VM-Ressourcenzuweisung |
| Verlust von Konfigurationen | Snapshots und Backups |
| Unbefugter Zugriff | Zugriffsbeschränkungen und SSH-Schlüssel |
| Veröffentlichung sensibler Daten | Anonymisierung der Dokumentation |
| Unbeabsichtigte externe Sicherheitstests | Beschränkung auf autorisierte Testsysteme |

## 10. Sicherheitskonzept

Sicherheitstests werden ausschließlich innerhalb der eigenen, autorisierten Laborumgebung durchgeführt.

Folgende Sicherheitsmaßnahmen sind Bestandteil des Projekts oder für die weitere Umsetzung vorgesehen:

- SSH Public-Key-Authentifizierung
- Verschlüsselte Netzwerkkommunikation
- Regelmäßige Systemaktualisierungen
- Kontrollierte Zugriffsberechtigungen
- Firewall-Konfiguration
- Netzwerksegmentierung
- Schutz sensibler Konfigurationsdaten

Private Schlüssel, Zugangsdaten, persönliche IP-Adressen und vertrauliche Systeminformationen werden nicht veröffentlicht.

## 11. Abnahmekriterien

Die erste Ausbaustufe gilt als erfolgreich umgesetzt, wenn:

- Beide virtuellen Maschinen funktionsfähig sind.
- Die Netzwerkkommunikation erfolgreich getestet wurde.
- Beide Systeme über NetBird erreichbar sind.
- Die SSH-Schlüsselauthentifizierung funktioniert.
- Netzwerkdienste mittels Nmap analysiert werden können.
- Die Implementierung nachvollziehbar dokumentiert ist.

## 12. Erwarteter Lernerfolg

Durch dieses Projekt vertiefe ich meine praktischen Kenntnisse in folgenden Bereichen:

- IT-Projektplanung
- Systemintegration
- Virtualisierung
- Netzwerktechnik
- Linux-Administration
- IT-Sicherheit
- Fehleranalyse
- Technische Dokumentation

---

[Zurück zur Projektübersicht](../README.md)

**PurpleShield | Build. Secure. Test. Learn.**
