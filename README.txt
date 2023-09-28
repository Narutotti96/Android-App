Frasca Manuel 

Il programma serve a mostrare un'attività multitask in Android.
Nella pagina principale si preme un bottone il quale avvia una seconda attività mettendo in attesa la principale.
Successivamente nella seconda attività si inserisce un testo in input che poi cliccando il bottone analogo si ritorna all'attività principale visualizzando l'input immesso come risultato.
 
All'interno di questo file sono presenti il file MainActivity.kt che è il file principale dove è presente un bottone da premere per avviare la seconda attività (SecondActivity.kt).
Il file SecondActivity.kt che è il file con il processo secondario dove è presente un testo che verrà preso in input ed inviato all'attività principale (MainActivity.kt). 

Per la scrittura del codice è stato usato l’IDE Android Studio Flamingo | 2022.2.1 Patch 1
Build #AI-222.4459.24.2221.9971841, built on April 19, 2023
Runtime version: 17.0.6+0-17.0.6b802.4-9586694 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
Linux 5.19.0-46-generic
GC: G1 Young Generation, G1 Old Generation
Memory: 1280M
Cores: 12
Registry:
    external.system.auto.import.disabled=true
    ide.text.editor.with.preview.show.floating.toolbar=false
    gradle.version.catalogs.dynamic.support=true


Current Desktop: ubuntu:GNOME in un sistema Linux Ubuntu 22.04.2.

la versione SDK è la 33, per le API è la 24 analogamente ho utilizzato come emulatore un NEXUS 4 con le API 24.


Il tutto è stato svolto in linguaggio Kotlin.
