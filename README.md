# Mario

[![Run on Repl.it](https://repl.it/badge/github/upperlinecode/mario-javascript)](https://repl.it/github/upperlinecode/mario-javascript)

## What We're Building

Mario is plumber with a family of games in which he jumps around from platform to platform killing monsters and collecting coins. If you haven't actually played a Mario game, you've probably played other platformers which are similar.

While any real Mario game is far too complex for you to recreate right now, you can learn a lot from trying to implement some of the essential elements in p5. This activity is extremely self-guided, so start off with you partner deciding what elements of the game you'd like to try to recreate.

If you just made a list, it's definitely too long. You'll be able to spend quite some time just getting movement (and especially jumping) to work.

## A Possible Beginning

To keep things simple, you should start off with a continuous ground (no actual platforms that is). Create a character with a position and a velocity. Now think about how the player should interact with these values.

For example, you may decide it's alright for the left and right arrows to alter position directly, but that the space bar should just change the character's velocity. Or perhaps the left and right keys should also only touch velocity, and some kind of simulated friction can slow the character down.

At some point you'll have to implement gravity. This can be as simple as decrasing y-velocity each frame, so long as the character is on the ground. How can you stop the player from jumping again mid-air?

If you have movement working to your satisfaction (and you may very well not get to this point), there are lots of possible next steps. Perhaps you want to add platforms above the ground. Perhaps you want to add a waddling enemy.

Just make sure to agree with your partner on what comes next, and make sure you have a clear plan in your heads before you start to write more code.
