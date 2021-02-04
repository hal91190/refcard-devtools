# Aide mémoire sur les outils de développement
Ce document présente une liste structurée d'outils de développement logiciel.

## Construction du document
Pour construire ce document, les outils suivants doivent être installés sur le système.
* bundler
* graphviz

### Installation des dépendances (gems)
```
$ bundle install
```

### Construction du document
```
$ asciidoctor -r asciidoctor-diagram -D html index.adoc
```
