## 👥 ***TalkAware: uno strumento basato su LLM per il contrasto alla Cyber Intimate Partner Violence***
#### 💻 Progetto di tesi in Metodi per il Ritrovamento dell'Informazione - Finiguerra Alessia

---

### 🧠 Introduzione
Il crescente utilizzo dei Social Media e della tecnologia ha portato alla diffusione di un preoccupante fenomeno, la ***Cyber Intimate Partner Violence***, ovvero la violenza in chiave digitale esercitata nei confronti del partner.  

A tal proposito, è stato sviluppato ***TalkAware***, uno strumento in grado di identificare precocemente segnali di violenza digitale all'interno delle dinamiche di coppia.  

Sfruttando le potenzialità offerte dai Large Language Models e usufruendo della loro natura generativa, ***TalkAware*** è in grado non solo di classificare ma anche di fornire una spiegazione sul fenomeno rilevato.

---

### 🔍 Struttura del repository
Il repository contiene:
- ```finetune_talkaware.py```: contiene il codice per effettuare il Fine-Tuning e il DPO del modello;
- ```interfaccia_talkaware.py```: contiene il codice per la creazione del dimostratore strutturato come una chat;
- ```style_css.css``` e ```style_html.html```: file di formattazione grafica (presenti anche sul repository personale su *HuggingFace Hub*);
- ```toxic_dpo.csv```: dataset utilizzato durante la fase di DPO;
- ```toxic_ft.csv```: dataset utilizzato durante la fase di Fine-Tuning.

---
