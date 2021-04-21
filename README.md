# Softwareentwicklung und Projektmanagement (SWPP)

## Allgemeines 

Diese **Dokumentation** begleitet das Fach **SWPP**. Es werden diverse Dokumentationen für 
unterschiedliche Projekte mit `Markdown` erstellt. 

![Projektmanangement](_media/istockphoto-980272768-612x612.jpg)

## Lehrplan
 <!-- tabs:start -->

#### ** Bildungs- und Lehraufgabe **

* Phasen des Projektmanagements in der Software erläutern
* phasenbezogene Dokumente unterscheiden und erklären
* zyklische Sichtweise des Phasenmodells
* Projektmanagement im Bezug auf eine *komplexe betriebswirtschaftliche Applikation* aus **APR**

#### ** Lehrstoff **

- Planungsphase
- Definitionsphase
- Entwurfsphase
- Implementierungsphase
- Abnahme 
- Einfürungsphase
- Wartungs- und Pflegephase


<!-- tabs:end -->

## Technische Umsetzung
die Technische  Umsetzung erfolgt in einem **Github-Projekt**. Für die Arbeit mit Dokumentation wird mit `Markdown` gearbeitet.
Als Software zur Erstellung der Dokumentation wird [docsify](https://docsify.js.org/#/) eingesetzt.

### Hinweise
Hinweise werden mittels `?>` erstellt. Ein wichtiger Inhalt kann mit `!>` gekennzeichent werden.

?> Das ist ein Hinweis.

!> Das ist absolut wichtig.

### Quelltexte
Quelltexte werden mit `Prism.js` dargestellt und werden folgendermaßen gestaltet:

```bash 
npm i docsify-cli -g
```

```bash
docsify init .
```

```bash
docsify serve .
```

Eine C#-Datei wird mit `Datei.cs` benannt. Der Quellcode einer Datei wird formatiert dargestellt:

```csharp
public class Demo{
    public string Text => "Hallo Welt!";
}
```

### Emoji
Emojis werden ebenfalls unterstützt:

:100: :fire: :apple: :grin: :wink: :relaxed: :mask:

```markdown
:100: :fire: :apple: :grin: :wink: :relaxed: :mask:
```

?> Mehr Emojis sind unter <https://gist.github.com/rxaviers/7360908> verfügbar.

### Tabellen

Tabellen werden ebenfalls in `Markdown` erstellt.

| Begriff           | Erklärung                                                          |
| :---------------: | -------------------------------------------------------------------|
| Interface         | Hierbei handelt es sich um eine **Schnittstelle**.                 |
| OOP               | Hierbei handelt es sich um die _Objektorientierte Programmierung_. |
| Klasse            | Hierbei handelt es sich um einen Bauplan.                          |

***

```markdown
| Begriff           | Erklärung                                                          |
| :---------------: | -------------------------------------------------------------------|
| Interface         | Hierbei handelt es sich um eine **Schnittstelle**.                 |
| OOP               | Hierbei handelt es sich um die _Objektorientierte Programmierung_. |
| Klasse            | Hierbei handelt es sich um einen Bauplan.                          |
```

### Aufgaben

Aufgeben werden folgendermaßen erstellt:

- [x] eine Erledigte Aufgabe
- [ ] noch nicht erledigte Aufgabe
- [ ] weitere noch nicht erledigte Aufgabe