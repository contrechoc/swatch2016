# swatch2016
Script of E-textile Swatch2015

two scripts

1: with conductive patches

uses: ATtiny85, neopixel
3 conductive textile patches

http://etextile-summercamp.org/swatch-exchange/epaulette/

/*

script for the e-textile swatchbook swatch 
title Epaulette
author Beam
2016
feel free to do whatever your want with the script

on three analog pins of the ATTINY are textile resistive yarn patches
the  minimum and maximum values are calibrated automatically during the first seconds
during the calibration you have to press the patches
then the values are mapped to the RGB Neopixel

example of mapping 3D data to a RGB LED - datavisualisation

http://etextile-summercamp.org/swatch-exchange/epaulette/

*/

2: using random values to generate color patterns

using analogRead from pins PB1 and PB2 to get "more" random values, even acting as some sort of capacitive influence
