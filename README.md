<<<<<<< HEAD
# Mindtech: Adolescent Mental Health & Social Media Analysis

Repository ufficiale del progetto di analisi dati focalizzato sul benessere digitale e psicologico degli adolescenti.



> **Case Study: Social Media Impact on Adolescent Mental Health**
>
> Questo studio analizza la correlazione tra le abitudini digitali e il benessere psicofisico degli adolescenti, focalizzandosi in particolare sull'impatto dell'iperconnessione serale e della privazione di sonno. Attraverso un'analisi quantitativa condotta su un campione di 1.200 soggetti, l'indagine identifica i fattori di rischio comportamentali legati all'utilizzo prolungato dei social media e del tempo di schermo prima del riposo notturno. L'obiettivo della ricerca è fornire evidenze strutturate a supporto di strategie di prevenzione digitale e di interventi mirati nel settore della salute e della tecnologia educativa.



### Approfondisci il Progetto
Per consultare il report completo, l'indice dettagliato, le tabelle delle metriche e l'analisi statistica approfondita, puoi accedere al documento ufficiale:

 [**Leggi il Case Study Completo (Google Docs)**](https://docs.google.com/document/d/1p99Gd8slAdC9DzvfW3gVMDjSFGi7zm21WkjHk_WND_s/edit?usp=sharing)



###  Tecnologie e Strumenti
* **Linguaggio**: Python (Jupyter Notebook)
* **Librerie**: Pandas, NumPy
* **Controllo versione**: Git & GitHub

- **Presentazione del Progetto**: Puoi visionare la [Presentazione esecutiva ultimata su Google Slides](https://docs.google.com/presentation/d/1nWJZMVd5Hhq6XvWWg_HEFtMyDAfIlv-VLBgLRzEpu5A/edit?usp=sharing).
=======




Case Study
Social Media Impact on Adolescent Mental Health

Questo studio analizza la correlazione tra le abitudini digitali e il benessere psicofisico degli adolescenti, focalizzandosi in particolare sull'impatto dell'iperconnessione serale e della privazione di sonno. Attraverso un'analisi quantitativa condotta su un campione di 1.200 soggetti, l'indagine identifica i fattori di rischio comportamentali legati all'utilizzo prolungato dei social media e del tempo di schermo prima del riposo notturno. L'obiettivo della ricerca è fornire evidenze strutturate a supporto di strategie di prevenzione digitale e di interventi mirati nel settore della salute e della tecnologia educativa.















INDICE 
1. Introduzione e obiettivi di Ricerca 
1.1  Scenario e definizione degli stakeholder 
1.2 Richieste e obiettivo strategico dell’indagine 
2. Raccolta, integrazione e preparazione dei dati 
2.1  Identificazione, sourcing e valutazione preliminare del dataset con ROCCC
2.2 Architettura del dataset: struttura e metriche 
2.3 Ordinamento e filtraggio dei dati 
3.  Analisi esplorativa 
3.1  Aggregazione dei dati per piattaforma social e risultati  
3.2 Organizzazione, Formattazione e Feature Engineering dei dati
3.3 Analisi Statistica e Matrice di Correlazione
4. Implicazioni Strategiche e Raccomandazioni 
4.1 Sintesi degli insight per gli stakeholder e le istituzioni educative
4.2 Linee guida pratiche e interventi mirati per un consumo digitale consapevole
5. Conclusioni e Sviluppi Futuri





Introduzione e Obiettivi di Ricerca 

Il presente studio si inserisce all'interno delle attività del MindTech Research Lab, un istituto focalizzato sull'analisi dell'impatto delle tecnologie digitali e dei social media sul benessere psicofisico in età evolutiva.
Contesto
Negli ultimi anni, la diffusione pervasiva degli smartphone tra i 13 e i 19 anni ha trasformato radicalmente le abitudini comunicative e sociali dei giovani. Se da un lato la tecnologia offre nuove opportunità, dall'altro la progettazione stessa delle piattaforme pensata per massimizzare l'attenzione e il coinvolgimento si scontra quotidianamente con i ritmi biologici fondamentali dei ragazzi, incidendo in modo critico sulla qualità del riposo notturno e sui livelli di stress percepito.
STAKEHOLDER 
Clayton Kars, Direttore Esecutivo (dirigenza)
Marco Valli: Head of Research & Strategy di MindTech Research Lab (manager)

Richiesta
Guidare un progetto di ricerca e analisi dati per mappare l'evoluzione delle abitudini digitali degli adolescenti (fascia d'età 13-19 anni). L'obiettivo finale è identificare le correlazioni critiche tra il tempo trascorso sui dispositivi, l'uso intensivo dei social media, le ore di sonno e i livelli di stress percepito, così da tradurre questi dati in un piano d'azione strategico: una guida pratica e linee guida basate sui dati destinate a scuole, famiglie e psicologi per favorire un controllo più consapevole della tecnologia.

L'obiettivo strategico dell'indagine
Di fronte alla difficoltà di genitori e istituzioni educative nel tracciare confini sani, il progetto nasce con una missione precisa: superare le impressioni generali e mappare con rigore scientifico le abitudini reali di un campione di 1.200 adolescenti. L'intento non è un mero esercizio statistico, ma la traduzione dei dati in evidenze concrete, utili a sviluppare linee guida pratiche e interventi mirati per scuole, famiglie e professionisti del settore.

Raccolta, Integrazione e Preparazione dei Dati 

Identificazione, sourcing e valutazione del dataset
La fase iniziale del percorso ha richiesto l'acquisizione del dataset di riferimento attraverso piattaforme open-source certificate, garantendo la tracciabilità e l'integrità originaria dei dati. Il file è stato sottoposto a un'ispezione preliminare nell'ambiente di sviluppo per verificare l'assenza di anomalie strutturali, la coerenza dei formati relativi al campione di 1.200 adolescenti.
Prima di iniziare l'analisi vera e propria, ho verificato la qualità e la struttura dei dati del file Teen_Mental_Health_Dataset.csv.
I controlli effettuati hanno dato esito totalmente positivo:
Dimensione del campione: Il dataset contiene 1.200 adolescenti (con un'età compresa tra i 13 e i 19 anni) e 13 variabili di riferimento.
Integrità dei dati: Non ho riscontrato valori mancanti (0 valori nulli) né record duplicati (0 duplicati). Questo significa che il dataset è pulito e pronto all'uso senza bisogno di interventi di correzione.
Sintesi dei dati principali (Medie del campione):
Dati Demografici e Tecnologici
age: Età del soggetto (compresa tra i 13 e i 19 anni).
gender: Genere di appartenenza.
daily_social_media_hours: Ore medie giornaliere trascorse sui social media.
platform_usage: Piattaforma social principale utilizzata.
Stile di Vita e Benessere Fisico
sleep_hours: Ore medie di sonno notturno.
screen_time_before_sleep: Tempo trascorso davanti allo schermo prima di dormire.
academic_performance: Valutazione del rendimento scolastico.
physical_activity: Livello di attività fisica svolta.
social_interaction_level: Frequenza delle interazioni sociali nel mondo reale.
Indicatori Psicologici e Comportamentali
stress_level: Livello di stress percepito (scala da 1 a 10).
anxiety_level: Intensità dei sintomi ansiosi (scala da 1 a 10).
addiction_level: Grado di dipendenza digitale stimato (scala da 1 a 10).
depression_label: Indicatore binario (0 o 1) per la presenza di segnali clinici di depressione.
AFFIDABILITÀ E CREDIBILITÀ DEL DATASET 
R (Reliable): Elevata; ho verificato l'assenza totale di valori nulli e duplicati tramite script.
O (Original): Fonte strutturata e primaria, basata su metriche comportamentali e cliniche dirette.
C (Comprensive): Completa; copre tutte le variabili demografiche, tecnologiche e psicologiche necessarie.
C (Current): Aggiornata e coerente con i moderni scenari di utilizzo dei social tra gli adolescenti.
C (Cited): Tracciabile e riproducibile grazie al versionamento su GitHub all'interno della cartella di progetto









ORDINAMENTO FILTRAGGIO E PROCESSO  DEI DATI DEL DATASET 

Statistiche Descrittive del Campione
L'analisi delle metriche di tendenza centrale ha delineato il profilo generale dei 1,200 adolescenti esaminati:
Età media: 15.93 anni (std=2.02, range 13-19).
Utilizzo dei social media: Una media di 4.54 ore giornaliere (std=2.03), con picchi massimi registrati fino a 8.0 ore.
Riposo e Benessere: Una media di 6.45 ore di sonno per notte e un livello medio di stress percepito pari a 5.45/10.
Segmentazione e Filtraggio Avanzato
Attraverso operazioni di filtraggio condizionale, ho focalizzato l'attenzione sui soggetti esposti a condizioni di forte vulnerabilità psicofisica:
Isolamento della coorte critica: Incrociando i dati di chi sperimenta un sonno insufficiente (5 ore per notte) unitamente a livelli elevati di stress (7/10), ho identificato 100 adolescenti (pari all'8.3% del campione totale).
Correlazione con indicatori clinici: All'interno di questo gruppo ristretto a rischio, la percentuale di soggetti che presenta indicatori positivi di depressione (depression_label == 1) sale drasticamente al 22.0%, evidenziando una correlazione critica tra privazione del riposo, sovraccarico di stress e benessere mentale.

Verifica dei valori nulli e dei duplicati 
Completezza: Il dataset è composto da 1.200 record e 13 variabili, senza la presenza di alcun valore nullo.
Assenza di Duplicati: L'ispezione dei record non ha evidenziato righe duplicate, garantendo l'unicità di ciascuna unità di osservazione.

Validazione dei Range e delle Scale di Misura
Ho verificato la coerenza dei valori minimi e massimi per tutte le variabili numeriche, riscontrando la perfetta aderenza ai domini teorici attesi:
Variabili Anagrafiche e Temporali: L'età dei soggetti (age) è compresa esattamente nel range adolescenziale tra 13 e 19 anni (media=15.93).
Metriche Comportamentali: Il tempo medio giornaliero dedicato ai social media (daily_social_media_hours) oscilla tra un minimo di 1.0 e un massimo di 8.0 ore (media=4.54). Le ore di sonno (sleep_hours) variano da 4.0 a 9.0 ore.
Scale Psicologiche (1-10): I punteggi relativi a livello di stress (stress_level), ansia (anxiety_level) e dipendenza digitale (addiction_level) rispettano rigorosamente il range stabilito da 1 a 10, così come l'etichetta binaria di depressione (depression_label, compresa tra 0 e 1).

Controllo delle Variabili Categoriche con eventuali bias 
L'ispezione delle variabili qualitative ha confermato l'assenza di errori di sintassi, refusi o categorie non codificate:
Genere: Suddiviso in modo bilanciato tra male (615) e female (585) .
Piattaforme Utilizzate: Classificate in modo pulito tra Instagram, TikTok ed entrambi.
Livello di Interazione Sociale: Distribuito uniformemente tra medium , low e high.
Esito finale: Il dataset non ha richiesto interventi di correzione straordinaria o imputazione dei dati, risultando strutturalmente integro, privo di errori e pienamente affidabile.

Scelta degli strumenti 
Jupyter Lab su repository GitHub per garantire la totale tracciabilità e riproducibilità del codice.
Pandas Utilizzato come libreria principale per caricare, pulire, filtrare e strutturare i dati in formato tabulare.


Analisi esplorativa


Impatto per Piattaforma Social 

Piattaforma Social
Ore Medie sui Social
Ore Medie di Sonno
Livello di Stress (1-10)
Livello di Ansia (1-10)
Indice di Dipendenza (1-10)
Both (Entrambe)
4.52 h
6.46 h
5.55
5.49
5.50
Instagram
4.56 h
6.44 h
5.50
5.67
5.58
TikTok
4.53 h
6.45 h
5.29
5.75
5.62










Relazione con il Livello di Interazione Sociale

Livello di Interazione Sociale
Livello di Stress (1-10)
Livello di Ansia (1-10)
Performance Accademica
High (Alto)
5.51
5.70
2.98
Medium (Medio)
5.48
5.69
3.00
Low (Basso)
5.35
5.53
2.99


OSSERVAZIONE SUL IMPATTO PER PIATTAFORMA SOCIAL
Si osserva una lieve accentuazione dei punteggi medi di ansia e dipendenza nei soggetti che utilizzano TikTok o Instagram in modo mirato rispetto all'uso combinato.
OSSERVAZIONE SULLA RELAZIONE CON IL LIVELLO DI INTERAZIONE SOCIALE 
All'interno di questo campione, la quantità di interazione sociale offline non è il fattore che "salva" o "affossa" lo studente dal punto di vista dello stress scolastico o del rendimento. I ragazzi viaggiano sugli stessi livelli di ansia e profitto a prescindere da quanto siano socievoli nella vita reale




Organizzazione, Formattazione e Feature Engineering dei dati

Distribuzione delle Nuove Variabili di Analisi
Nuova Categoria / Indicatore
Criterio di Definizione
Numero di Soggetti 
Percentuale sul Totale
Sonno Adeguato
>5.0 ore di sonno notturno
936
78.0%
Sonno Insufficiente
5.0 ore di sonno notturno
264
22.0%
Rischio Normale (Stress/Ansia)
Punteggi <7 in stress o ansia
1,014
84.5%
Rischio Combinato (Stress & Ansia Elevati)
Punteggio 7 in entrambi i parametri
186
15.5%


OSSERVAZIONI SULLA DISTRIBUZIONE DELLE NUOVE VARIABILI 
Il 22% del campione sperimenta regolarmente un sonno insufficiente, rappresentando una fascia a forte rischio di correlazione con l'uso prolungato dei dispositivi digitali.
Il 15.5% degli adolescenti presenta una co-occorrenza critica di stress e ansia elevati, 




Analisi Statistica e Matrice di Correlazione

Variabili
Ore Social
Ore Sonno
Schermo pre-sonno
Livello Stress
Livello Ansia
Indice Dipendenza
Performance Accademica
Ore Social
1.00
-0.01
0.04
0.03
0.03
-0.02
0.01
Ore Sonno
-0.01
1.00
0.01
-0.01
-0.01
-0.05
0.02
Schermo pre-sonno
0.04
0.01
1.00
-0.01
-0.01
0.03
-0.03
Livello Stress
0.03
-0.01
-0.01
1.00
0.02
-0.00
-0.00
Livello Ansia
0.03
-0.01
-0.01
0.02
1.00
0.03
-0.06
Indice Dipendenza
-0.02
-0.05
0.03
-0.00
0.03
1.00
0.03
Performance Accademica
0.01
0.02
-0.03
-0.00
-0.06
0.03
1.00




Osservazioni 
I coefficienti prossimi allo zero indicano che all'interno del campione analizzato non emergono legami lineari diretti e marcati tra l'uso dei dispositivi digitali e l'insorgenza di stress o alterazioni del sonno presi singolarmente.
La performance accademica mostra un'indipendenza quasi totale rispetto alle abitudini digitali e ai carichi di ansia o stress censiti.






>>>>>>> 5c4e747 (Aggiornato README.md per la fase di Share)
