# how-to-wget
über Terminal wget.exe verwenden  

## Webseite als HTML-Seite downloaden  
komplett, inkl. Skripte, Dateien und aller Unterseiten  

1.) Lade dir wget.exe herunter. Zum Beispiel von dieser Quelle: https://eternallybored.org/misc/wget/  
2.) Speichere sie in einen Ordner. Zum Beispiel `C:\tools\wget\`  
3.) Öffne die **Eingabeaufforderung (CMD)** oder **Powershell**  
4.) Wechsle in den Ordner wo du deine wget.exe gespeichert hast  

Eingabe im Terminal/Powershell:  
`.\wget.exe --mirror --convert-links --adjust-extension --page-requisites --no-parent https://deine-seite.tld`  

Als Ergebnis bekommst du einen Ordner (Ordnername = Domain) mit allen notwendigen Ordner und Dateien, die zum Öffnen der Seite notwendig sind.
