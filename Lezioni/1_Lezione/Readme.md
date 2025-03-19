[Vai al file principale](../../Readme.md)

# Lezione 1 19 Marzo 2025

## Git: Vantaggi e Svantaggi

Git aiuta a mantenere la storia del tuo progetto nella tua repository.  
Tiene traccia delle modifiche e permette di tornare indietro in caso di errori.

### ✅ Vantaggi di Git

- ✅ **Controllo della versione**: consente di salvare ogni modifica e ripristinare versioni precedenti.
- ✅ **Branching e merging**: permette di lavorare su più funzionalità contemporaneamente senza interferire con il codice principale.
- ✅ **Collaborazione**: facilita il lavoro di squadra con strumenti come GitHub, GitLab e Bitbucket.
- ✅ **Velocità**: è progettato per essere rapido ed efficiente.
- ✅ **Sistema distribuito**: ogni sviluppatore ha una copia completa della repository, riducendo il rischio di perdita dei dati.
- ✅ **Tracking delle modifiche**: mostra chi ha cambiato cosa e quando.
- ✅ **Compatibilità**: funziona su diverse piattaforme e con diversi strumenti di sviluppo.
- ✅ **Controllo integrità codice**: tiene conto ai dati da mettere e modifici la storia. -> anche se elimini i dati 
- ✅ **Gestione dei conflitti**: consente di risolvere conflitti durante il merging.
- ✅ **Controllo versioni**: consente di mantenere un controllo completo delle versioni del codice.

### ❌ Svantaggi di Git

- ❌ **Curva di apprendimento ripida**: i nuovi utenti potrebbero trovare difficile imparare Git, specialmente con comandi complessi.
- ❌ **Gestione dei merge complessa**: in progetti molto grandi, il merging può diventare complicato e richiedere tempo.
- ❌ **Necessità di linea di comando**: anche se esistono interfacce grafiche, molte operazioni avanzate richiedono l'uso della CLI.
- ❌ **Spazio su disco**: a causa della sua natura distribuita, le repository possono diventare molto grandi con il tempo.
- ❌ **Mancanza di un'interfaccia centralizzata**: a differenza di altri sistemi come SVN, non esiste un'unica repository centrale ufficiale.

Git è uno strumento potente, ma richiede una buona comprensione per essere usato al meglio.

### **Vantaggi di Git: Sviluppo Distribuito e Sviluppo Non Lineare**  

Uno dei principali vantaggi di Git è il **sistema distribuito**, che permette di lavorare in modo **non lineare**. Vediamo nel dettaglio questi due concetti.  

---

## **📌 Cos'è lo Sviluppo Distribuito?**  

Lo sviluppo distribuito significa che ogni sviluppatore ha una copia completa della repository, compresa l'intera cronologia delle modifiche.  

### 🔹 **Caratteristiche dello Sviluppo Distribuito in Git:**  
- **Ogni sviluppatore ha una copia locale della repository**, con tutta la sua cronologia.  
- **Non dipende da un server centrale**: è possibile lavorare offline e sincronizzarsi in seguito.  
- **Maggiore sicurezza**: se il server remoto si rompe, ogni copia locale può essere usata per ripristinare i dati.  
- **Migliore collaborazione**: gli sviluppatori possono lavorare indipendentemente e unire il loro lavoro quando necessario.  

💡 *Esempio:*  
Se lavori con SVN (un sistema centralizzato), ogni modifica deve essere salvata direttamente sul server. Con Git, invece, puoi lavorare localmente e inviare le modifiche solo quando sei pronto.  

---

## **📌 Cos'è lo Sviluppo Non Lineare?**  

Lo sviluppo non lineare in Git significa che gli sviluppatori possono lavorare su più funzionalità contemporaneamente utilizzando i **branch (rami)**.  

### 🔹 **Caratteristiche dello Sviluppo Non Lineare in Git:**  
- **Uso dei branch**: puoi creare un ramo per ogni nuova funzionalità senza interferire con il codice principale.  
- **Lavoro parallelo**: più sviluppatori possono lavorare su diverse funzionalità senza sovrascrivere il lavoro degli altri.  
- **Storico pulito**: grazie a commit separati per ogni ramo, la cronologia rimane chiara e organizzata.  
- **Facile gestione delle versioni**: puoi unire (merge) o eliminare un ramo quando una funzionalità è completa.  

💡 *Esempio:*  
- Il ramo `main` contiene il codice stabile.  
- Crei un nuovo ramo `feature-login` per lavorare su una nuova funzione di login.  
- Dopo aver terminato, fai il merge di `feature-login` con `main`, senza intaccare il codice durante lo sviluppo.  

---

## **🔄 Differenza tra Sviluppo Lineare e Non Lineare**  

| Tipo di sviluppo | Descrizione | Esempio |
|------------------|-------------|---------|
| **Sviluppo Lineare** | Tutti lavorano su un'unica sequenza di commit senza branch separati. | SVN e sistemi centralizzati. |
| **Sviluppo Non Lineare** | Gli sviluppatori creano e uniscono rami in modo indipendente. | Git e altri VCS distribuiti. |

---

## **🎯 Perché Git è Potente?**  

✅ Lo **sviluppo distribuito** riduce il rischio di perdita di dati e permette di lavorare offline.  
✅ Lo **sviluppo non lineare** semplifica la gestione delle funzionalità e del codice.  
✅ Il sistema di **branching** consente un'organizzazione più efficiente del lavoro.  

Se hai bisogno di più dettagli, fammelo sapere! 🚀😊