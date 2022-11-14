# Project Description

Hunt the nut! is a small silverlight based game in the style of the classic snake known from the first nokia mobiles. 

# Port to WPF

After deprecation of Silverlight, I ported the game to WPF. 

## Limitiations/Changes in the WPF port

- Adjusted the level files to ne refresh rate
- the CocaCola was originally intented to speed up the squirrels for a few seconds. But this doesn't work anymore, as the timer for the refresh does not really behave the same as in silverlight. So the coca cola is now adding one or two squirrels to the tails, but without counting as a nut!

### OpenSilver

Though OpenSilver claims to be a 99% compatible port for silverlight, it basically translate the silver xaml elements into html. As this game is only using a "Canvas" element on which the graphics are drawn on (using double buffering), the game can't be ported to OpenSilver

