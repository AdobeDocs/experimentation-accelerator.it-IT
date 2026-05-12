---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Utilizzo dei dati in AI con Journey Optimizer Experimentation Accelerator
topic: Content Management
role: User
level: Beginner
keywords: contenuto, esperimento, multiplo, pubblico, trattamento
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b3538224-471e-4c63-a444-9b19d89ae29cid: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dcid: b5ce8718-c3af-4fdb-a1a9-fca32f83a87cid: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: d095671a-1355-40aa-8b5f-06c33c68080bid: e1e0219c-f879-479f-8427-888ed2a6e9c2id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 2%

---

# Utilizzo dei dati in AI con Journey Optimizer Experimentation Accelerator{#experiment-accelerator-security}

**Adobe Journey Optimizer Journey Optimizer Experimentation Accelerator** ti consente di scoprire automaticamente informazioni approfondite e di consigliare opportunità per migliorare i tuoi esperimenti e il tuo programma di sperimentazione. La soluzione sfrutta l’intelligenza artificiale e l’apprendimento automatico per fornire questi consigli. Questa istruzione chiarisce come vengono utilizzati i dati dei clienti in **Journey Optimizer Experimentation Accelerator**.

## Quali dati utilizza Journey Optimizer Experimentation Accelerator?

Attualmente sono disponibili tre tipi di dati utilizzati da **Journey Optimizer Experimentation Accelerator**:

* **Metadati esperimento**: nome esperimento, definizione del pubblico utilizzato nell&#39;esperimento e i trattamenti nell&#39;esperimento, ad esempio nome, percentuali suddivise, posizione o superficie in cui viene distribuito l&#39;esperimento.

* **Prestazioni dei trattamenti**: numero di persone, media della metrica di successo e deviazione standard per ogni trattamento.

* **Contenuto del trattamento**: HTML con rendering e schermata del trattamento così come apparirebbe a un utente sul tuo sito Web.

## Che cosa fa Journey Optimizer Experimentation Accelerator con questi dati?

**Journey Optimizer Experimentation Accelerator** prende il contenuto di ogni trattamento e crea un&#39;incorporazione, ovvero una rappresentazione matematica del contenuto, quindi mette in correlazione tali incorporazioni con le prestazioni dei trattamenti. Questo processo consente l’estrazione degli attributi del contenuto con prestazioni migliori per utilizzi futuri. Tali attributi vengono quindi inseriti in un modello di linguaggio di grandi dimensioni ospitato da Adobe, che li converte in istruzioni leggibili dall’utente utilizzate per generare informazioni approfondite e suggerire opportunità.

## Quali restrizioni ha Journey Optimizer Experimentation Accelerator sui dati utilizzati?

Ogni cliente viene assegnato a un’organizzazione e a una sandbox specifiche. Per ogni sandbox viene addestrato un modello dedicato. Quando si elimina una sandbox, tutti i dati, i segnali e i modelli correlati vengono rimossi definitivamente.

* Utilizziamo solo i dati dei clienti per addestrare o perfezionare il modello da quel cliente.

* Non uniamo mai i clienti per addestrare o perfezionare un modello.

## I modelli Adobe o l’intelligenza artificiale cambieranno automaticamente l’esperienza utente di un brand?

No. **Journey Optimizer Experimentation Accelerator** fornisce solo consigli su cosa può essere modificato e come può essere modificato. Solo gli utenti che dispongono delle autorizzazioni per modificare l’esperienza utilizzando Journey Optimizer o Target potranno agire in base a questi consigli. Tutti i consigli possono essere rivisti e modificati prima di essere esclusi.

## Esiste un rischio per la stabilità dei dati o del sistema?

**Journey Optimizer Experimentation Accelerator** acquisisce e analizza solo i dati, producendo insight e consigli per test futuri. Non dispone dell’accesso per modificare le impostazioni di test. Tutti i suggerimenti generati all’interno dello strumento vengono inviati a Target e Journey Optimizer per l’implementazione, garantendo nessun impatto sulle attività correnti del cliente.
