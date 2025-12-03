# Linee Guida per l’Anonimizzazione dei Dati – InSIDE Lab

Queste linee guida definiscono le procedure minime per garantire che i dati condivisi nel repository siano sicuri e non identifichino individui o entità.

---

## 🔒 1. Rimuovere informazioni identificative
Eliminare completamente:
- nomi e cognomi,
- indirizzi, telefoni, email,
- ID fiscali, codici cliente, matricole,
- coordinate geografiche precise.

---

## 🔐 2. Aggregare variabili sensibili
Sostituire valori granulari con categorie:
- età → classi di età,  
- reddito → fasce di reddito,  
- localizzazione → area geografica amplia.

---

## 🔄 3. Simulare o perturbare i dati
Opzioni possibili:
- aggiunta di rumore casuale,
- generazione di dataset sintetici,
- sostituzione con distribuzioni simulate.

---

## 🧪 4. Controllo finale
Prima del caricamento, verificare che:
- nessuna persona o impresa sia identificabile,
- non esistano combinazioni univoche,
- sia esplicitata la fonte dei dati.

---

## 📂 5. Formati consigliati
- CSV  
- Parquet  
- Stata (`.dta`) se serve compatibilità

---

## ❗ Nota importante
La responsabilità dell’anonimizzazione ricade su chi carica i dati.  
In caso di dubbio, **non pubblicare**.
