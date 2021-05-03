# Mario

[![Run on Repl.it](https://repl.it/badge/github/upperlinecode/mario-javascript)](https://repl.it/github/upperlinecode/mario-javascript)

## What We're Building

Mario is plumber with a family of games in which he jumps around from platform to platform killing monsters and collecting coins. If you haven't actually played a Mario game, you've probably played other platformers which are similar.

While we don't have enough time to recreate a full-fledged platformer right now, you can learn a lot from trying to implement some of the essential elements in p5. This activity is fairly self-guided, so start off with you partner deciding what elements of the game you'd like to try to recreate.

If you just made a list, it's definitely too long. You'll be able to spend quite some time just getting movement (and especially jumping) to work.

## A Possible Beginning

### Step One: Walking sideways

1. Use a big horizontal brown or green rectangle to draw the ground, and draw a much smaller vertical red rectangle to symbolize Mario.

2. Create an object called `mario` to store Mario's position and velocity. It should include `x`, `y`, `vx`, and `vy` components. Initialize this object to have Mario standing still on the ground, and change the coordinates used by `rect` to draw him dynamically at the stored position.

3. Even though you're not yet using them, increment `mario.x` and `mario.y` by `mario.vx` and `mario.vy`, respectively, each time the `draw` loop runs.

3. Create a definition for `function keyPressed()` in which we can make Mario react to user input. There are two main ways to make Mario walk: The first is to simply increase or decrease his `x` position when a key is pressed, and the second is to instead alter his `vx` property to send him moving in a certain direction. If you choose the latter, you'll need to introduce friction (that is, bring `mario.vx` a little closer to `0` each frame) to avoid him sliding too far.

### Step Two: Jumping Mario

1. Add a conditional to `keyPressed` which sets `mario.vy` to something negative when the up arrow (or spacebar if you prefer) is pressed. You should see him float off the top of the screen.

2. Now introduce gravity. That is, increase `mario.vy` by a small amount each frame, so long as he is not touching the ground.

3. You may also want to stop Mario from jumping when he is not touching the ground. A simple conditional that checks `mario.y` will likely do.

### Continuations

If you have movement working to your satisfaction (and you may very well not get to this point), there are lots of possible next steps. Perhaps you want to add platforms above the ground. Perhaps you want to add a waddling enemy.

Just make sure to agree with your partner on what comes next, and make sure you have a clear plan in your heads before you start to write more code.
