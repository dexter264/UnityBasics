# How to use Unity



## Chapter 1


### Introduction


If you are looking to create a game, but you can’t find a game engine, much less an easy to use one, or even a free option, consider Unity. Unity is an extremely powerful game engine that is used by game developers all over the world. Many people love it for its simplistic design and easy to use format. Yet, some people associate simplicity with incapability, and believe that it cannot be used to make anything to powerful, because nothing that simple can be that powerful, right? 
Wrong. Unity is, hence the introductory statement, quite powerful. Some of the world’s most popular and successful games have been made on it, and now that it has been around for so long, it has gotten to be so popular that tutorials and assets are overflowing to help you get started building the best game you can make.
Yet, Unity still has more to offer! As Unity progresses and gets more and more updates, so will its animation tools. With a cutting-edge animation platform, you can even make animated movies on Unity! Personally, the game route is what interests me, so I use the tools to make cutscenes for all my games.
Now another thing Unity has to offer is game modes. You can build games in three different modes, 2D, 3D, URP, or HDRP, and we will get into those later. Now what is cool about this is that you can build in different graphics levels. 2D of course being the most basic, then 3D, which is a little more complicated, URP and HDRP are the two Render Pipelines that let you achieve top of the line graphics in your games.
Probuilder, some people hate it, I personally love it. It’s a package made by Unity themselves that allows you to model and build, within the Unity editor! Some people say that it is over simplified, others that it isn’t even usable, however if you are making games, it is so very much quicker to hop into Unity and realize that you don’t have a chimney for a cottage, then whip out Probuilder and model it next to the cottage to see how tall and wide to make it, than hop into Blender with no idea how big to make it and then stretch the texture making it fit. None of that is a problem in Probuilder.
Moving on, now another useful tool is the terrain editor, it allows for rapid terrain modeling with tons of preset brushes and such. Also, its texture adding tools are quite amazing, it can slap just about any texture you want on there, and with full control of where to place it and everything, to make realistic mountains and rocks.
So, in the end the decisions up to you about what game engine to choose, and not going to change your decision that much, but the facts will. Unity is an amazing game engine and there is no doubt about it. Even if you still think you want another, maybe you will think about this and choose Unity. 








## Chapter 2


### The basic 2D engine


As mentioned previously, Unity has the four game modes. The basic 2D, basic 3D, URP, and HDRP. The first of these is the 2D and the one this chapter is all about.
The 2D side of Unity is perfect for side scrolling platformers, top-down RPGs, dungeon crawlers, roguelikes, or even older styles such as F Zero, Mortal Kombat, or even Star Fox.
Now, the 2D is compatible with the URP for realistic lighting, but we will not get into that. But as it is, the 2D is powerful, now. After the 2018 version of Unity, the 2D tools have improved drastically. It has also made 2D physics quite fuller and more capable.
With the aid of the Rigidbody2D, the 2D physics handler, you can create quite a few effectors to make your games vivid and fun.
To prepare to create an effector, create an empty Game Object, or use a sprite, give it any collider of your choosing, use a 2D polygon collider with sprites that have more complicated shapes, 2D circle collider for sprites with more round shapes, and 2D box collider for square shapes. I cannot stress this enough, make sure to get a 2D collider for 2D shapes! Anyway, set your collider to is trigger, check use by effector, and grab the effector of your choosing.
2D Area Effector: Mostly to be used with empty game objects, it can add forces to any Rigidbody2Ds that come within its trigger. There are 2 sections to change settings in: Force and Damping.
Under Force, you can change, if it should use a global angle, which means push direction is not effected by the objects rotation, the force angle, direction in which to push, force magnitude, how hard to push, force variation, if it should wobble the force that it pushes with, force target, what to push. Under Damping, you can change, what drag to apply to the Rigidbody, and if it should apply an angular drag, and really that’s about it for the Area Effector.
2D Surface Effector: Can make things like conveyor belts and such. To set it up, repeat the previous steps only do not check Is Trigger on the collider. Again, there are 2 sections to change settings in: Force and Options.
Under Force, you can change speed, which is speed, speed variation, once again, wobbles the speed, and force scale, which is how hard to push. Under Options, you can change use contact force, if it should use the objects initial momentum, use friction, if it should use friction, and use bounce, if it should use bounce, and that wraps up the Surface Effector.
2D Point Effector is used for things like magnets. To set it up, follow the directions from the Area Effector. Once more, 2 sections to change settings from: Force and Damping.
Under Force: magnitude, speed, variation, wobble, scale, distance to reach, source, what to pull with, target, what to pull, mode, how to pull. Under Damping: drag, resistance to pull, angular drag, resistance to rotation. That sums up the Point Effector.
2D Buoyancy Effector: used for water. To set it up follow the directions from the Area Effector. It has 2 sections to change settings in, Damping and Flow, and some normal settings.
Normal settings: use collider mask, if it should use layers to know what to effect. Collider Mask, what layer(s) to effect. Density, how much the object floats. Surface level target floating height. Damping: Linear drag, resistance. Angular drag, rotation resistance. Flow: Angle, direction to flow. Magnitude, force to flow. Variation, wobble.
2D Platform Effector: used for one-way collisions on platforms. To set it up follow the directions from the 2D Surface Effector. It has 2 sections to change settings in, One Way and Sides, and some normal settings.
Normal settings: use collider mask, if it should use layers to know what to effect. Collider Mask, what layer(s) to effect. Rotational offset, offset from the object’s rotation. One Way: Use one way, if it should use a one-way collision system. Surface arc, angle of collision. Sides: Use side friction, apply friction to sides of platform. Use side bounce, apply bouncing to the sides of the platform. Side arc, angle of collision for the sides. With that we will wrap up the 2D Platform Effector.
Now that you know the basics for 2D physics, the rest is up to you. Play around with these settings, modify things, and just have fun building awesome physics in your 2D games. The next step is 2D joints, but since this book is geared for beginners, we won’t get into all, of that now. 
That pretty much sums up the 2D part of this book. Personally, 3D is my favorite mode to create games in, but 2D can also be fun and challenging. Now once again, most people think that 2D games generally aren’t as good as 3D ones, but I don’t think so. Generally, 3D games aren’t quite as solid as 2D ones because when they add another dimension people don’t think that they need to make as good of a game. So, in the end, most 2D games are very solid fun and an interesting experience to play.



