# Sprite_Loader
---
A Sprite Loader for GTA:Network
---

Like the resource?

Donate a few bucks: https://www.paypal.me/stuyk

---
#### USE OF THIS CODE IS STRICTLY FOR THE GTA:NETWORK CLIENT.

#### USE OF THE CODE ELSEWHERE IS STRICTLY PROHIBITED.
---
#### How to use it:
```
let sprite: Sprite = resource.sprite_loader.newSprite(); // Create a local variable to hold our Sprite instance.
sprite.TicksPerFrame = 4; // How many ticks before we move to the next frame. (4 is default);
sprite.Width = 576; // Width of Frame or Size
sprite.Height = 576; // Height of Frame or Size
sprite.XPos = 500; // Position on Screen X
sprite.YPos = 500; // Position on Screen Y
// This is where we add all of our clientside frames. You must also add these into your meta.xml
sprite.AddFrame = "clientside/resources/images/effect/effect_00.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_01.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_02.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_03.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_04.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_05.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_06.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_07.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_08.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_09.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_10.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_11.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_12.png";
sprite.AddFrame = "clientside/resources/images/effect/effect_13.png";
sprite.LoopAmount = 1; // How many times would you like this to loop? (0 loops forever);
sprite.ready(); // Lets our sprite manager know the sprite is ready to be drawn.
```
