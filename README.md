# Git Demo

Hallo Lena.

---

## Geht immer
### Status abfragen
git status
### Anzeigen der vergangenen Commits
git log --all --decorate --graph

## Adden und committen
git add file
git commit -m 'Beschreibung' oder git commit (öffnet Editor)

## commit ändern, geht aber nur vorm pushen!!
git commit --amend

## Packt den Schmu auf Git
git push

## Schmu von Git auf lokalen PC
git pull

---

## Little Story
Es war einmal ein Git Repository...

Da erzeugte man einen Branch:

git branch little_story 

git branch

git checkout little_story

Dinge tun auf Branch little_story, adden und committen 

git checkout master

Dinge auf Master tun, adden und committen

git merge little_story
