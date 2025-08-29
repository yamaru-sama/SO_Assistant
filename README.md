<p align="center">
<img width="800" height="800" alt="Image" src="https://github.com/yamaru-sama/SO_Assistant/blob/main/logo.png" />
</p>

# SO_Assistant – Chatbot per Sistemi Operativi

**SO_Assistant** è un chatbot didattico sviluppato con [Dialogflow Standard](https://dialogflow.cloud.google.com/) e integrato con [Telegram](https://telegram.org/).  
Il progetto è stato realizzato come parte di un elaborato per offrire supporto agli studenti del corso di **Sistemi Operativi**, permettendo loro di porre domande in linguaggio naturale e ricevere risposte mirate sui contenuti del programma.

## 🎯 Obiettivi del progetto

- Fornire risposte rapide e affidabili su concetti come: file system, processi UNIX, shell, pipe, primitive C, ecc.
- Offrire un’interfaccia familiare tramite Telegram, accessibile 24/7.
- Utilizzare intents, entities e contexts per modellare una conoscenza tematica strutturata.
- Gestire follow-up e fallback per garantire una conversazione fluida.

## 📁 Contenuto della repository

- `SO_Assistant.zip` – Esportazione completa del progetto Dialogflow, contenente:
  - Intents (oltre 45)
  - Entities personalizzate
  - Event handlers (WELCOME, FALLBACK)
  - Contexts automatici per i follow-up Yes/No
- `README.md` – Questo file di descrizione

## 💬 Integrazione Telegram

L’agente è stato collegato a Telegram tramite **BotFather**. Per testarlo:

1. Apri Telegram e cerca il bot con il nome `@SO_Assistant_bot`.
2. Avvia una conversazione con `/start`.
3. Invia una domanda (es. *"Cos'è un processo in UNIX?"*).

> ⚠️ Nota: per eseguire una nuova integrazione con il tuo account, sarà necessario creare un nuovo bot Telegram con BotFather e aggiornare il token in Dialogflow.

## 📚 Collegamento alla tesi

Per dettagli teorici, progettuali e tecnici sul chatbot, è possibile consultare il documento completo dell'elaborato disponibile a richiesta all'indirizzo mail dylanepro@gmail.com.

## ✅ Requisiti minimi

- Un account Google con accesso a [Dialogflow Standard](https://dialogflow.cloud.google.com/)
- Un account Telegram per creare un bot tramite [@BotFather](https://t.me/BotFather)
- Connessione a Internet

## 📄 Licenza

Questo progetto è distribuito a scopo didattico e dimostrativo. Tutti i contenuti testuali derivano dal materiale del corso di Sistemi Operativi e sono utilizzati con finalità educative.
