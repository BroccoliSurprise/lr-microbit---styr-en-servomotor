#  Lær micro:bit - Servomotor

## Steg 1 

På Pin 9 (Den oransje ledningen) er det koblet til en servomotor. 
Last ned dette programmet og se hva som skjer med LEGOfiguren.

```template
for (let index = 0; index < 4; index++) {
    pins.servoWritePin(AnalogPin.P9, 0)
    basic.pause(500)
    pins.servoWritePin(AnalogPin.P9, 180)
    basic.pause(500)
}
```


```ghost
basic.showNumber(0-0)
basic.showIcon(IconNames.Heart)
basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    `)
basic.showString("Hello!")
basic.pause(randint(0, 10))
for (let indeks = 0; indeks <= 4; indeks++) {
	
}
```


> Åpne denne siden på [https://broccolisurprise.github.io/lr-microbit---styr-en-servomotor/](https://broccolisurprise.github.io/lr-microbit---styr-en-servomotor/)

## Bruk som utvidelse

Dette kodeområdet kan bli lagt til som en **utvidelse** i MakeCode.

* åpne [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klikk på **Nytt prosjekt**
* klikk på **Utvidelser** i menyen under tannhjulet
* søk etter **https://github.com/broccolisurprise/lr-microbit---styr-en-servomotor** og importér

## Rediger dette prosjektet ![Build status badge](https://github.com/broccolisurprise/lr-microbit---styr-en-servomotor/workflows/MakeCode/badge.svg)

For å redigere dette kodeområdet i MakeCode.

* åpne [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klikk på **Importer** og så på **Importér URL**
* lim inn **https://github.com/broccolisurprise/lr-microbit---styr-en-servomotor** og klikk på importér

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/broccolisurprise/lr-microbit---styr-en-servomotor/raw/master/.github/makecode/blocks.png)

#### Metadata (brukes for søk, visualisering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
