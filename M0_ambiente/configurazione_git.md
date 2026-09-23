### ESERCIZIO 4

COMANDI USATI:

```
git config --global user.name "Leila Karic"

git config --global user.email "leila.karic@marconirovereto.it"

git config --global init.defaultBranch main

git config --global core.editor "code --wait"
``` 

OUTPUT OTTENUTO DOPO IL COMANDO:
```
git config --list --show-origin
```

```
path=true
file:C:/Program Files/Git/etc/gitconfig init.defaultbranch=master
file:Z://.gitconfig     user.name=Leila Karic
file:Z://.gitconfig     user.email=leila.karic@marconirovereto.it
file:Z://.gitconfig     init.defaultbranch=main
file:Z://.gitconfig     core.editor=code --wait

```