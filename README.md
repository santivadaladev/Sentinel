# 🛡️ OS_Sentinel: Open-Source Civic Intelligence & Territorial Awareness

OS_Sentinel è un progetto open-source, no-profit e guidato dalla community, nato per raccogliere, strutturare e storicizzare in modo totalmente anonimo le criticità informatiche (incidenti ICT) e territoriali (sicurezza urbana) della città di **Campobasso** e della regione Molise.

Il progetto si basa sulla filosofia della **Threat Intelligence Civica**: trasformare eventi di cronaca, report istituzionali e dati pubblici in un dataset aperto, normalizzato e riutilizzabile da giornalisti, università e cittadini per migliorare la consapevolezza del territorio.

---

## 🛑 Pilastri Fondamentali & Privacy (GDPR)

Per evitare che il progetto si trasformi in "schedatura", OS_Sentinel applica rigidamente questi vincoli di design:
1. **Zero Dati Personali (No PII):** Non viene memorizzato alcun dato relativo a persone fisiche (nomi, targhe, volti, indirizzi privati o civici).
2. **Clessidra Temporale:** Gli eventi non registrano mai l'orario esatto, ma vengono aggregati su base mensile (es. *Dicembre 2023*) per impedire la re-identificazione.
3. **Geolocalizzazione Approssimativa:** La precisione si ferma al livello di Comune e Quartiere/Zona. Niente coordinate GPS esatte.

---

## 📂 Struttura Attuale del Progetto

```text
os_sentinel/
├── README.md                  # Questo file (Presentazione e Note Tecniche)
├── CONTRIBUTING.md            # Guida per i collaboratori
├── LICENSE                    # Licenza MIT (Codice libero e protetto)
└── os_sentinel_db_molise.xlsx # Il Database Master ufficiale (Fogli Excel strutturati)
