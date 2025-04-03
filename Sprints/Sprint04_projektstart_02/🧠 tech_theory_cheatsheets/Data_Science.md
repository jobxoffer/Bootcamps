# 🚀 **Projektstart: KI-gestütztes Finanzanalyse-Tool**  

## 🎯 **Lernziel für den Projektstart**  

**💰 Am Ende dieser Einheit kannst du:**  
✅ **Daten-Meister:in werden:**  
   - 💳 Banktransaktions-CSVs mit Pandas einlesen  
   - 🧹 Finanzdaten säubern (Duplikate entfernen, Kategorien zuordnen)  
   - 🔢 Monatliche Ausgaben summieren und analysieren  

✅ **KI-Entdecker:in:**  
   - 🤖 Ein einfaches ML-Modell für Ausgabenkategorien trainieren  
   - 📊 Modellgenauigkeit mit einer Confusion Matrix bewerten  
   - 🔄 Daten-Pipeline für regelmäßige Updates erstellen  

✅ **Dashboard-Expert:in:**  
   - 📱 Ein persönliches Finance-Dashboard mit Streamlit bauen  
   - 🎮 Interaktive Filter für Zeiträume und Kategorien hinzufügen  
   - 📤 PDF-Reports mit monatlichen Ausgabentrends generieren  

**✨ Warum lohnt sich das?**  
🔧 **Praktische Skills:**  
   - 🐍 Python-Kenntnisse vertiefen  
   - 🤖 Erste Machine-Learning-Erfahrungen sammeln  
   - 🛠️ Portfolio-Projekt mit Alltagsbezug  

💼 **Karriere-Impact:**  
   - 📈 Finanztech-Kompetenzen aufbauen  
   - 🏦 Relevante Skills für Banken/Fintechs entwickeln  
   - 💰 Praktisches Tool für die eigene Finanzplanung  

**💪 Motivations-Boost:**  
"Finanzdaten sind das Gold der Moderne –  
mit diesem Projekt baust du dir deinen eigenen Datenschatz! 💎"  

**📌 Checkliste für Erfolg:**  
🔹 [ ] Transaktionsdaten eingelesen  
🔹 [ ] Mindestens 3 Ausgabenkategorien automatisch klassifiziert  
🔹 [ ] Dashboard mit monatlicher Übersicht erstellt  
🔹 [ ] Projekt auf GitHub veröffentlicht  

**🚨 Denk dran:**  
"Beim ersten ML-Modell muss nicht alles perfekt sein –  
Hauptsache, es lernt und du mit ihm! 🧠"  

**🎁 Bonus:**  
Für jede erreichte Accuracy-Stufe: 🍕 Belohnung gönnen!  
(70% = Kaffee, 80% = Pizza, 90% = Feierabendbier!)  

---

# 📂 **Portfolioaufgabe: Finanzanalyse-Tool erstellen**  

## 🎯 **Deine Mission**  
Entwickle ein **KI-gestütztes Tool**, das persönliche Ausgaben automatisch kategorisiert und visualisiert!  

---

## 🌟 **Aufgabenübersicht**  
### 🔹 **Grundaufgabe (Pflicht)**  
1. **📊 Datenanalyse mit Python**  
   - Importiere Bankdaten (CSV oder Mock-Daten)  
   - Bereinige die Daten (fehlende Werte, Währungsumrechnung)  
   - Erstelle erste Visualisierungen (Ausgaben nach Kategorie/Monat)  

2. **🤖 KI-Modell entwickeln**  
   - Trainiere einen Kategorien-Klassifikator (z.B. Random Forest)  
   - Erreiche mindestens 70% Accuracy  
   - Speichere das trainierte Modell als .pkl-Datei  

3. **📱 Dashboard bauen**  
   - Erstelle ein Streamlit-Dashboard mit:  
     - Monatlicher Ausgabenübersicht  
     - Kategorie-Filter  
     - Modell-Performance-Anzeige  

### 🔹 **Bonusaufgaben (optional)**  
- 🔥 **Automatisierte Reports:** Generiere wöchentliche PDF-Zusammenfassungen  
- 💬 **NLP-Verbesserung:** Nutze Wortembedding für bessere Klassifikation  
- ☁️ **Deployment:** Veröffentliche dein Tool auf Streamlit Cloud  

---

## 🛠 **Technischer Input**  
### 📜 **Cheatsheet: Wichtigste Code-Snippets**  
```python
# Daten vorbereiten
import pandas as pd
df = pd.read_csv("transactions.csv")
df['Datum'] = pd.to_datetime(df['Datum'])

# Einfaches ML-Modell
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier()
model.fit(X_train, y_train)  # X = Textbeschreibungen, y = Kategorien

# Streamlit Dashboard
import streamlit as st
st.title("Mein Finanzdashboard")
st.bar_chart(df.groupby('Kategorie')['Betrag'].sum())
```

### 📚 **Ressourcen**  
- [Pandas Finanz-Tutorial](https://towardsdatascience.com/personal-finance-analysis-with-pandas-8c34cf087af1)  
- [Scikit-learn Dokumentation](https://scikit-learn.org/stable/)  
- [Streamlit Dokumentation](https://docs.streamlit.io/)  

---

## 💡 **Tipps & Tricks**  
### ✅ **Für Einsteiger:**  
- Starte mit **manuell kategorisierten Testdaten** (100-200 Transaktionen)  
- Nutze **vorgefertigte Kategorien** (Lebensmittel, Transport, Freizeit etc.)  

### 🏆 **Für Fortgeschrittene:**  
- Implementiere **Transfer Learning** mit FinBERT für bessere Textanalyse  
- Baue eine **Budget-Prognose** für kommende Monate  

---

## 🔖 **Badge-Anforderungen**  
### 🏅 **Mindestanforderungen:**  
- [ ] Funktionierendes Klassifikationsmodell (>70% Accuracy)  
- [ ] Streamlit-Dashboard mit Grundfunktionen  
- [ ] Dokumentiertes GitHub-Repository  

### ⭐ **Bonus-Punkte:**  
- [ ] Automatisierter Report-Export  
- [ ] NLP-Verbesserungen  
- [ ] Live-Deployment  

---

## 📌 **So gehst du vor**  
1. **📖 Daten beschaffen** (Eigene Exporte oder Mock-Daten)  
2. **🛠 Schrittweise entwickeln** (Daten → ML → Dashboard)  
3. **📝 Jeden Fortschritt dokumentieren**  
4. **🙋 Bei Problemen fragen** (Community nutzen!)  

**🚀 Du schaffst das!**  
*"Dieses Projekt verbindet Data Science mit praktischem Nutzen –  
perfekt für dein Portfolio und deine Finanzen! 💸"*  

> **🔗 Nächste Schritte:**  
> ▶️ Woche 1: Datenexploration  
> ▶️ Woche 2: Modellentwicklung  
> ▶️ Woche 3: Dashboard-Bau