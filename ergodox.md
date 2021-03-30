---
layout: page
title: "My Ergodox EZ Layout"
permalink: /ergodox/
---

# My Ergodox Layout

I've often found myself wanting to share and explain the keyboard layout I developed over four years of using an Ergodox EZ as a daily driver at work. 
However, because I moved from using the Configurator to writing my own keymaps in C years ago, it's pretty difficult to share the theory and utility of the layout with most people.  
So, I finally undertook to write up my latest 'map in KLE (the Keyboard Layout Editor) and to describe it here, in detail. 
This is just what has worked for me and there's no reason in particular that it should or shouldn't work for you. 
Then again, I've written proposals, Powerpoints, LaTeX, C, C++, Python, R, emails, Teams messages, reports, and spreadsheets with this layout and I think it handles all of these use cases well. 

A note: I've been running this on Mac for the past couple years, so there may be some Mac-isms at various places in the map (e.g., the desktop switcher keys). 


## The Base Layer

My base layer remains QWERTY-based, because every time I think of switching alpha layouts, I fall down the "which layout should I choose?" rabbithole until I get tired :-)
Of course, the actual organization of the alpha layer isn't the secret sauce in a QWERTY-based layout and I think most of what I've done here would work just as well with Colemak or ASETNIOP or any of the others.

[IMAGE HERE]


I've indicated a few things with colors in this layout. 
Most notably, keys that trigger any kind of layer transition are colored in a particular color corresponding to the layer the lead to.
In several cases, multiple keys can be used to get to a particular layer.
TOs take you straight to the new layer, turning off every other layer except the base (QWERT) layer. 
LTs and OSLs turn that new layer on temporarily, either while being held (LT and OSL) or for the next keystroke after it's pressed and released (OSL).
If you get into a layer via an LT, if that same key has a function in the target layer, you won't be able to use it (so, e.g., I can't hold down ; to get into EDIT and expect to be able to use the Home key).

## The NUMPAD Layer

This is the next layer in the stack, so it's the next one I'll talk about. 
It's a quite straightforward layer, overall, though I take advantage of the Ergodox's plentiful keys to get a little more bang for my layer buck than I do on, e.g., the equivalent Gergo keymap.

[IMAGE HERE]




## The EDIT Layer

Okay! This was the layer that started them all! 
I had been using a Vortex Poker 3 keyboard before the 'dox and really appreciated the little navigational cluster it puts under the right home keys.
So, when I got my new keyboard, obviously that was the first thing I replicated! 
I'd also put a few AHK scripts together for the Pok3r for things like "move one word ahead" (option-right on Mac, control-right on Windows) and found them super useful for text editing, so I added those in, too, and before long I had the concept of a whole layer dedicated to editing text.


[IMAGE HERE PLZ]



## The F and J Alternate Hands Home Row Symbols Layers

These are some of my favorite layers in the layout and I find myself reaching for them constantly, especially anytime I'm coding. 
Features like the home row punctuation, the parens/braces/brackets, and the equals, dash, underscore group massively reduce the amount of time I bring my hands out of home position.


[IMAGE HERE]



[OTHER IMAGE HERE]



## The MEDIA Layer

Here we have some controls for media and some mouse keys that I find occasionally useful for various tasks. 
This layer is reasonbly self-explanatory.

[IMAGE HERE]

It's nice to be able to bring my right hand down one row and have all of my media controls right there.


## The ADJUST Layer

This is the least exciting layer and is more for safety than anything else. 
If I want to hang out in FSYM layer for a while or I somehow get stuck in MEDIA, I've always got the option to pop over to ADJUST and bail out to the base layer.

[IMG]











