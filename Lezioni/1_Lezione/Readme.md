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

💡 _Esempio:_  
Se lavori con SVN (un sistema centralizzato), ogni modifica deve essere salvata direttamente sul server. Con Git, invece, puoi lavorare localmente e inviare le modifiche solo quando sei pronto.

---

## **📌 Cos'è lo Sviluppo Non Lineare?**

Lo sviluppo non lineare in Git significa che gli sviluppatori possono lavorare su più funzionalità contemporaneamente utilizzando i **branch (rami)**.

### 🔹 **Caratteristiche dello Sviluppo Non Lineare in Git:**

- **Uso dei branch**: puoi creare un ramo per ogni nuova funzionalità senza interferire con il codice principale.
- **Lavoro parallelo**: più sviluppatori possono lavorare su diverse funzionalità senza sovrascrivere il lavoro degli altri.
- **Storico pulito**: grazie a commit separati per ogni ramo, la cronologia rimane chiara e organizzata.
- **Facile gestione delle versioni**: puoi unire (merge) o eliminare un ramo quando una funzionalità è completa.

💡 _Esempio:_

- Il ramo `main` contiene il codice stabile.
- Crei un nuovo ramo `feature-login` per lavorare su una nuova funzione di login.
- Dopo aver terminato, fai il merge di `feature-login` con `main`, senza intaccare il codice durante lo sviluppo.

---

## **🔄 Differenza tra Sviluppo Lineare e Non Lineare**

| Tipo di sviluppo         | Descrizione                                                          | Esempio                      |
| ------------------------ | -------------------------------------------------------------------- | ---------------------------- |
| **Sviluppo Lineare**     | Tutti lavorano su un'unica sequenza di commit senza branch separati. | SVN e sistemi centralizzati. |
| **Sviluppo Non Lineare** | Gli sviluppatori creano e uniscono rami in modo indipendente.        | Git e altri VCS distribuiti. |

---

## **🎯 Perché Git è Potente?**

✅ Lo **sviluppo distribuito** riduce il rischio di perdita di dati e permette di lavorare offline.  
✅ Lo **sviluppo non lineare** semplifica la gestione delle funzionalità e del codice.  
✅ Il sistema di **branching** consente un'organizzazione più efficiente del lavoro.

Ecco una descrizione chiara e completa dello **Sviluppo Distribuito in Git**, senza comandi ma con tutti i concetti fondamentali.

---

# **🌍 Sviluppo Distribuito in Git**

Lo **sviluppo distribuito** è uno dei principali vantaggi di Git rispetto ai sistemi di controllo versione centralizzati. Ogni sviluppatore possiede una **copia completa della repository**, compresa l’intera cronologia delle modifiche, e può lavorare in autonomia senza dipendere da un server centrale.

---

## **🔹 Caratteristiche dello Sviluppo Distribuito in Git**

✅ **Ogni sviluppatore ha una copia locale della repository**

- La copia locale include tutti i file del progetto e la loro cronologia.
- Non è necessario connettersi a un server per visualizzare o gestire le versioni precedenti del codice.

✅ **Non dipende da un server centrale**

- Si può lavorare offline e sincronizzare le modifiche solo quando necessario.
- Nessun blocco del lavoro in caso di problemi al server remoto.

✅ **Maggiore sicurezza**

- Se il server remoto si rompe, ogni sviluppatore ha una copia completa del progetto e può ripristinarlo.
- Nessuna perdita di dati grazie alle numerose copie distribuite tra i membri del team.

✅ **Migliore collaborazione**

- Ogni sviluppatore lavora indipendentemente senza interferire con gli altri.
- Le modifiche possono essere condivise e unite solo quando sono pronte.

✅ **Maggiore velocità**

- La maggior parte delle operazioni avviene localmente, senza bisogno di una connessione internet costante.
- Le modifiche vengono inviate al server remoto solo quando si decide di condividerle.

✅ **Ognuno ha il proprio pezzo di codice con la sua storia**

- Gli sviluppatori possono lavorare su diverse parti del progetto senza influenzarsi a vicenda.
- Ogni funzionalità o bug fix può essere sviluppato separatamente e unito in seguito.

---

## **📊 Vantaggi dello Sviluppo Distribuito**

| ✅ **Vantaggi**                                                                   | ❌ **Svantaggi**                                                        |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| **Lavoro indipendente**: nessun blocco in caso di problemi al server              | **Può essere complesso per i principianti**                             |
| **Più copie di backup**: minore rischio di perdita dati                           | **Possibili conflitti quando più persone modificano gli stessi file**   |
| **Migliore collaborazione**: gli sviluppatori possono lavorare separatamente      | **Richiede una buona organizzazione per gestire i contributi del team** |
| **Maggiore velocità**: la maggior parte delle operazioni avviene localmente       | **Necessario sincronizzarsi manualmente con gli altri sviluppatori**    |
| **Flessibilità nello sviluppo**: ogni sviluppatore ha il proprio spazio di lavoro | **Richiede una gestione efficace dei branch e delle revisioni**         |

---

## **🎯 Perché lo Sviluppo Distribuito è Utile?**

✔ Evita dipendenze da un server centrale.  
✔ Consente di lavorare ovunque, anche senza connessione internet.  
✔ Migliora la sicurezza del progetto grazie alle copie multiple.  
✔ Favorisce una collaborazione più efficiente tra i membri del team.  
✔ Permette di sviluppare e testare nuove funzionalità senza influenzare il codice principale.

---

**💡 Conclusione:**  
Lo **sviluppo distribuito** è uno dei punti di forza di Git. Grazie alla possibilità di lavorare indipendentemente e sincronizzarsi solo quando necessario, il processo di sviluppo diventa più flessibile, sicuro ed efficiente.

🚀 _Git semplifica la collaborazione e garantisce che il tuo codice sia sempre al sicuro!_

---

# **📂 I Tre Stati dei Dati nella Repository Git**

In Git, i file all'interno di un progetto possono trovarsi in **tre stati principali**:

1. 📝 **Modificato (Modified)**
2. 📌 **Staged (In Stage)**
3. ✅ **Commit (Committed)**

---

## **📝 1. Stato Modificato (Modified)**

🔹 Il file è stato modificato, ma **Git non lo ha ancora tracciato** ufficialmente.  
🔹 Le modifiche sono solo **nel file locale**, senza essere preparate per il commit.  
🔹 Se chiudi il progetto senza salvare lo stato, potresti perdere queste modifiche.

📍 _Esempio:_ Hai cambiato una riga di codice in un file, ma Git non è ancora stato informato della modifica.

---

## **📌 2. Stato Staged (In Stage)**

🔹 Il file è stato aggiunto all’**area di staging**, pronto per essere salvato nella cronologia.  
🔹 Git ora sa che il file deve essere incluso nel prossimo commit.  
🔹 Puoi continuare a lavorare su altri file senza compromettere quelli già aggiunti allo staging.

📍 _Esempio:_ Dopo aver modificato un file, lo hai segnato come pronto per il commit, ma non è ancora registrato nella cronologia ufficiale.

---

## **✅ 3. Stato Committed (Commit Salvato)**

🔹 Il file è stato **ufficialmente salvato nella repository Git**, diventando parte della cronologia.  
🔹 Il commit include una descrizione delle modifiche, permettendo di tornare indietro se necessario.  
🔹 Questo è lo stato più sicuro: le modifiche sono registrate e pronte per essere sincronizzate con altri sviluppatori.

📍 _Esempio:_ Hai salvato le modifiche con un commit e ora fanno parte della storia del progetto.

---

## **📊 Riepilogo dei Tre Stati**

| Stato          | Descrizione                                        | Icona |
| -------------- | -------------------------------------------------- | ----- |
| **Modificato** | Il file è cambiato, ma Git non lo traccia ancora.  | 📝    |
| **Staged**     | Il file è pronto per essere salvato con un commit. | 📌    |
| **Committed**  | Il file è stato salvato nella cronologia Git.      | ✅    |

---

### 🎯 **Perché è importante conoscere questi stati?**

✅ Aiuta a **gestire meglio le modifiche** nei file.  
✅ Evita **perdite di dati** accidentali.  
✅ Permette di **organizzare le modifiche** prima di salvarle nella storia del progetto.

## comandi configurazione utente del git

```bash
git config --global user.name "username"
git config --global user.email "email"
```

```bash
git comnfig --list  # visualizza tutti i parametri configurati
git init # inizializza una nuova repository

ls -la # visualizza tutti i file e cartelle nella directory corrente solo su git bash
dir # visualizza tutti i file e cartelle nella directory corrente solo su cmd o poweshell 
```
