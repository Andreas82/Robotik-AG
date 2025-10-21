# Robotik-AG
## Erste Stunde 06.11.25
### Planung
Es gibt eine ganze Reihe von Editoren, die wir für Calliope benutzen können.

Das Würfelbespiel funktioniert und nutzt den Beschleunigungssensor und das Display.

### Code-Beispiele
let T = 0
basic.forever(function () {
    T = input.temperature()
    basic.showNumber(T)
})
Liest den Temperatursensor und gibt die Temperatur auf dem Display aus


