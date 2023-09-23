# Vorlage für DPSG Stammeshomepage mit Hugo

## Vorraussetzungen

* [Hugo](https://gohugo.io/getting-started/installing/)
* [Git](https://git-scm.com/downloads)

## Installation

```bash
git clone  https://github.com/emhl/dpsg-website.git
cd bezirk-website
git submodule update  --init
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
