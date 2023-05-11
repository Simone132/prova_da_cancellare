# GITHUB #

git config --global user.email "you@example.com"

  git config --global user.name "Your Name"

- 2 generare il token con il pannello di controllo di GITHUB nella sezione Developer settings

- 3 scegliere tra gli scope disponibili cioè le funzionalità alle quali avrà accesso il nostro profilo GITHUB

- 4 gh auth login in visual studio code e seguire la procedura


## CREARE UN REPOSITORY ##

- 1 creare il repository con Github.

- 2 creare un repository locale attraverso il comando
  git init

- 3 aggiungiamo il files readme con il comando
  git add README.md

- 4 facciamo il nostro primo commit che significa creare un nuovo salvataggio del documento staged
  git commit -m "first commit"
(faccio git status per vedere lo stato, che sarà on branch master)

- 5 creiamo il branch main e cioè il ramo principale nel quale avverranno le modifiche
  git branch -M main       (git branch nomeBranch permette di spostarsi da un branch all'altro, qua stiamo creando il main rinominando il master)

- 6 aggiungimo l'origine remota cioè la destinazione dei nostri commit
  git remote add origin https://github.com/delectablerec/java-fullstack-assign.git

- 7 lanciamo il comando per caricare il contenuto aggiunto alla staged area in questo caso il README.md
  git push -u origin main 





