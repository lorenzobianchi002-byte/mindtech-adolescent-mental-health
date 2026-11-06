# Mindtech: Adolescent Mental Health & Social Media Analysis

Analisi dati esplorativa (EDA) focalizzata sulla correlazione tra l'utilizzo dei social media, la qualità del sonno e i livelli di stress/ansia in un campione di 1200 adolescenti[cite: 1].

## 📋 Panoramica del Progetto
Questo repository fa parte del progetto di analisi dati incentrato sul benessere digitale e psicologico degli adolescenti. L'obiettivo è analizzare abitudini digitali, ore di sonno e metriche di stress per identificare pattern di rischio e fornire insight basati sui dati[cite: 1].

## 📊 Struttura del Dataset
Il dataset analizzato è composto da **1200 soggetti (righe)** e **13 variabili (colonne)**[cite: 1], tra cui:
- **Dati demografici**: Età (`age`), Genere (`gender`)[cite: 1].
- **Abitudini digitali**: Ore giornaliere sui social (`daily_social_media_hours`), Piattaforme utilizzate (`platform_usage`), Tempo di schermo prima di dormire (`screen_time_before_sleep`)[cite: 1].
- **Salute e benessere**: Ore di sonno (`sleep_hours`), Livello di stress (`stress_level`), Livello di ansia (`anxiety_level`), Indice di dipendenza (`addiction_level`), Indicatore di depressione (`depression_label`)[cite: 1].

## 🔍 Risultati Chiave e Metriche
- **Integrità dei dati**: Audit completato con successo. Il dataset risulta perfettamente pulito, senza valori nulli (`Null: 0`) o record duplicati (`0`)[cite: 1].
- **Fascia a rischio**: L'incrocio tra ore di sonno insufficienti ($\le$ 5h) e livelli di stress elevati ($\ge$ 7) evidenzia un gruppo vulnerabile significativo, con una percentuale di indicatori di depressione pari al **22.0%**[cite: 1].
- **Piattaforme**: L'utilizzo si distribuisce in modo equilibrato tra Instagram, TikTok e l'uso combinato di entrambe le piattaforme[cite: 1].

## 🛠️ Strumenti e Tecnologie
- **Linguaggio**: Python (Jupyter Notebook)[cite: 1]
- **Librerie principali**: Pandas, NumPy[cite: 1]
- **Controllo versione**: Git / GitHub[cite: 1]

## 🚀 Come consultare il progetto
Puoi esplorare l'intero codice e l'esecuzione dettagliata delle analisi aprendo il file principale nel percorso:
`notebooks/mindtech_analysis.ipynb`[cite: 1]
