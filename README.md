# Schritt 1-3 wie oben, dann:

# README.md erstellen
cat > README.md << 'EOF'
# DesertGreener: Europa geht das Wasser aus

🌊 **Vollständige Präsentation: 100 Folien**
- 🌐 **Weltwassertag Initiative 2026:** www.weltwassertag.at
- 📊 624 globale Dürre-Cluster analysiert
- 💰 Big 4-Bewertungsmethodik (DCF, Multiples, Comparables)
- 🪙 DGRX Token-Ökonomie-Visualisierung (400M EUR, 0,10 EUR)

## 📥 Präsentation ansehen

[HTML-Datei herunterladen](./index.html) und im Browser öffnen

## Highlights
- 🌍 8 Regionen weltweit analysiert
- 💧 ~9,3 km³ Wasserpotenzial (Ambition-Szenario)
- 👥 17,3 Mio. Menschen versorgbar
- 💼 290.000 Arbeitsplätze
- 📈 Wissenschaftlich fundiert (Waldstein, Köppen-Geiger)

## Kontakt
**Weltwassertag Initiative 2026**  
www.weltwassertag.at
EOF

# README commiten
git add README.md
git commit -m "Add README with presentation overview"
git push origin main
