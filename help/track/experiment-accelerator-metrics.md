---
solution: Journey Optimizer
product: journey optimizer
title: Metriche di Journey Optimizer Experimentation Accelerator
description: Migliora la tua capacità di condurre esperimenti in modo efficace e generare insight
topic: Content Management
role: User
level: Beginner
keywords: contenuto, esperimento, multiplo, pubblico, trattamento
TQID: https://experienceleague.adobe.com/OrtdIfQfKMIWODRi9fr-dEuc7g06hISv6-Dq-54qGeY
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 364
ht-degree: 6%

---

# Metriche {#experiment-accelerator-metrics}

Nella pagina **[!UICONTROL Metriche]** le metriche di successo degli esperimenti di Journey Optimizer e Target vengono visualizzate in un&#39;unica posizione, consentendo il monitoraggio delle prestazioni, il confronto e informazioni più approfondite.

## Dashboard di {#dashboard}

Quando si accede alla scheda **[!UICONTROL Metriche]**, tutte le metriche di successo disponibili in Journey Optimizer e Adobe Target sono elencate in una visualizzazione consolidata per consentire di tenere traccia delle prestazioni tra le iniziative, confrontare i risultati e identificare rapidamente le aree che richiedono attenzione.

Accedere ai filtri facendo clic su ![](assets/do-not-localize/Smock_Filter_18_N.svg), che offre opzioni specifiche del contesto, ad esempio il filtro per **[!UICONTROL Source]** o **[!UICONTROL Utilizzato in esperimenti attivi]**.

In alternativa, puoi trovare rapidamente una metrica digitandone il nome nella barra di ricerca.

![](assets/experiment-monitor-metrics.png)

## Dettagli metrica {#metric-details}

### Incrementale nel tempo

![](assets/experiment-monitor-metrics-2.png)

Il grafico **[!UICONTROL Incrementale nel tempo]** fornisce un&#39;analisi visiva della tendenza della metrica selezionata in un intervallo di tempo scelto. Utilizza il menu a discesa per passare dalla visualizzazione giornaliera a quella settimanale e viceversa, in modo da regolare il livello di granularità.

Per riferimento rapido sono disponibili i seguenti valori di riepilogo:

* **[!UICONTROL Totale]**: il valore cumulativo della metrica selezionata nel periodo di reporting.

* **[!UICONTROL Media]**: valore tipico della metrica calcolato nell&#39;intervallo di tempo selezionato. Il bilanciamento delle fluttuazioni giornaliere o settimanali consente di ottenere un quadro più chiaro delle prestazioni normali e può essere utilizzato come base di confronto.

* **[!UICONTROL Tasso di conversione]**: percentuale di profili che hanno completato l&#39;azione desiderata (ad esempio, acquisto, iscrizione) dopo aver visto il trattamento.

Ciascun valore include una variazione percentuale rispetto al periodo precedente, per verificare facilmente se le prestazioni stanno migliorando, diminuendo o rimanendo stabili.

### Effetto esperimento

![](assets/experiment-monitor-metrics-3.png)

Questa sezione mostra tutti gli esperimenti attivi entro l’intervallo di tempo selezionato (Ultimi 90 giorni, Ultimi 30 giorni o Ultimi 7 giorni) ed evidenzia il loro contributo alla metrica.

Sono disponibili le metriche seguenti:

* **[!UICONTROL Incremento]**: misura del miglioramento percentuale del tasso di conversione di un determinato trattamento rispetto al basale.

* **[!UICONTROL Affidabilità]**: prova che un determinato trattamento è uguale al trattamento basale. [Ulteriori informazioni](http://experienceleague.adobe.com/it/docs/journey-optimizer/using/content-management/content-experiment/technotes/experiment-calculations)

* **[!UICONTROL Contributo]**: proporzione della modifica complessiva della metrica che può essere attribuita a un esperimento o a un trattamento specifico, consentendo l&#39;identificazione delle iniziative che esercitano il maggiore impatto relativo.
