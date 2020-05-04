# Leds


## Toggle Leds
Toogle bloğunu alınız.
```blocks



basic.forever(function () {
    led.toggle(0,0)
})
```


## Random x
Pick Random kod bloğunu 'x' yerine yerleştirelim ve 0 ile 4 arası bir değer tanımlayalım
```blocks 
basic.forever(function () {
    led.toggle(Math.randomRange(0, 4),0)
})
```
## Random y
Pick Random kod bloğunu 'y' yerine yerleştirelim ve 0 ile 4 arası bir değer tanımlayalım

```blocks 
basic.forever(function () {
    led.toggle(Math.randomRange(0, 4), Math.randomRange(0, 4))
})
```