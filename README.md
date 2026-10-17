# MG3
## Devlog
1. The default value for float and int is 0 or 0.0 The default value for boolean is false and the default value for string is "" (empty quotation marks or string).
2. The Update() method doesnt get called manually instead it gets called every frame when there is a script attached to a GameObject.
3. KickWeapon uses the Timer by controlling how long the kick hitbox/attack stays active after the player presses the kick button. They do this by using the Update() method, since this method is called for every frame so once the timer reaches 0, it deactivates the kick so the player doesnt kick forever.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
