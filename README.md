# hack-a-thing-1-theboyz
### Oliver McTammany and Matthew Kersey

# Week One

## Tanks Game in Unity
### Summary
For Hack a Thing 1, we chose to look at programming a simple game in Unity. Neither of us had done any work with Unity or C\# prior to this experience, and decided to follow a couple of tutorials in order to get acquainted. tanks.unitypackage is the result of following the tutorial for a tank game provided on the Unity website. It is a 2 player game in which users battle eachother in tanks. In addition, we decided to create a modded version, 3rdPerson.unitypackage. This version turns the game into a third person shooter type of game, adding more options for motion as well as greater control over the camera. In the map, there are a number of dummy tanks which act as targets for players.

### Division of Labor
We each followed the tutorial individually in order to gain experience. Oliver worked on the original game from the tutorial, while Matthew worked on the modded version.

### What We Learned
We both got some experience working in Unity as well as coding in C\#. 

### What Didn't Work
3rd Person is not quite as polished, there are certain things that we weren't able to accomplish (such as a game manager, audio mixing, and limiting the motion of the camera). Other than that, nothing.

# Week Two

## Miscellaneous Tests with Unity & AR
### Summary
For Hack a Thing 2, we decided to continue working with Unity, specifically looking at different ways of integrating AR & controller support. We used several tutorials to build a floating cube and a bouncing ball for Hololens (https://www.youtube.com/watch?v=FmYp5dqqYAQ). We ended up spending a lot of time attempting to get programs onto the Hololens from our laptops, but in the end, we are excited about what we were able to do. In addition, we looked at ARCore and putting an AR application on an Android phone. Wanting to make a similar demo to what we made for Hololens, we modified an example provided with the ARCore kit (Called "HelloAR") and followed some of the directions from the previously mentioned tutorial. In addition, we leveraged ARCoreUtils (https://github.com/jonas-johansson/ARCoreUtils) to make the planes found by ARCore into colliders, which proved to be nontrivial.

We also looked at adding Xbox One controller support to the 3rd person game we made last week (Driver: https://github.com/360Controller/360Controller).

### Division of Labor
Oliver did the majority of the work on the Hololens (Matthew trouble shot a bit), and Matthew worked on the ARCore app and controller support.

### What We Learned
We continued to develop comfort with Unity as well as the different things that you can do with it.

### What Didn't Work
Getting Unity code onto the Hololens was difficult, but worked in the end. The ARCore app pales in comparison to the Hololens app due to its inability to identify and track planes at a sufficiently high speed. 