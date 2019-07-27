# Windows Capslock Key Japanese Input Toggle
Toggle Japanese input (hiragana/alphanumeric toggle) with the CapsLock key on non-Japanese keyboards. It's like having your very own `Eisu` (<ruby>英数<rt>えいすう</rt></ruby>) key!

## Installation
Run `Map Caps Lock to F15.reg` file to remap CapsLock to F15 and restart your computer.

### Google IME
Import the `Google IME Keymap (MS-IME F15 Mod).txt` keymap. This uses the default MS-IME shortcuts but has an additional four shortcuts added for F15.

### Caveats
`Shift + CapsLock` will not toggle CapsLock mode so you will loose the ability to lock your caps.

## Background
I have a non-Japanese keyboard and have known for a while now that many Japanese keyboards allow you to toggle between Japanese and English input via the Caps Lock key. I jump in and out of these two input methods so frequently that I decided I'd like to do the same. So I set about using the built in MS-IME and tried to bind to Caps Lock but with no luck. Next, I tried using Google IME but again it didn't appear to be an option. So I wondered, how on earth do Japanese people toggle input methods with the Caps Lock key anyway?

On many Japanese keyboards on the `Caps Lock` key is written `Caps Lock 英数`. Initially I thought this difference was merely aesthetic, just a bit of extra print on Japanese keyboards to describe the secondary function of their <code>Caps Lock</code> key. However further investigation showed it's not a <code>Caps Lock</code> key at all as it sends a different scan code. 

This key is actually known as the `Eisu` (<ruby>英数<rt>えいすう</rt></ruby>) key and it isn't always where the `Caps Lock` key is. The `Eisu` key is either found on the left of the `A` key or on the left of the `Space` bar but commonly the `Eisu` key on PC keyboard is also functions as a `Caps Lock` key. On Windows, the `Eisu` key causes changing IME input mode to ASCII capable mode in most IMEs. Additionally, `Shift + Eisu` provides the caps lock function.

Initial experiments to give my non-Japanese an `Eisu` were unsucessful. I think it is possible to remap `Caps Lock` to `Eisu` but making use of it would probably require I set my keyboard layout to Japanese which would just be confusing so instead I decided to remap `Caps Lock` to another key, preferably one that I don't use. I decided on `F15` because my keyboard lacks an `F15` key and I'm not even sure how I'd go about emulating an `F15` keypress on my keyboard. Besides I've not once needed `F15` before so `F15` it is!
