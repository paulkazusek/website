---
layout: post
title:  Visual Studio Code installieren unter Ubuntu
date:   2019-09-09
categories: software
tags: vscode ubuntu
excerpt_separator: <!--more-->
---

Visual Studio Code (VS Code) basiert auf dem Framework Electron ist ein plattformübergreifender Open Source Quellcode Editor von Microsoft. Es verfügt über eine integrierte Debbugung-Unterstützung, Versionsverwaltung mit Git, Syntax Highlighting, Code Vervollständigung und ein integriertes Terminal.

<!--more-->
VS Code kann mit einer vielzahl von Programmiersprachen verwedent werden, weil es ein sprachunabhängiger Quellcode Editor ist. Unterschied zum Visual Studio oder anderen Entwicklungsumgebungen ist. In VC Code werden keine Solutions (*.sln) oder Projekte geöffnet und es wird nicht in den projektspezifischen Dateien gearbeitet. Sondern es werden Verzeichnisse geöffnett und von dort aus werden die Dateien bearbeitet.

VS Code kann über Plugins (Zusatzmodule) aus einem zentralen Repository erweitert werden. Das ist der beeindruckenste Teil, die Anpassbarkeit über Erweiterungen. Wir können unser Werkezug an das aktuelle Projekt so anpassen, wie wir es benötigen. Das können Unterstützungen für eine neue Sprachen sein, oder Syntax Highlighting, Code Linter, Debugger, Code Snippets und viel mehr. Wenn wir die Pluings nicht mehr benötigen, dann können sie deaktiviert oder sogar deinstalliert werden.


### Installation auf Ubuntu 18.04

VS Code kann nicht direkt aus den offiziellen Paketquellen installiert werden. Es gibt mehrere Möglichkeiten zur Installation. Die einfachste Möglichkeit VS Code auf Ubuntu zu installieren ist über die [Projektseite][vscode] oder die [Downloadseite][vscode-download] im Browser zu öffnen. Hier das .deb Paket herunterzuladen (in meinem Fall in den Download Ordner). Und anschließend mit apt (Advanced Packaging Tool) auf der Kommandozeile installieren.

{% highlight bash %}
sudo apt install ~/Downloads/code_1.38.1-1568209190_amd64.deb
{% endhighlight %}


[vscode]: https://code.visualstudio.com
[vscode-download]: https://code.visualstudio.com/Download
[vscode-github]: https://github.com/microsoft/vscode
