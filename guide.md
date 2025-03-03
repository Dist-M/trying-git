### Tenere aggiornata la repository locale - ```git fetch```

eseguendo questo comando, aggiorno le refernze del mio locale con quelle della repository online


### Tenere traccia dei propri sviluppi - ```git status```
mostra lo stato attuale della mia repository locale rispetto alla repository online; con precisione mette in evidenza:
- su quale branch mi trovo
- se il mio branch è allineato con quello online (non controlla un nuovo stato della repository, online, fare una ```git fetch``` per aggiornare questa informazione)
- quali file sono stati modificati e se quest'ultimi si trovano in fase di staging o meno


### Aggiungere i file alla fase di staging - ```git add [path/to/file]```
i file specificati nel comando - ```git add``` vengono agiunti alla **fase di staging** e preparati per una eventuale **commit**

### Creare una nuova commit - ```git commit -m "your message"```
i file presenti nella **fase di staging** vengono _commmittati_:
- viene creata una nuova **commit** 
- la **commit** viene aggiunta al mio **branch locale**

NB: questa commit è presente solo sul mio branch locale


### Aggiungere modifiche alla repository online - ```git push```
le modifche effettuate e _commitatte_ sul branch locale venono aggiunte al branch nella repository online

### Sincronizzare il branch locale con le modifiche online - ```git pull```
con questo comando contorllo se ci sono nuove commit sul corrispettivo online dl branch in cui mi trovo, ed eventualmente porto le modifiche anche sul mio branch locale 

