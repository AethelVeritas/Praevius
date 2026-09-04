---
title: "Praevius"
author: "AethelVeritas"
description: "Low profile split wireless keyboard, with a touchpad." 
created_at: "2026-08-28"
---

# September 5: Initial Constraints

This keyboard needs to:
- be low-profle 
- use an onboard nrf52840 chip
- be wireless
- use the TPS65 touchpad

   In regards to the layout, I want something more "conservative" than Quaero. The layout of Fulmen was basically almost perfect for me, except the index columns and rather low thumb row. So something with little to none splay, as it needs to be comfortable for my father as well. And maybe a detachable number row, same as I did with Quaero, but with more mousebites so that the PCB actually still looks decent with the number row removed. So I guess something similar to the ZSA Voyager but with more thumb keys. Might have to make one or two thumb keys detachable as well, as I personally prefer three while my father wants more. Also Chocs (either v2 or v1) will probably the best option. ULPs look interesting, but I think I'd be sacrificing switch feel for height. Plus they're more expensive.  
   The aforementioned chip unfortunately only comes in an aQFN package, so the only options would be PCBA or using a hot air station. Been thinking that I could try and get only the chip PCBA-ed, and then hand-solder the rest. That would require the rest of the components to have big enough packages, and for having only a chip PCBA-ed significantly cheaper than the whole board, which I highly doubt will be the case. Another option would using a hot air station to solder the chip and then hand-solder the rest. Should be doable with big enough packages + a fine enough pinecil tip, but we'll see. The reason I'm using an onboard chip instead of something like the Seeed Studio Xiao NRF52840 is because it does not have enough pins (only 11), and it's also a bit bulky. After much time spent browsing the r/ergomechkeyboards subreddit and seeing all the wonderfully low-profile builds there I also want to make something similar. 

Random idea: if I do end up having a significant battery bulge, or if I ever use dev board again as the MCU, I could thermoform the "bump" that cover the dev board. That way, I don't have to struggle with designing a a cover for the latter that's not too bulky or ugly, like what happened with Quaero or Fulmen (my last two keyboards).

After about an hour or two of slight adjustments and consulting with my father, this is what I came up with. It's obviously a rough draft, as I think I could adjust it even more, especially the thumb cluster. 
![ergogen](Pics/pic1.png)

**Total  time spent: 3 hours**
