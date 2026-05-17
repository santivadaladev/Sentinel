<p align="center">
  <img src="sentinellogo.png" alt="Sentinel Logo" width="280"/>
</p>

# 🛡️ OS_Sentinel: Open-Source Civic Intelligence & Territorial Awareness

OS_Sentinel è un progetto open-source, no-profit e guidato dalla community, nato per raccogliere, strutturare e storicizzare in modo totalmente anonimo le criticità informatiche (incidenti ICT) e territoriali (sicurezza urbana) della città di **Campobasso** e della regione Molise.

Il progetto si basa sulla filosofia della **Threat Intelligence Civica**: trasformare eventi di cronaca, report istituzionali e dati pubblici in un dataset aperto, normalizzato e riutilizzabile da giornalisti, università e cittadini per migliorare la consapevolezza del territorio.

---

## 🌐 Link Rapidi del Nodo Operativo

| Risorsa | Descrizione | Stato Server |
| :--- | :--- | :--- |
| 🗺️ [**Mappa Interattiva (Radar)**](https://teknoirdev.github.io/Sentinel/) | Visualizzazione geo-spaziale in tempo reale degli incidenti | **🟢 ONLINE** |
| 📊 [**Database Master (Excel)**](os_sentinel_db_molise.xlsx) | Archivio strutturato, normalizzato e storicizzato dei dati | **📦 PRONTO AL DOWNLOAD** |

---

## 🛑 Pilastri Fondamentali & Privacy (GDPR)

Per evitare che il progetto si trasformi in "schedatura" o sorveglianza di massa, OS_Sentinel applica rigidamente questi tre vincoli di progettazione fin dalla sua architettura di base:

1. **Zero Dati Personali (No PII):** Non viene memorizzato alcun dato relativo a persone fisiche (nomi, targhe, volti, indirizzi privati o specifici numeri civici).
2. **Clessidra Temporale:** Gli eventi non registrano mai l'orario esatto in cui sono avvenuti. I dati vengono aggregati su base puramente mensile (es. *Dicembre 2023*) per impedire correlazioni e re-identificazione.
3. **Geolocalizzazione Approssimativa:** La precisione cartografica varia in base alla categoria. Per la *Sicurezza Urbana* si ferma rigorosamente al livello di Comune e Macro-Quartiere/Zona (es. *Quartiere Vazzieri*), senza mai esporre coordinate GPS puntuali di abitazioni private.

---

## 📂 Struttura del Progetto

```text
Sentinel/
├── .github/                  # Configurazione dei server e automazioni GitHub Pages
├── sentinellogo.png          # Logo ufficiale del progetto (Cyber-Octopus)
├── README.md                 # Questo file (Presentazione, Note Tecniche e Indice)
├── index.html                # Interfaccia web e codice sorgente della mappa interattiva (Leaflet)
├── contributing.md           # Linee guida e policy per l'inserimento dei dati dei collaboratori
├── LICENSE                   # Licenza MIT (Codice totalmente libero e protetto)
└── os_sentinel_db_molise.xlsx # Il Database Master ufficiale (Fogli Excel strutturati)
