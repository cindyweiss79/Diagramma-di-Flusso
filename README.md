# Diagramma-di-Flusso cleanROOMS

# Controllo Camere e Minibar – Script JavaScript

Questo script interattivo in JavaScript simula il controllo delle camere di un hotel e dei rispettivi minibar, chiedendo all'utente lo stato della stanza e del minibar, e notificando le azioni da intraprendere.

## 🚀 Funzionalità

- Chiede se la stanza è sporca e fornisce un messaggio in base alla risposta.
- Controlla se il minibar è vuoto e notifica un eventuale rifornimento.
- Permette all'utente di ripetere il processo per più stanze.

## 🧠 Come funziona

1. Lo script avvia un ciclo `while` che continua finché ci sono camere da controllare.
2. Per ogni iterazione:
   - Chiama `cleanRoom()`: chiede se la stanza è sporca (`sì/no`).
   - Chiama `checkMiniBar()`: chiede se il minibar è vuoto (`sì/no`).
   - Alla fine chiede se ci sono altre camere da controllare.
3. Il ciclo si interrompe quando l’utente risponde **"no"**.

## 💻 Esecuzione

Puoi eseguire questo script direttamente in un ambiente browser:

1. Apri il browser.
2. Apri gli strumenti di sviluppo (`F12` o clic destro → "Ispeziona" → scheda "Console").
3. Incolla il codice nella console e premi `Invio`.

## 📋 Esempio di interazione

```plaintext
La stanza è sporca? (sì/no)
> sì
Pulizia in corso...

Il minibar è vuoto? (sì/no)
> no
Il minibar è a posto.

Ci sono altre camere da controllare? (sì/no)
> sì
... (ripete il processo)
