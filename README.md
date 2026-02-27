# SOC Incident Analysis – Verdächtige Login-Aktivität (Lab Portfolio)
Dieses Repository enthält strukturierte SOC-Incident-Analysen aus einer kontrollierten Laborumgebung. Es demonstriert praktische Fähigkeiten in SIEM‑Triage, Log‑Analyse, Root‑Cause‑Analyse (RCA) und der Ableitung von Handlungsempfehlungen. Die Inhalte dienen als Portfolio praktischer SOC‑Arbeiten für Lernzwecke, Dokumentation und berufliche Weiterentwicklung.

SOC Incident Analysis – Suspicious Login Activity (Lab Portfolio)
This repository contains structured SOC incident analyses from a controlled lab environment.
It demonstrates practical skills in SIEM triage, log analysis, root cause analysis (RCA), and remediation recommendations.
The content is intended as a portfolio of practical SOC work for learning, documentation, and professional development.

## 📌 Projektübersicht
Analyse eines simulierten SOC-Falls mit verdächtigen Login-Aktivitäten und möglichem Malware-Verdacht in einer virtuellen Laborumgebung.

## 🎯 Ziel des Projekts
- Analyse und Bewertung eines SIEM-Alarms
- Durchführung einer Incident-Triage
- Empfehlung geeigneter Gegenmaßnahmen

## 🧪 Umgebung & Setup
- VMware (Oracle VM VirtualBox)
- Kali Linux (Angreifer)
- Metasploitable (Zielsystem)

## 🛠️ Tools & Technologien
- SIEM
- EDR
- Wireshark

## 🧩 Szenario
Ein SIEM-Alarm meldete mehrere fehlgeschlagene Login-Versuche, gefolgt von einem erfolgreichen Zugriff aus einer ungewöhnlichen Quelle.

## 🔍 Analyse & Vorgehen
1. Analyse der Authentifizierungs-Logs im SIEM  
2. Überprüfung der Endpoint-Aktivitäten im EDR  
3. Korrelation von Netzwerkdaten mit Wireshark  
4. Identifikation verdächtiger IP-Adressen
5. Bewertung des Angriffspfads und möglicher Kompromittierung

## 📊 Ergebnisse
- Einstufung: True Positive  
- Hinweise auf Brute‑Force‑Versuch mit anschließendem erfolgreichen Login
- Verdächtige IP‑Adresse bestätigt
- Potenzielles Risiko für unautorisierten Zugriff
 
## 🛡️ Maßnahmen & Empfehlungen
- Sperrung der betroffenen Benutzerkonten  
- Blockierung der IP-Adresse  
- Anpassung der Login-Richtlinien
- Überprüfung weiterer Systeme auf ähnliche Aktivitäten

## 🧪 Web Traffic Analysis – Burp Suite

![Burp Suite HTTP History](burpsuite-http-history.png)

**Summary**
- HTTP‑Requests über Burp Suite Proxy erfasst
- Analyse von Request/Response‑Verhalten
- Verständnis für Web‑Traffic‑Inspektion demonstriert

**Tools**
- Burp Suite
- Kali Linux
- VirtualBox


## 📚 Learnings
- Vertiefte praktische Erfahrung in SOC‑Triage  
- Stärkung der Fähigkeiten in Log‑ und Netzwerkverkehrsanalyse
- Verständnis für die Kombination von SIEM‑, EDR‑ und Netzwerkdaten

## ⚠️ Hinweis
Alle Tests wurden ausschließlich in einer isolierten Laborumgebung durchgeführt.
