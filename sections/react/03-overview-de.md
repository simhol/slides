# React.js Überblick

## Was ist React?

- Eines der 3 großen JavaScript UI Frameworks (neben Angular, Vue.js)

## Grundlagen moderner JavaScript UI Frameworks

- deklarativ
- Komponenten-Struktur

## Deklarativ

- Datenmodell, das den gesamten Anwendungszustand abbildet
- User-Interaktionen ändern das Modell, das View wird automatisch aktualisiert

## Komponenten-Struktur

- "eigene" HTML-Tags
- Datenfluss via Properties und Events
- Üblicherweise unidirektionaler Datenfluss (vom Eltern- zum Kindelement)

## Beispiel: Datenmodell und -fluss in einer Todo-App

<img src="assets/todo-components-datamodel.svg" />

## Was macht React besonders?

- JavaScript-basierte Template-Syntax
- Explizite Änderung des Anwendungszustands mittels Settern
- State-Objekte sind unveränderlich (immutable)

## Geschichte von React

- 2013 von Facebook als open source veröffentlicht
- Februar 2019: Einführung von Hooks
- bevorstehende Ergänzungen: [suspense for data fetching](https://reactjs.org/docs/concurrent-mode-suspense.html) und [concurrent mode](https://reactjs.org/docs/concurrent-mode-intro.html)
