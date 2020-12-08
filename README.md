# A Simple Megascan Material Shader for Unreal Engine

This is a simple material shader written for use with Megascan assets in Unreal Engine. It is written in Blueprint for use in Unreal Engine 4.24, but should be scalable for use in versions 4.25 and later (if not immediately usable).

## What is a Megascan?

A megascan is a high-resolution scan of a real world object. Megascans can be used to create remarkably photorealistic scenes in Unreal Engine.

## What does this shader do?

This shader allows one to change the materials properties of the megascan. While this shader allows one to change ambient occlusion, specular reflectance, roughness, and cavity properties of the megascan material, it can be extended to provide support for more properties!

## How does it work?

The heart of the shader itself is the UE4 blueprint that provides both the underlying shader math and the user interface (UI) code that allows users to easily change material properties in the Editor. As the values are changed in the editor, they are used as inputs to update the shader. The shader then applies the updated values to the material instance, resulting in an updated look in real time.

```
![Shader in Action](documentation/images/megascan_shader.gif)
```

## Warning!

To comply with the terms of the [Unreal Engine EULA](https://www.unrealengine.com/en-US/eula/publishing), this project can be used in UE4/Twinmotion **ONLY**.

## Credits

Special thanks for Michael Gerard for his udemy course on megascan shaders. Please check out his LinkedIn page [here](https://www.linkedin.com/in/michael-gerard-56537113a/).

And, as well, the good people at [Quixel](https://www.quixel.com/) and [Unreal Engine](https://www.unrealengine.com/) for making this all possible. ;)
