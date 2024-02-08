# DeepBrainMRI
Il progetto mira allo sviluppo di un sistema diagnostico per identificare e classificare tumori cerebrali attraverso immagini di risonanza magnetica. Questa innovazione potrebbe estendersi a modelli più avanzati, assistendo professionisti non solo nella diagnosi delle malattie più comuni, ma anche delle malattie più rare e complicate da diagnosticare. L'intelligenza artificiale offre un potenziale significativo nell'ambito medico, migliorando la precisione diagnostica e supportando il trattamento.   

**Risorse Utili:** 
È possibile visualizzare la presentazione finale a <a href="">questo link<a>.    
È possibile leggere il report finale a <a href="">questo link<a>.    
È possibile trovare il dataset originale <a href="https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset">qui</a>.

# Installazione
**Requisiti:**   
*  Un account <a href="https://www.kaggle.com">www.kaggle.com</a>.     
*  Un account Google per poter accedere a <a href="https://colab.research.google.com">Google Colab</a>.     

**Seguire i seguenti passaggi:**   
1) Andare su Kaggle, effettuare il login e recarsi nelle impostazioni cliccando l'immagine in alto a destra e poi su `settings`;       
2) Nella sezione **API** cliccare su `Create New Token` e si avvierà il download di un file chiamato "_kaggle.json_";
3) Scaricare i Notebook da GitHub e caricarli tutti sulla stessa cartella su Google Drive;     
 **NOTA:** _È fortemente consigliato di creare la cartella del progetto nella propria home su Google Drive. Qualora si voglia comunque utilizzare una cartella differente sarà necessario aggiornare il percorso della cartella su ogni notebook._
4) Una volta caricati su Google Drive in una cartella comune, aprire il file chiamato `Dataset (Download + Pre-Processing).ipynb` ed eseguire le prime istruzioni;
5) Quando verrà chiesto di caricare il file _kaggle.json_, inserire il file scariato al punto n°2;
6) Dopo che opendatasets avrà ricevuto il file json avvierà il download del dataset. Ora è possibile pre-processarlo a propria scelta e salvarlo su Google Drive, in modo che sia facilmente accessibile agli altri notebook;     
  **NOTA**: _A causa di limitazioni di Google Drive, potrebbero essere necessari diversi minuti affinché il dataset salvato risulti visibile e accessibile dai notebook!_
8) Una volta salvato uno o più datasets, questi saranno facilmente importabili negli altri notebook e utilizzabili con i vari modelli;

# Struttura del progetto
Il progetto è stato organizzato in più notebook in base ai modelli e alle operazioni da effettuare:    
`Dataset (Download + Pre-Processing).ipynb` : permette di scaricare il dataset, analizzarlo, eseguire diversi tipi di pre-processing e salvarlo su Google Drive.
. . .

# Autori
<a href="https://github.com/TheRoberto2512">Roberto A. Usai</a>  
<a href="https://github.com/Cipe96">Marco Cipollina</a>   
<a href="https://github.com/danif95">Daniele Fenu</a>      
