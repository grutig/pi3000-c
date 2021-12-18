# Pi3000 release c  
December 2021  
  
SIMH emulator for HP3000 / CLASSIC (Series III)  
download link: https://www.i8zse.eu/project-pi3000-release-c/  
  
I have updated the HP3000 emulator to version 10, and reorganized the whole project.  
  
To allow greater usability, it is now a package - that can be installed on various platforms -  
contained in a single .zip file. Just unzip the zip file in a directory of your choice  
and rename the compiled executable for your platform, contained in the directory /bin,  
simply deleting the extension:  
  
hp3000.bsd FreeBSD  
hp3000.linux Linux x86  
hp3000.osx MacOSx  
hp3000.rpi2 Raspberry Pi2  
hp3000.rpi4 Raspberri Pi4  
  
For windows, the hp3000.exe executable must remain unchanged, just use its specific batches (.cmd)  
  
there are two batches  
mpe-auto:  
starts the MPE operating system skipping the initial configuration phase  
mpe-man:  
boot the MPE operating system in the traditional way.  
  
The configuration includes two hard drives (a 7920 and a 7925), a 7970 tape drive  
  
The operating system is derived from the software kit available at http://simh.trailing-edge.com/hp/  
In addition to the operating system, the image is pre-installed with the HP3000 Contributed Software Library tape  
Release 7 of 1981. The Contributed Library was a freely usable, non-commercial software library,  
distributed through the HP3000 regional user groups.  
The list of installed files is available at http://www.3kranger.com/HP3000/CSL/CSL7STDL.txt  
All files are documented in the DOC.MAINLIB group inside the emulation; files can be read using the command  
: EDITOR  
/ TEXT <filename> .DOC.MAINLIB  
/ LIST ALL  
/ EXIT  
All sources are in SOURCE.MAINLIB.  
There is also an MGR.GAMES account with some games, on ADV.GAMES account there is the porting for HP300  
of original Colossal Cave Adventure.  
  
If you are interested to HP3000 you can check two sites:  
Managing HP 3000 Systems - for Complete Novices at URL http://www.3kranger.com/Interact/stachnik/Stachnik.shtm  
The original manuals are instead available at URL http://www.bitsavers.org/pdf/hp/3000/   
  
SIMH Copyright (c) 1993-2005, Robert M Supnik  
HP3000 emulator Copyright (c) 2011-2021, J. David Bryan  
  
DISCLAIMER  
  
The MPE operating system is (C)Hewlett-Packard, and is used under Fair Use for hystorical and educational purposes.   
All rights and credits go directly to its rightful owners.   
No copyright infringment intended.  
  
  
--------------------------------  
  
# Pi3000 release c
Dicembre 2021

Emulatore SIMH per HP3000/CLASSIC (Series III)
download link: https://www.i8zse.eu/project-pi3000-release-c/

Ho aggiornato l'emulatore HP3000 alla versione 10, e riorganizzato complessivamente il progetto.

Per consentire una più amplia utilizzabilità ora è un pacchetto - installabile su varie piattaforme -
contenuto in un singolo file .zip. E' sufficiente scompattare il file zip in una directory a scelta 
e rinominare l'eseguibile compilato per la propria piattaforma, contenuto nella directori /bin, 
eliminando l'estensione:

hp3000.bsd   FreeBSD	
hp3000.linux Linux x86
hp3000.osx   MacOSx
hp3000.rpi2  Raspberry Pi2
hp3000.rpi4  Raspberri Pi4

Per windows, l'eseguibile hp3000.exe deve rimanere inalterato, è sufficiente usare i suoi batch specifici (.cmd)

ci sono due batch 
mpe-auto:
avvia il sistema operativo MPE saltando la fase di configuerazione iniziale
mpe-man:
avvia il sistema operativo MPE in modo tradizionale.

La configurazione prevede due dischi fissi (un 7920 ed un 7925), una unità a nastro 7970

Il sistema operativo è derivato dal software kit disponibile su http://simh.trailing-edge.com/hp/
Oltre al sistema operativo, nell'immagine è preinstallato il nastro della Contributed Software Library HP3000
Release 7 del 1981. La Contributed Library era una libreria di software non commerciale e liberamente utilizzabile, 
distribuito dai regional user group HP3000. 
L'elenco dei file installati è consultabile su http://www.3kranger.com/HP3000/CSL/CSL7STDL.txt
Tutti i file sono documentati nel gruppo DOC.MAINLIB; i file possono essere letti usando il comando
:EDITOR
/TEXT <nomefile>.DOC.MAINLIB
/LIST ALL
/EXIT
Tutti i sorgenti sono in SOURCE.MAINLIB.
E' inoltre presente un account MGR.GAMES con alcuni giochi, mentre su ADV.GAMES è disponibile il porting per
hp3000 di Colossal Cave.

Segnalo a chi fosse interessato altri due siti per approfondire l'argomento HP3000:
Managing HP 3000 Systems – for Complete Novices su http://www.3kranger.com/Interact/stachnik/Stachnik.shtm 
I manuale originali sono invece disponibili su http://www.bitsavers.org/pdf/hp/3000/

SIMH Copyright (c) 1993-2005, Robert M Supnik
HP3000 emulator Copyright (c) 2011-2021, J. David Bryan

DISCLAIMER
 
Il sistema operativo MPE è (C)Hewlett-Packard e viene utilizzato in Fair Use con finalità storiche ed educative.
Tutti i diritti e crediti vanno direttamente ai legittimi proprietari, e non c'è nessuna intenzione di violare copyright. 
