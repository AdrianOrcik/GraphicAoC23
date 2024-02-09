# GraphicAoC23

## Table of Contents

1. [Gradient Sky](#gradient-sky)
2. [Water Ripple Effect](#water-ripple-effect)
3. [Basic Light Shader](#basic-light-shader)
4. [Outline Shader](#outline-shader)
5. [Pulse Effect](#pulse-effect)
6. [Frosted Glass](#frosted-glass)
7. [Rainbow Shader](#rainbow-shader)
8. [Simple Wave](#simple-wave)
9. [Texture Blending](#texture-blending)
10. [Bump Mapping](#bump-mapping)
11. [Cel Shading](#cel-shading)
12. [Sunset Horizon](#sunset-horizon)
13. [Star Twinkling](#star-twinkling)
14. [Heat Haze Effect](#heat-haze-effect)
15. [Vignette Effect](#vignette-effect)
16. [Motion Blur](#motion-blur)
17. [Stencil-Based Object Highlighting](#stencil-based-object-highlighting)
18. [Depth Offset for Decals](#depth-offset-for-decals)
19. [Advanced Stencil Techniques for Portals](#advanced-stencil-techniques-for-portals)
20. [ZTest and ZWrite for X-Ray Vision](#ztest-and-zwrite-for-x-ray-vision)
21. [Stencil Buffer for Dynamic Shadows](#stencil-buffer-for-dynamic-shadows)
22. [ZClip for Clipping Effects](#zclip-for-clipping-effects)
23. [Depth-Based Effects for Water Surface](#depth-based-effects-for-water-surface)
24. [Offset and Stencil for Smooth Curve Visualization](#offset-and-stencil-for-smooth-curve-visualization)

## Gradient Sky

Simulates 2D day-night cycle with smooth transitions between day and night skies textures. 

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/674ceefe-7768-45df-ace3-743dfb8e988f

## Water Ripple Effect

Simulates ripples on a 2D water surface.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/4dbc008f-6377-4c95-bf18-e1a946f1f472

## Basic Light Shader

//TODO: Add advanced lighting

Simple 2D lighting effects, including ambient, directional and point light on a 2D sprite.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/9a93a36d-7750-4a7f-9c57-abbf86eb8e4f

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/6b7edcbc-d6ac-45a4-88b1-fbf9445896ae

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/2e7611ab-6d14-44f7-88d8-7cdd3d3d31a3

## Outline Shader

Shader generates vertex-based outlines around 2D sprites.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/9341e809-17c3-4b3a-ba98-73a5c1a88e2b

## Pulse Effect

Shader creates a visual pulse in size and outline effect on objects.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/a8ed2193-ddcf-4dbd-87f2-a82485bfa98a

## Frosted Glass

Simulates the appearance of frosted water on 2D surfaces.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/d87fc210-4715-4e06-bde5-92ab2b055164

## Rainbow Shader

This shader smoothly transitions through rainbow colors on a 2D surface.

<img width="326" alt="D7-2D-RainbowTexture" src="https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/201f021e-8998-4e9a-9284-2ce7a791bdce">

## Simple Wave

Shader creates a waving motion effect, suitable for simulating flags or foliage in 2D.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/9d2c27b1-3c96-4574-961f-c7c9d5cafef8

## Texture Blending

Shader blends multiple textures on a surface with adjustable blending factors based on RGB texture.

<img width="363" alt="D9-2D-MultipleTexturesBlendBasedOnRGBTexture" src="https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/be2adfd6-97a0-4c28-b5d4-322e9831c8f5">

## Bump Mapping

Shader implements a bump mapping effect to create perceived surface details on 3D objects.
Ambient + Diffuse vs Added specular light vs Added detail normal map

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/bc0e1c4d-1513-4da3-9ddd-92333b0e66ac

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/f69b9019-4b36-4485-90b1-4ce5efcfb824

## Cel Shading

Shader creates a cel-shading effect for 3D models to achieve a cartoon-like appearance.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/eaf6d629-d2cb-4777-be7b-6ca1c26718d4

## Sunset Horizon

//TODO:

This shader simulates a sunset horizon with a dynamic gradient effect and light scattering.

**Assignment Video:** [Watch the video](http://link-to-the-video)

**Description:** [Read the description](http://link-to-the-description)

## Star Twinkling

Shader implements a starry sky with a twinkling star effect based on noise to the 2D surface.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/dad67f87-5a47-43fd-9244-d2392b79074d

## Heat Haze Effect

Shader simulates the visual distortion caused by heat haze.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/d0589f13-e8da-43ba-b64a-41bcea1b23ce

## Vignette Effect

Shader implements a vignette effect to freeze the edges of the screen, focusing attention on the center.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/32a5eeb9-1cc5-4b8e-a948-8f65bd7cd231

## Motion Blur

Shader develops a motion blur effect to convey a sense of speed or movement.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/ec80607d-502b-4207-9cf5-6f81ec917fb0

## Stencil-Based Object Highlighting

Shader utilizes stencil buffers to create an effect where selected objects in a 2D scene are highlighted over other objects.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/57905521-c85a-4401-8e13-d1453a3713a7

## Depth Offset for Decals

This shader uses depth offset to properly render decals on surfaces. This is crucial for adding details like scars, signs, or dirt on 3D models without altering their geometry.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/611e07f9-c8cf-439e-aebe-2ae8b2d20dbf

## Advanced Stencil Techniques for Portals

//TODO:

This shader creates a portal effect using stencil buffers, where entering one portal visually and seamlessly leads to exiting another.

**Assignment Video:** [Watch the video](http://link-to-the-video)

**Description:** [Read the description](http://link-to-the-description)

## ZTest and ZWrite for X-Ray Vision

Shader uses ZTest and ZWrite parameters to create an X-Ray vision effect, allowing certain objects to be seen through others.

<img width="459" alt="D20-3D-XrayLighting" src="https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/9c3f4fc4-9573-4d29-bb95-32ccd3dfbf0b">

<img width="506" alt="D20-3D-XrayLighting2" src="https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/36c19d72-3406-43c2-94ca-f563640dce4e">

## Stencil Buffer for Dynamic Shadows

Shader uses the stencil buffer to create dynamic shadows that interact with various objects in the 2D scene, adding a layer of realism and depth.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/86e4940d-f871-400f-b87e-028a590927cb

## ZClip for Clipping Effects

Shader utilizes ZClip to create unique clipping effects, such as objects disappearing or transitioning in a particular way when they move beyond a certain plane.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/dd172401-52cb-42df-81d6-5f7cbe2b7833

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/23f2ec1a-36f8-4af7-b6e6-f793c49e9d1f

## Depth-Based Effects for Water Surface

Shader simulates a dynamic water surface with waves using shaders focused on depth-based effects.

<img width="595" alt="D23-3D-DepthWaterMeshHole" src="https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/63f536f3-93da-4381-bd8c-8d9de6faeafa">

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/a45e94b0-37f0-45b6-a029-638f71cf43bd

## Offset and Stencil for Smooth Curve Visualization

Shader uses a combination of offset and stencil techniques to visualize smooth curves or surfaces from basic geometric shapes.

https://github.com/AdrianOrcik/GraphicAoC23/assets/14979589/f2551d46-8f35-42a7-9a80-d2f2840b4cb0

