![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)

# DeepBrainMRI
Il progetto mira allo sviluppo di un sistema diagnostico per identificare e classificare tumori cerebrali attraverso immagini di risonanza magnetica. Questa innovazione potrebbe estendersi a modelli più avanzati, assistendo professionisti non solo nella diagnosi delle malattie più comuni, ma anche delle malattie più rare e complicate da diagnosticare. L'intelligenza artificiale offre un potenziale significativo nell'ambito medico, migliorando la precisione diagnostica e supportando il trattamento.   

<p align="center"><img src="https://github.com/TheRoberto2512/DeepBrainMRI/assets/70667004/ef4a5842-79d3-4c9b-8de1-8fff5fc9e8ae"></p>

# Risorse Utili
Il report finale è consultabile a <a href="https://drive.google.com/file/d/10R7wBGUi1C4-gfKmDy9DlV3-mn4EjmI-/view?usp=sharing">questo link<a>. Si può reperire il dataset originale <a href="https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset">qui</a>. È inoltre possibile scaricare direttamente i pesi dell'EfficientNetV2S Fine Tuning a <a href="https://drive.google.com/file/d/1gOhUuTudMDyIe6SPYTvVHbb_M1fNS5de/view?usp=sharing">questo link<a>.
Tutti i riferimenti a siti, documenti e/o persone sono riportati alla fine del report finale.

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
7) Una volta salvato uno o più datasets, questi saranno facilmente importabili negli altri notebook e utilizzabili con i vari modelli.

# Struttura del progetto
Il progetto è stato organizzato in più notebook in base ai modelli e alle operazioni da effettuare:    
| Nome File | Operazioni effettuabili |
| :---: | :---: |
| **Dataset (Download + Pre-Processing).ipynb** | Permette di scaricare il dataset, analizzarlo ed eseguire diversi tipi di pre-processing|       
| **Modello Dense.ipynb** | Permette di addestrare un modello Dense e verificarne le prestazioni |    
| **Modello Convolutivo.ipynb** | Permette di addestrare un modello Convolutivo e verificarne le prestazioni |     
| **Modello EfficientNetV2S.ipynb** | Permette di osservare le prestazioni dell'EfficientNetV2 con e senza Fine Tuning |      
| **Analisi dei risultati.ipynb** | Permette di mettere a confronto i vari modelli e le loro performance |

# Librerie utilizzate
All'interno dei notebook sono state utilizzate le seguenti librerie:
| Nome Libreria | Utilizzo |
| :---: | :---: |
| `Tensorflow` e `Keras` | Per utilizzare i modelli, i layer e i tensori  |
| `OpenDatasets` | Per il download del dataset da kaggle |
| `Numpy` e `Pandas` | Per operazioni di processing |
| `MatPlotLib` | Per visualizzare i dati graficamente |
| `os` e `shutil` | Per gestire file e cartelle |
| `scikitlearn` | Per le matrici di confusione |
| `PIL` | Per manipolazione e salvataggio delle immagini |

# Autori
<a href="https://github.com/TheRoberto2512">Roberto A. Usai</a>  
<a href="https://github.com/Cipe96">Marco Cipollina</a>   
<a href="https://github.com/danif95">Daniele Fenu</a>      
