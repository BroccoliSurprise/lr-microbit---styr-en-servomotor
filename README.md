#  Lær micro:bit - Servomotor

## Steg 1 

&nbsp;
&nbsp;

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
## Steg 2

&nbsp;
&nbsp;

Tallene du sender til servomotoren må være mellom 0 og 180. Ser du hva tallene betyr?

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

