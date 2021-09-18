
# Arrays - die Supervariablen
Diese Art von Variablen ist wohl die wichtigste in den verschiedenen Programmiersprachen:
Sie stellt eine Liste dar, in der sehr viele Werte gespeichert werden können.

* Ein Beispiel mit Namen:

```blocks
input.onButtonPressed(Button.A, function () {
    anzahl_elemente = namens_liste.length
    for (let index = 0; index <= anzahl_elemente - 1; index++) {
        name = namens_liste[index]
        alter = alters_liste[index]
        basic.showString("" + name + " ist " + alter + "Jahre alt")
        basic.pause(5000)
    }
})
let alter = ""
let name = ""
let anzahl_elemente = 0
let alters_liste: string[] = []
let namens_liste: string[] = []
namens_liste = ["Maria", "Georg", "Sophie"]
alters_liste = ["12", "11", "12"]
``` 

* Ob man jetzt 3 Namen hat oder 500, der Programmcode ändernt sich nicht - außer bei der Befüllung der Variablen!
* Wenn du dieses kleine Programm nacharbeiten und auch verändern kannst, hat du einen Riesenschritt im Programmieren gemacht.
* Hier zum Öffnen in Makecode: [Beispiel](https://makecode.microbit.org/#pub:_THmW3ohWpDb4)

## Arrays im Projekt "Morse 1" angewendet: [Beispiel](https://makecode.microbit.org/#pub:_CbADhU1MC5R7)

### Dieses Bild zeigt den Programmcode in einer Grafik an.

![Eine gerenderte Ansicht der Blöcke](https://github.com/dlpl-mb/morse_01_bst_senden/raw/master/.github/makecode/blocks.png)

<hr>
<style>.page-header {font-size:1rem;height:0vh;padding-top:1.5rem}</style> <script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
