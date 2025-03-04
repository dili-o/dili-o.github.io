---
layout: default
title: Portfolio
permalink: /
---

## C++ Vulkan Renderer

<img src="{{ site.baseurl }}/assets/FlightHelmet.png" width="600">
<img src="{{ site.baseurl }}/assets/Sponza.png" width="600">
<img src="{{ site.baseurl }}/assets/Sponza_Meshlet.png" width="600">

<i>A modern rendering engine written from scratch using C++ with the [Vulkan API](https://vulkan.lunarg.com/) that leverages GPU-driven techniques to maximize efficiency and visual quality. This project explores modern real-time rendering approaches and advancements in graphics programming. The renderer is a used to view [glTF](https://www.khronos.org/Gltf) models. </i>

<div class="project-desc" markdown="1">
- Implements a [mesh shader](https://www.khronos.org/blog/mesh-shading-for-vulkan) pipeline for GPU side meshlet culling 
- Implements two-pass [occlusion culling](https://jcgt.org/published/0002/02/05/) using a depth pyramid
- Makes use of Imgui to display a GPU profiler
</div>

<div markdown="1">
 Access the GitHub repository [HERE](https://github.com/dili-o/vulkan-renderer)
</div>
----------------------




## Compute based Path Tracer

<img src="{{ site.baseurl }}/assets/Pathtracer.png" width="600">

<i>In this project, I implement the core concepts discussed in the e-book ["Ray Tracing in One Weeked"](https://raytracing.github.io/books/RayTracingInOneWeekend.html), converting the CPU implementation from the book to a GPU implementation utilizing the compute pipeline in the Vulkan API.</i>

<div class="project-desc" markdown="1">
- Uses Vulkan's compute pipeline to process ray intersections in parallel
- Implements Lambertian, Metal, and Dielectric materials
- Accumulates rendered frames for progressive refinement
</div>

<div markdown="1">
Access the GitHub repository [HERE](https://github.com/dili-o/RayTracing)
</div>
----------------------

## Space Invaders Clone: C++ SFML Project

<img src="{{ site.baseurl }}/assets/Space_Invaders.gif" alt="Animated GIF" width="600">

<i>This project is a clone of the arcade classic Space Invaders, built from the ground up in C++ with SFML. The project was built as a learning experience following the free lectures by [David Churchill](https://www.youtube.com/playlist?list=PL_xRyXins84_Jf-aCh7chj47HR4oZLPwK) on game programming using an Entity Component System.

<div class="project-desc" markdown="1">
- Entity Component System (ECS) for separation of concerns and improved performance
- AABB Collision Detection and Resolution for precise hitbox interactions between player, enemies, and projectiles
- Resource Management for managing loading and caching of textures, sounds, and fonts
</div>

<div markdown="1">
Access the GitHub repository [HERE](https://github.com/dili-o/Scene_Invaders)
</div>
----------------------
