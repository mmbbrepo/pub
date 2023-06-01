# Pentaho 
## Installazione e configurazione ambiente di sviluppo (SPOON ) 9.3

Prerequisiti: Java SDK 11 , Windows 

### Installazione Java
Se gia non  installato , scaricare il sowftare di  installazione dell'SDK di  Java dal link segnalato nella sezione   [Risorse](#java_sdk).
Una volta scaricato procedere con l'installazione confermando le opzioni presentate a video

### Configurazione ambiente
Dovranno essere impostate due variabili di ambiente
* Java Home : dove verra specificata la cartella dove si è installata l'SDK java es .C:\Program Files\Java\jdk-11

* Path: verificare che il pacchetto di installazione abbia aggiunto il percorso degl eseguibii di java es: C:\Program Files (x86)\Common Files\Oracle\Java\javapath


### Verifica dell'ambiente
Aprire il prompt dei comandi DOS e digitare il seguente comando 
```dos
java -version
```
verrà presentata a video la versione dell'ambiente java installato 

```dos
java version "13-ea" 2019-09-17
Java(TM) SE Runtime Environment (build 13-ea+33)
Java HotSpot(TM) 64-Bit Server VM (build 13-ea+33, mixed mode, sharing)
```

## Installazione Pentaho
Scaricare dal sito di cui il link è presente nella sezione [Risorse](#pentaho) il pacchetto di installazione e decomprimerlo in una cartella del computer 

Dalla cartella di installazione accedere alla sottocartella **data-integration** e lanciare il bat **spoon.bat**











# Resources

## Software 

Ambiente di sviluppo IDE  (SPOON) <a  name="pentaho"></a>[https://sourceforge.net/projects/pentaho/](https://sourceforge.net/projects/pentaho/)

Java SDK 11 
<a name="java_sdk"></a>[https://www.oracle.com/it/java/technologies/javase/jdk11-archive-downloads.html](https://www.oracle.com/it/java/technologies/javase/jdk11-archive-downloads.html)

## Sorgenti
Sorgenti Pentaho [https://github.com/orgs/pentaho/repositories?type=all](https://github.com/orgs/pentaho/repositories?type=all)