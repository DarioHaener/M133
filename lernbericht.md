# Lern-Bericht
Haener Dario

## Einleitung

Im Modul 133 haben wir gelernt wie man mit xhtml und JSF Sowie mit verschiedenen Sessions umzugehen.

## Was habe ich gelernt?

Einen String in einer Bean abzuspeichern um diesen an einem späteren Zeitpunkt wiederzugeben.

## Beschreibung

Wie man mit Beans Strings speichert, damit man diese später wieder ausgeben kann. Wobei ich eine `SessionScoped` Bean verwendet habe.
In meinem Fall heisst diese Bean `sessionHandler`.

Eingabe Nachname
```Java
<!-- Input Surname -->
Geben sie ihr nachnamen ein
<!-- Saves input surname in bean -->
<h:inputText value="#{sessionHandler.nachname}" id="nachname"/>
<!-- Takes user to next page -->
<h:commandLink value="Nächste Seite" action="index_2.xhtml"/>
```

Ausgabe Nachname
```Java
<!-- Output Surname -->
<h:outputLabel value="#{sessionHandler.nachname}" id="nachname"/>
```

GIF vom Speichern und wiedergeben.

![beans](https://user-images.githubusercontent.com/69902881/187161603-64471643-fac7-479c-918e-e58beea569b1.gif)

## Verifikation

Der erste Code-Fetzen speichert den Nachnamen und der zwite gibt ihn später wieder aus.
Im GIF kann man sehen wie ich meinen Namen eingebe und dieser dann am schluss wiedergegeben wird.

# Reflektion zum Arbeitsprozess

👍 Ich konnte mich trotz verpasstem einstieg schnell in das Modul einarbeiten.

👎 Ich konnte an der ersten Lektion nicht Teilnehmen und musste manche Aufträge nachholen. 

**VBV**: Pausen besser einteilen
