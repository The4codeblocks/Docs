---
title: MeshPart
description: A part that can have custom mesh applied to it.

icon: polytoria/MeshPart
weight: 2
---

# MeshPart

:polytoria-MeshPart: MeshPart is a part that can have custom mesh applied to it, the mesh may be from the Polytoria Store (Hats, Tools and Heads) or user-uploaded meshes.

{{ inherits("Part") }}

## Methods

### PlayAnimation(animationName;string,objectPath;string=nil,speed;float=1,loop;bool=false) { method }

Plays the animation with the specified name, if it exists.

### StopAnimation(name;string=nil) { method }

Stops playing the current animation.

### GetAnimations() { method }

Returns the names of the animations associated with the mesh.

### GetAnimationSources:string[] { method }

### GetAnimationInfo:AnimationInfo[] { method }

## Properties

### AssetID:int { property }

The asset ID of the mesh part.

### CurrentAnimation:string { property }

The current animation of the mesh part.

### IsAnimationPlaying:bool { property }

Returns whether or not the animation is playing.

### PlayAnimationOnStart:bool { property }

Specifies whether or not to play the animation on start.

### CollisionType:CollisionType { property }

Specifies the collision type of the part.
