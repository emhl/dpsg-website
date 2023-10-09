# Vorlage für DPSG Stammeshomepage mit Hugo

## Vorraussetzungen

* [Hugo](https://gohugo.io/getting-started/installing/)
* [Git](https://git-scm.com/downloads)

## Installation

Erstelle ein neues Repository auf GitHub, anhand dieser Vorlage (Knopf "Diese Vorlage verwenden" oben rechts).

Lade das Repository herunter und starte den lokalen Server:

```bash
git clone  https://github.com/BENUTZERNAME/dpsg-website.git
cd dpsg-website
hugo serve
```

Browser öffnen: <http://localhost:1313>

## Konfiguration

Die Konfiguration erfolgt in der Datei `config.toml`.

Neue Seiten können im Ordner `content` angelegt werden. Die Datei `content/_index.md` ist die Startseite.

## Auf Webserver aufspielen

```bash
hugo
```

Die generierten Dateien befinden sich im Ordner `public`. Dieser kann auf den Webserver kopiert werden.

## Theme aktualisieren

falls sich etwas am [Theme](https://github.com/emhl/hugo-dpsg) ändert, und du diese Änderungen übernehmen möchtest, kannst du mit

```bash
hugo mod get -u github.com/emhl/hugo-dpsg
```

das Theme aktualisieren.

Dort findest du auch die Dokumentation zum Theme. und andere Installationsmöglichkeiten, welche es dir erlauben, das Theme zu verändern.
