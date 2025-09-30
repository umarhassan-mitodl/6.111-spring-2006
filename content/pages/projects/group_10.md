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
title: Group 9
uid: adfdd650-b23d-826e-2a98-f527493aba1b
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Groups: {{% resource_link 154db192-2574-3f27-fc7e-20328846dbe3 "1" %}} | {{% resource_link cc50bffd-29fe-46a8-2986-bc1cfa41de10 "2" %}} | {{% resource_link ace94507-4f7e-bb05-30ff-a5bcc981ddec "3" %}} | {{% resource_link b2eb79ee-1861-14d3-8a60-26d864e56d26 "4" %}} | {{% resource_link 3b862e69-7adf-714d-c58f-a02ac6fd37e3 "5" %}} | {{% resource_link 7d70f20b-d552-c8a6-1be5-c2300b36deb7 "6" %}} | {{% resource_link 2c9812a5-49b4-08db-64ac-968b82c46542 "7" %}} | {{% resource_link a0c6077b-44dd-9568-d8e5-b199ea8ff7ab "8" %}} | 9 | {{% resource_link 6d09a50d-68de-ac04-2fef-b8a4dd7141a1 "10" %}} | {{% resource_link 2c408b96-f405-b9b8-7c7a-f54469520d8b "11" %}} | {{% resource_link 07d2680f-44db-7ed7-91a5-3e42659bf896 "12" %}} | {{% resource_link 3ea44805-4a81-c281-22f1-1f62c8c8d827 "13" %}} | {{% resource_link 2abdaad1-137b-1bd8-ace4-562ce30baf8b "14" %}} | {{% resource_link 08ca57c2-ac27-d35e-12fb-0c544d7f16bc "15" %}}

A Two-Input Polygraph
---------------------

By Chris Buenrostro, Isaac Rosmarin, Archana Venkataraman

Abstract
--------

In this project we propose to design and implement a 2-input polygraph using the Xilinx Virtex2 FPGA. The two physiological signals that we will focus on are pulse rate and skin conductivity. These inputs were chosen because they are fairly easy to measure and interpret. During times of emotional stress, such as when the subject is forced to lie, his pulse rate increases. Likewise, the subject is more likely to sweat, thus increasing his skin conductivity.

The project will be divided into three portions: the Physiological Sensor Block, the Digital Control Block, and the Display Block. The sensor block will focus on extracting data from the analog sensors used to measure pulse and skin conductivity. It will involve assembling the two sensors needed for the project, interfacing with an analog-to-digital converter (ADC), and storing the results in a Block RAM. The digital control block is the major control unit for the project. Although it will provide for both user interaction and memory access, most of this section will focus on analyzing data from the sensor. Since the subject is asked several control questions which serve as a baseline, the system must be able to identify different types of questions and algorithmically analyze the physiological signals appropriately. The display block will focus on outputting the measurements and the results. Just as conventional polygraphs record the physiological data using pen and paper, we would like to display the sensor outputs and the computer's decision on the monitor. This portion will provide for additional features such as screen capture, so data can be compared visually.

Project Files
-------------

Presentation ({{% resource_link cd127bb9-8cf0-129a-24e7-8e6a02fcae12 "PDF" %}})

Report ({{% resource_link b9937ffb-556d-53c0-806b-20e9a7baa7c0 "PDF" %}})

Report Appendix ({{% resource_link f8c2b869-d379-3abd-1b62-7cf632280915 "PDF" %}})