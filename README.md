## ZMK
This is the zmk config for my corne.  

I figure it would be a good place to put some TODOs for improvement.  

### TODO
5. Homerow mods prior idle time
   - Increased required-prior-idle-time for homerow mods from 200 to 400, in order to have better rolling-typing experience, but seems like it's not really working that well. for using ctrl+a ctrl+e to jump to line start/end, it's fairly annoying
   - might switch back to 200, or try 300
4. Homerow combos
   - Just remove homerow - and _ combos, already missing them.
   - [ATTN!!]Now they're in another layer, feels like my thumb is doing a lot of work right now.
  
   
3. Other Combos
   - I realize there're some keys that are kinda 'perfect' for combos, e.g., pb \ vd \ jl \ kh(only if i type khan), make them into combos?   
   - [UPDATE]Added key repeat at ,. position for experiment.
   - [UADATE]It's a weird position lol. 


2. [DONE] ~~Combo Key Ignore~~
   - Solution: ditch - and _ combos completely, remap layers.  
   - Now when typing fast, sometimes _ and - combos didn't trigger, output st and en instead. In this case, I'd delete and press "st" to trigger combo again, but becuz of the required-idle-prior thingy, another "st" will just trigger again
   - Hence, it'd probably be great to add space, backspace, delete to key ignore
   - Another problem is, for normal typing, if i wanna type "publish_stop" this kinda words, i'd have to purposely pause before hitting the combos; i think - and _ are really more commonly used than (), so might switch - _ with ()
   - Or just find a better way to trigger combos without intentional pausing. As () are heavily used in writing codes too.  

3. [DONE] ~~Homerow mod and combo~~
   - Right now I have 'rs' on homerow for both modifiers and tab combo. If both keys are pressed down (for long enough time), modifiers are the expected behavior. But now it's hitting tabs on repeat.  

----  

### Keymap
Keymap drawn by [Keymap Drawer](https://github.com/caksoylar/keymap-drawer/tree/v0.17.0)
![Corne Keymap](./keymap-drawer/corne.svg)
