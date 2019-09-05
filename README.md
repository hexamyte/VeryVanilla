# VeryVanilla
A very vanilla-esque loot filter for Path of Diablo cobbled together by stea--borrowing ideas from other filters and adjusting them to my liking.

Main Goal: Take many useless items off the screen and add some differentiating features to certain items without turning the screen into rainbow unicorn barf.

How to install the filter - follow the excellent instructions by KarmaNation256 here:

https://github.com/KarmaNation256/pod-loot-filter/wiki/Installing-Loot-Filter

But use this link the the VeryVanilla filter:

https://raw.githubusercontent.com/hexamyte/VeryVanilla/master/item.filter

Also see KarmaNation256's instructions on how to enable mouse wheel hotkeys:

https://github.com/KarmaNation256/pod-loot-filter/wiki/Adding-Mouse-Wheel-as-a-Hotkey

** This is both a readme and notes to myself


Basic summary of filter functions:
  - Hide small piles of gold, where "small" is based on character level (not working, but why?)
  - Hide obsolete health/mana potions based on character level
  - Hide all throwable potions and white bolts/arrows after level 9, plus hide all stamina potions period
  - Show value of white items that can carry inherent skill bonuses (wands, staves, etc) to highlight items with skills
  - Show rune names in tan rather than white
  - Hide (most) cracked/broken etc items. Rule showing value for skill items takes precedent, rework both of these.
  - Items with sockets have [#] appended to the name, where # = number of sockets
  - Normal-quality etherial items without sockets are hidden, those with sockets also have [Eth] appended to the name
  - Items used for runewords have (Runeword) appended to the name, in tan. Untested, not sure how it works. 

Ideas "in process" (in no particular order):
  - Finish the basic summary of filter functions
  - Replace the readme with a wiki (learn how to use GitHub properly...)
  - Highlight POD-specific items
  - Fix the gold filters
  - Adjust inferior and "skill-item" (wand, barb helm, etc) filters to hide more skill-items. Item value gates?
  - Hide more normal, no-socket items based on level
  - Make sure to show etherial items that would be worth socketing with Larzuk
  - Figure out how the RW (runeword) item tag works. Is it items useful for runewords, or items containing runewords?
