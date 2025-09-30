---
content_type: page
description: ''
hide_download: true
hide_download_original: null
learning_resource_types:
- Projects
ocw_type: CourseSection
parent_title: Projects
parent_type: CourseSection
parent_uid: 332f2eab-5d2e-3e04-51e5-b212cabc7de3
title: Group 5
uid: 3b862e69-7adf-714d-c58f-a02ac6fd37e3
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Groups: {{% resource_link 154db192-2574-3f27-fc7e-20328846dbe3 "1" %}} | {{% resource_link cc50bffd-29fe-46a8-2986-bc1cfa41de10 "2" %}} | {{% resource_link ace94507-4f7e-bb05-30ff-a5bcc981ddec "3" %}} | {{% resource_link b2eb79ee-1861-14d3-8a60-26d864e56d26 "4" %}} | 5 | {{% resource_link 7d70f20b-d552-c8a6-1be5-c2300b36deb7 "6" %}} | {{% resource_link 2c9812a5-49b4-08db-64ac-968b82c46542 "7" %}} | {{% resource_link a0c6077b-44dd-9568-d8e5-b199ea8ff7ab "8" %}} | {{% resource_link adfdd650-b23d-826e-2a98-f527493aba1b "9" %}} | {{% resource_link 6d09a50d-68de-ac04-2fef-b8a4dd7141a1 "10" %}} | {{% resource_link 2c408b96-f405-b9b8-7c7a-f54469520d8b "11" %}} | {{% resource_link 07d2680f-44db-7ed7-91a5-3e42659bf896 "12" %}} | {{% resource_link 3ea44805-4a81-c281-22f1-1f62c8c8d827 "13" %}} | {{% resource_link 2abdaad1-137b-1bd8-ace4-562ce30baf8b "14" %}} | {{% resource_link 08ca57c2-ac27-d35e-12fb-0c544d7f16bc "15" %}}

3-D Pong
--------

By Igor Ginsburg

Abstract
--------

3D Pong takes MIT Pong to the next level with a 3D interface. At the heart of the project there is a hardware based 3D renderer. The renderer takes in a 3D model, specifically a sequence of colored triangles in a 3D space, and produces a 2D SVGA image. The view is controlled through a trackball mouse, which specifies rotations, translations and zoom. While the renderer can take in pre-built models stored in on-chip ROM, during gameplay a model of the current board is generated dynamically.

The project contains several high-level modules in addition to the renderer. A track-ball driver connects to the PS/2 interface and provide rotation, translation and zoom inputs, along with a possible lightsource input, to the renderer. A game-logic module provides ball and paddle coordinates to the game-model builder. The game-model builder turns the ball and paddle coordinates into a 3D model of the game field. The 2D image produced by the renderer is buffered in a double-buffer module which interfaces with the labkit SRAM. An SVGA module uses these buffered images to generate monitor outputs.

The renderer is pipelined, and is divided into several submodules. These include a rotator, a translator, a triangle shader, a projector, and a pixel-painter. The rotator module uses matrix multiplication to rotate triangle vertices about the origin. The translator module uses signed subtraction to recenter the points about a new origin. The shader module calculates a vector normal to the triangle's plain, then take a dot product with the light-source vector, in order to calculate the proper color for the entire triangle. The projector module, uses the z-coordinate of each point to rescale the x and y coordinates, based on a given lens focal length. Finally, the pixel painter enumerates the pixels in the interior of the triangle, storing their colors and z-coordinates to the buffer module.

Project Files
-------------

Presentation ({{% resource_link 61f8548e-486f-7eca-b897-1f962d9e63d1 "PDF" %}})

Report ({{% resource_link 9837d1a7-f89f-fd4f-db83-d34d63e245f8 "PDF" %}})

Report Appendix ({{% resource_link 6e2d3ddb-2dce-8145-d5a5-15311cdd8857 "PDF" %}})