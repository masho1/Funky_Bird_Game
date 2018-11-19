# Funky_Bird_Game
A game done according to Flappy Bird game tutorial. It is played by clicking on the mouse button and avoiding the pipes.

Link to the tutorial: https://www.youtube.com/watch?v=A-GkNM8M5p8&list=WL&index=27&t=7835s

Why this tutorial: As we have been working on 3D game at the university, I thought I would give 2D game a try and learn different aspects. As well as that, I mostly work on 2D and this kind of game would be closest to what I can do by myself soon.

Difficulties/bugs and fixes:
1. When the bird was touching the ground nothing was happening. I discovered it quite late and had to go back to the beginning of the tutorial. 
* Fix - I had a Box Collider component instead of Box Collider2D component. As soon as I fixed it, it started working.
2. Countdown and Play didn't work
* Fix - the layers were messed up and they had to be adjusted.
3. Pipes, stars and clouds were not moving towards the bird
* Fix - the ratios in my game were much different than in the tutorial. I changed some positive values(for moving) into negative and made the speed higher. Also, I had to delete and recreate Parent components and Prefabs couple of times until they made sense.
4. Pipes, stars and clouds were not scaling well.
* Fix - had to modify prefabs, create new GameObjecs and apply afterwards.
5. Unity was crushing every time I would push play
* Fix - there was a problem with the code loop, which was causing the crushes.
6. After pushing "replay" button, game objects were not resetting on their places
* Fix - partially I fixed it, but it still has a bug that I cannot figure out.

What did I learn:
1. A game with 3 hour tutorial takes two days to complete:)
2. Learned how to work with Prefabs, Parent Objects, what kind of graphic materials to use for such game, how to modify some settings that the game doesn't crush

What have I added to the game:
- My own graphics:)


