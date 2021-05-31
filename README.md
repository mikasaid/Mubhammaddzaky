adb shell input touchscreen swipe 530 1420 530 1120
adb shell input touchscreen swipe 530 1120 830 1120
which is

adb shell input touchscreen swipe x1,y1, x2,y2
but they are two discontinuous swipes.. Its equivalent to doing the first swipe, take ur hand off the screen and do the second swipe and so on..

I would like to achieve this as a single swipe.. Like, imagine a game where theres hot fire underneath and you have to drag om-nom across various obstacles without taking your finger off om-nom.. with the above mentioned adb swipe, poor om-nom would fall into the fire and become roasted-om-nom. :(

something like

adb shell input touchscreen swipe [(x1,y1, x2,y2), (x3,y3, x4,y4)...(xn-1,yn-1, xn,yn)]
if not adb, any other alternative?

android
adb
swipe
swipe-gesture
