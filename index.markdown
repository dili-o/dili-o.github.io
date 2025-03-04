---
layout: default
title: Portfolio
permalink: /
---

## Vulkan Renderer

<img src="{{ site.baseurl }}/assets/FlightHelmet.png" width="600">

<div class="project-desc" markdown="1">
- A vulkan renderer where I am explore modern rendering techniques
- Implements GPU driven techniques like compute frustum and occlusion culling
- Makes use of Imgui to display a GPU profiler
</div>

<i>A modern rendering engine built with Vulkan that leverages GPU-driven techniques to maximize efficiency and visual quality. This project explores modern real-time rendering approaches and advancements in graphics programming.</i>

<div markdown="1">
 Access the GitHub repository [HERE](https://github.com/dili-o/vulkan-renderer)
</div>
----------------------




## Compute based Path Tracer

<img src="{{ site.baseurl }}/assets/Pathtracer.png" width="600">

<div class="project-desc" markdown="1">
- Uses Vulkan's compute pipeline to process ray intersections in parallel
- Implements Lambertian, Metal, and Dielectric materials
- Accumulates rendered frames for progressive refinement
</div>

<i>In this project, I implement the core concepts discussed in the e-book ["Ray Tracing in One Weeked"](https://raytracing.github.io/books/RayTracingInOneWeekend.html), converting the CPU implementation from the book to a GPU implementation utilizing the compute pipeline in the Vulkan API.</i>

<div markdown="1">
Access the GitHub repository [HERE](https://github.com/dili-o/RayTracing)
</div>
----------------------

## Space Invaders Clone: SFML Project

<img src="{{ site.baseurl }}/assets/Space_Invaders.gif" alt="Animated GIF" width="600">
<div class="project-desc" markdown="1">
- Entity Component System (ECS) for separation of concerns and improved performance
- AABB Collision Detection and Resolution for precise hitbox interactions between player, enemies, and projectiles
- Resource Management for managing loading and caching of textures, sounds, and fonts
</div>

<i>This project is a clone of the arcade classic Space Invaders, built from the ground up in C++ with SFML. The project was built as a learning experience following the free lectures by [David Churchill](https://www.youtube.com/playlist?list=PL_xRyXins84_Jf-aCh7chj47HR4oZLPwK) on game programming using an Entity Component System.

Access the GitHub repository [HERE](https://github.com/dili-o/Scene_Invaders)

