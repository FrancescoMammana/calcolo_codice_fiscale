# Calcolo Codice Fiscale Italiano 🇮🇹

> Strumento web per calcolare e verificare il Codice Fiscale italiano e la Partita IVA.  
> 100% client‑side, zero dipendenze, zero build.

**[→ Apri il sito](https://francescomammana.github.io/calcolo_codice_fiscale/)**

---

### Funzionalità

| Funzione | Descrizione |
|---|---|
| **Genera da Dati** | Genera il codice fiscale completo (16 caratteri) da cognome, nome, data di nascita, sesso e codice catastale |
| **Verifica Cifra CF** | Calcola la cifra di controllo (16° carattere) dai primi 15 caratteri di un codice fiscale |
| **Verifica Cifra P.IVA** | Calcola la cifra di controllo (11° cifra) di una Partita IVA con algoritmo di Luhn |
| **Decodifica CF** | Decodifica un codice fiscale di 16 caratteri: estrae anno, mese, giorno, sesso, codice catastale e verifica la cifra di controllo |

---

### Stack

- Singolo file `index.html` (HTML + CSS + JS inline)
- JavaScript ES6+ vanilla, CSS custom properties
- Tema chiaro/scuro automatico (`prefers-color-scheme`)
- Sistema di tab per le 4 modalità
- **Zero** dipendenze esterne, **nessun** build step

---

### Deploy

Ad ogni push su `main`:
1. GitHub Actions carica l'artefatto
2. Viene deployato automaticamente su GitHub Pages

---

### Primi passi

```
git clone git@github.com:FrancescoMammana/calcolo_codice_fiscale.git
cd calcolo_codice_fiscale
```

Non serve installare nulla. Apri `index.html` nel browser o servilo con:

```
python3 -m http.server 8000
```
