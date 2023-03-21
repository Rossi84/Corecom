Esportazione dati
=================


In questa sezione illustreremo come esportare i dati ed elaborarli mediante Microsoft Excel 2016 o versioni successive. Dal menù Conciliazioni e Definizioni, selezionare i filtri di ricerca e premere il tasto **Cerca**. Successivamente premere il tasto **Esporta** per scaricare il file CSV contenente i dati filtrati.


.. figure:: /media/esportazione_dati1.png
   :align: center
   :name: esportazione-dati1
   :alt: Esportazione dati1
   
   Esportazione dati Passo 1



Aprire un nuovo foglio di lavoro Microsoft Excel. Dal menù **Dati**, selezionare l'icona **Da Testo/CSV** ed aprire il file CSV scaricato al passo precedente. Premere il tasto **importa**. 

.. figure:: /media/esportazione_dati2.png
   :align: center
   :name: esportazione-dati2
   :alt: Esportazione dati2
   
   Esportazione dati Passo 2

.. figure:: /media/esportazione_dati3.png
   :align: center
   :name: esportazione-dati3
   :alt: Esportazione dati3
   
   Elaborazione dati Passo 3


Selezionare **Trasforma Dati**  per eliminare le colonne che non faranno parte dell'elaborazione (es descrizione del problema, iban cliente etc) o per elaborare i dati. In alternativa, selezionare  **Carica** per visualizzare tutti i dati presenti nel CSV. 

.. figure:: /media/esportazione_dati4.png
   :align: center
   :name: esportazione-dati4
   :alt: Esportazione dati4 
   
   Elaborazione dati Passo 4


Calcolare la durata procedimentale
==================================

Dal menù **Trasforma Dati** selezionale la colonna **Data fine** nel foglio di lavoro. Con il tasto destro del mouse, selezionare **Trasforma tipo** da **Data/Ora** in **Data**.
Dal menù **Aggiungi colonna**, selezionare colonna personalizzata ed aggiungere la formula =Duration.Days([Data fine]-[Data istanza]) per calcolare la durata dei procedimenti in giorni.

.. figure:: /media/esportazione_dati5.png
   :align: center
   :name: esportazione-dati5
   :alt: Esportazione dati5
   
   Elaborazione dati Passo 5


.. figure:: /media/esportazione_dati6.png
   :align: center
   :name: esportazione-dati6
   :alt: Esportazione dati6
   
   Elaborazione dati Passo 6