# 🚀 **Projektstart: EcoMarket - Nachhaltige Produktplattform**  

## 🎯 **Lernziel für den Projektstart**  

**🌍 Am Ende dieser Einheit kannst du:**  
✅ **Frontend-Grundlagen meistern:**  
   - 🏗️ Responsive Layout mit HTML5/CSS3 erstellen  
   - 🎨 Modernes UI-Design mit CSS Grid/Flexbox  
   - 📱 Mobile-First Ansatz umsetzen  

✅ **Interaktive Elemente entwickeln:**  
   - 🛒 Produktfilter mit JavaScript implementieren  
   - ⭐ Bewertungssystem programmieren  
   - 🗺️ Integrierte Nachhaltigkeits-Karte einbinden  

✅ **Backend-Anbindung verstehen:**  
   - 📡 API-Aufrufe mit Fetch/Async-Await  
   - 🛢️ Mock-Datenbank mit JSON erstellen  
   - 🔄 Daten zwischen Frontend/Backend austauschen  

**✨ Warum lohnt sich das?**  
🔧 **Praktische Skills:**  
   - 🌐 Fullstack-Webentwicklung lernen  
   - 💻 Moderne JavaScript-Kenntnisse aufbauen  
   - 🛠️ Portfolio-Projekt mit realem Nutzen  

🌱 **Nachhaltiger Impact:**  
   - ♻️ Bewusstsein für ökologische Produkte schaffen  
   - 🌳 CO₂-Fußabdruck durch lokale Angebote reduzieren  
   - 💚 Gemeinschaft nachhaltiger Händler unterstützen  

**💪 Motivations-Boost:**  
"Jede Code-Zeile für diese Plattform hilft direkt unserer Umwelt –  
was für ein kraftvolles Projekt für deine Karriere! 🌍✨"  

**📌 Checkliste für Erfolg:**  
🔹 [ ] Responsive Grundstruktur erstellt  
🔹 [ ] Mind. 3 Filterfunktionen implementiert  
🔹 [ ] Produktdatenbank angelegt  
🔹 [ ] Projekt auf GitHub veröffentlicht  

**🚨 Denk dran:**  
"Perfektion kommt durch Iteration –  
starte mit einem MVP und erweitere schrittweise! 🛠️"  

**🎁 Bonus:**  
Für jede abgeschlossene Aufgabe: 🌱 Pflanze einen digitalen Baum (z.B. bei Ecosia)!  

---

# 📂 **Portfolioaufgabe: Nachhaltige Plattform entwickeln**  

## 🎯 **Deine Mission**  
Erstelle eine **interaktive Webplattform**, die nachhaltige Produkte und lokale Anbieter sichtbar macht!  

---

## 🌟 **Aufgabenübersicht**  
### 🔹 **Grundaufgabe (Pflicht)**  
1. **🖥️ Frontend-Entwicklung**  
   - Erstelle responsive Seite mit:  
     - Produktübersicht  
     - Filterfunktionen (Kategorie, Entfernung, Öko-Score)  
     - Detailansicht  

2. **📡 Datenmanagement**  
   - Baue JSON-Datenbank mit 20+ Produkten  
   - Implementiere Suchfunktion  
   - Lade externe Nachhaltigkeitsdaten per API  

3. **🌐 Deployment**  
   - Veröffentliche auf GitHub Pages/Vercel  
   - Dokumentiere den Tech-Stack  

### 🔹 **Bonusaufgaben (optional)**  
- 🔥 **User Accounts:** Registrierung/Login  
- 💚 **CO₂-Rechner:** Fußabdruck pro Produkt  
- 🗺️ **Geomapping:** Lokale Händler anzeigen  

---

## 🛠 **Technischer Input**  
### 📜 **Cheatsheet: Wichtige Code-Snippets**  
```javascript
// Produktfilter
function filterProducts() {
  return products.filter(p => 
    p.category === selectedCategory &&
    p.ecoScore >= minScore
  );
}

// API-Anfrage
async function fetchEcoData() {
  const response = await fetch('api/eco-scores');
  return response.json();
}
```

### 📚 **Ressourcen**  
- [MDN Web Docs](https://developer.mozilla.org/)  
- [CSS-Tricks Guide](https://css-tricks.com/)  
- [Sustainable Web Design](https://sustainablewebdesign.org/)  

---

## 💡 **Tipps & Tricks**  
### ✅ **Für Einsteiger:**  
- Nutze [Bootstrap](https://getbootstrap.com/) für schnelles Styling  
- Starte mit statischen Daten vor API-Integration  
- Teste auf [MobileMoxie](https://www.mobilemoxie.com/)  

### 🏆 **Für Fortgeschrittene:**  
- Implementiere [Lazy Loading](https://web.dev/lazy-loading/)  
- Nutze [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) für Offline-Funktionalität  
- Optimiere für [Green Webhosting](https://www.thegreenwebfoundation.org/)  

---

## 🔖 **Badge-Anforderungen**  
### 🏅 **Mindestanforderungen:**  
- [ ] Funktionierende Filterfunktionen  
- [ ] Responsive Design  
- [ ] Dokumentiertes GitHub-Repo  

### ⭐ **Bonus-Punkte:**  
- [ ] API-Integration  
- [ ] Progressive Web App Features  
- [ ] Accessibility optimiert  

---

## 📌 **So gehst du vor**  
1. **📐 Plane dein Layout** (Figma/Sketch)  
2. **🛠 Baue Komponenten** (Header, Karten, Filter)  
3. **📡 Verbinde Daten** (JSON → API)  
4. **🚀 Veröffentliche & feiere!**  

**🚀 Du schaffst das!**  
*"Diese Plattform könnte der Startpunkt für viele nachhaltige Kaufentscheidungen sein!"*  

> **🔗 Nächste Schritte:**  
> ▶️ Woche 1: Frontend-Grundgerüst  
> ▶️ Woche 2: Filter & Interaktion  
> ▶️ Woche 3: Datenintegration  
