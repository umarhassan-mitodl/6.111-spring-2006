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
title: Group 13
uid: 3ea44805-4a81-c281-22f1-1f62c8c8d827
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Groups: {{% resource_link 154db192-2574-3f27-fc7e-20328846dbe3 "1" %}} | {{% resource_link cc50bffd-29fe-46a8-2986-bc1cfa41de10 "2" %}} | {{% resource_link ace94507-4f7e-bb05-30ff-a5bcc981ddec "3" %}} | {{% resource_link b2eb79ee-1861-14d3-8a60-26d864e56d26 "4" %}} | {{% resource_link 3b862e69-7adf-714d-c58f-a02ac6fd37e3 "5" %}} | {{% resource_link 7d70f20b-d552-c8a6-1be5-c2300b36deb7 "6" %}} | {{% resource_link 2c9812a5-49b4-08db-64ac-968b82c46542 "7" %}} | {{% resource_link a0c6077b-44dd-9568-d8e5-b199ea8ff7ab "8" %}} | {{% resource_link adfdd650-b23d-826e-2a98-f527493aba1b "9" %}} | {{% resource_link 6d09a50d-68de-ac04-2fef-b8a4dd7141a1 "10" %}} | {{% resource_link 2c408b96-f405-b9b8-7c7a-f54469520d8b "11" %}} | {{% resource_link 07d2680f-44db-7ed7-91a5-3e42659bf896 "12" %}} | 13 | {{% resource_link 2abdaad1-137b-1bd8-ace4-562ce30baf8b "14" %}} | {{% resource_link 08ca57c2-ac27-d35e-12fb-0c544d7f16bc "15" %}}

Audio-Driven Laser Tetris
-------------------------

By Cameron Lewis and James Sun

Abstract
--------

The purpose of this project is to demonstrate an advanced version of the classic arcade game Tetris. Our version boasts a much more dynamic and random game-play experience than conventional implementations, bringing new meaning to the concept of background music. Users will manipulate the falling objects as in the traditional game, but there will be several twists. The entire game will be driven by music and then projected onto a large screen using a laser raster system. In addition, more detailed game graphics along with other audio-based effects will be displayed on a VGA monitor connected to the FPGA Labkit.

The audio-based elements of the game will operate in the following manner: the drop rate of the game pieces will be controlled by music frequencies and magnitudes. The audio input to the system will be connected to the AC97 audio decoder on the Labkit which will digitize the analog signals and pass them into the FPGA for processing.

The video components will be comprised of two display elements. First will be the high resolution VGA imaging module, which will display the complete Tetris game with scores, settings, and other game errata. Second will be the laser display, which will interface with the core graphics output of the Tetris game by a separate laser controller module - whose job will be to rapidly modulate the output of the laser at appropriate times as to create a low resolution, scanning raster image of the Tetris playing field.

Project Files
-------------

Presentation ({{% resource_link d58c108e-98a6-a77e-cace-2178c786dec0 "PDF" %}})

Report ({{% resource_link e1cb3a38-820b-773d-6062-42f6e541f7e0 "PDF" %}})

Report Appendix ({{% resource_link 340b4daa-a8ef-4430-6ffa-a09e576bc9f5 "PDF" %}})