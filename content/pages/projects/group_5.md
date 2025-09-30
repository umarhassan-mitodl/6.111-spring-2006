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
title: Group 4
uid: b2eb79ee-1861-14d3-8a60-26d864e56d26
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Groups: {{% resource_link 154db192-2574-3f27-fc7e-20328846dbe3 "1" %}} | {{% resource_link cc50bffd-29fe-46a8-2986-bc1cfa41de10 "2" %}} | {{% resource_link ace94507-4f7e-bb05-30ff-a5bcc981ddec "3" %}} | 4 | {{% resource_link 3b862e69-7adf-714d-c58f-a02ac6fd37e3 "5" %}} | {{% resource_link 7d70f20b-d552-c8a6-1be5-c2300b36deb7 "6" %}} | {{% resource_link 2c9812a5-49b4-08db-64ac-968b82c46542 "7" %}} | {{% resource_link a0c6077b-44dd-9568-d8e5-b199ea8ff7ab "8" %}} | {{% resource_link adfdd650-b23d-826e-2a98-f527493aba1b "9" %}} | {{% resource_link 6d09a50d-68de-ac04-2fef-b8a4dd7141a1 "10" %}} | {{% resource_link 2c408b96-f405-b9b8-7c7a-f54469520d8b "11" %}} | {{% resource_link 07d2680f-44db-7ed7-91a5-3e42659bf896 "12" %}} | {{% resource_link 3ea44805-4a81-c281-22f1-1f62c8c8d827 "13" %}} | {{% resource_link 2abdaad1-137b-1bd8-ace4-562ce30baf8b "14" %}} | {{% resource_link 08ca57c2-ac27-d35e-12fb-0c544d7f16bc "15" %}}

Fingerprint Verification System
-------------------------------

By Bashira Chowdhury and Cheryl Texin

Abstract
--------

We will design and implement an image recognition system to identify fingerprints based on a given database. We will begin by inputting simple images and checking that the system accurately identifies those images. As the system is developed, more complex images can be used. The final stage of the project will involve identifying an individual's fingerprint based on standard points of identification used in common practice.

This project consists of a few stages. The initial stage will involve creating a database in memory for the image comparison. The next stage will be developing an interface between the camera and a RAM to store the image that needs to be identified. Once the image has been loaded into the system, it must be processed to select the appropriate characteristics for the comparison to the database. The processed image will then be compared to the images in the database to determine the quality of the similarities. The most similar image will be selected and presented to the user interface along with the quality of the identification.

The image processing will involve a series of filters in the spatial domain. There will be an edge-detection filter to sharpen the image, prior to binarization of the fingerprint. Another filter will select the unique components of the fingerprint. The database will contain the post-processed fingerprint information to minimize the size of the stored data. The database size will be limited to the memory of the labkit, which will be sufficient to demonstrate the functionality of the fingerprint matching system.

The work will be split into two components. Bashira will be responsible for interfacing the camera to the labkit, as well as managing the data storage in memory. Cheryl will implement the image processing to isolate the data for the analysis and the matching. Once the fingerprint recognition scheme is working, both team members will work to enhance the identification interface as time allows to create a visually appealing result.

Project Files
-------------

Presentation ({{% resource_link 88b085c5-056b-33d6-caf2-f13c39f1286a "PDF" %}})

Report ({{% resource_link f0614cc0-efa9-719b-0d35-fff6db957b0e "PDF" %}})

Report Appendix ({{% resource_link 6e2d3ddb-2dce-8145-d5a5-15311cdd8857 "PDF" %}})