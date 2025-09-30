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
title: Group 15
uid: 08ca57c2-ac27-d35e-12fb-0c544d7f16bc
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Groups: {{% resource_link 154db192-2574-3f27-fc7e-20328846dbe3 "1" %}} | {{% resource_link cc50bffd-29fe-46a8-2986-bc1cfa41de10 "2" %}} | {{% resource_link ace94507-4f7e-bb05-30ff-a5bcc981ddec "3" %}} | {{% resource_link b2eb79ee-1861-14d3-8a60-26d864e56d26 "4" %}} | {{% resource_link 3b862e69-7adf-714d-c58f-a02ac6fd37e3 "5" %}} | {{% resource_link 7d70f20b-d552-c8a6-1be5-c2300b36deb7 "6" %}} | {{% resource_link 2c9812a5-49b4-08db-64ac-968b82c46542 "7" %}} | {{% resource_link a0c6077b-44dd-9568-d8e5-b199ea8ff7ab "8" %}} | {{% resource_link adfdd650-b23d-826e-2a98-f527493aba1b "9" %}} | {{% resource_link 6d09a50d-68de-ac04-2fef-b8a4dd7141a1 "10" %}} | {{% resource_link 2c408b96-f405-b9b8-7c7a-f54469520d8b "11" %}} | {{% resource_link 07d2680f-44db-7ed7-91a5-3e42659bf896 "12" %}} | {{% resource_link 3ea44805-4a81-c281-22f1-1f62c8c8d827 "13" %}} | {{% resource_link 2abdaad1-137b-1bd8-ace4-562ce30baf8b "14" %}} | 15

Local Decoding of Walsh Codes to Reduce CDMA Despreading Computation
--------------------------------------------------------------------

By Matthew Doherty

Abstract
--------

Chan et al. invented several novel classes of algorithms to reduce computation in software implementations of the IS-95 reverse link by exploiting software's inherent flexibility over hardware. The algorithms work by processing only a fraction of the despread signal to decode Walsh codewords, relying on an outer feedback loop to choose the fraction of despread signal to process in order to maintain a target bit error rate. Because FPGAs are significantly more flexible than ASICs, the same algorithms can be implemented in an FPGA to reduce computation in hardware. This reduction in computation results directly in power savings because FPGA power consumption is heavily dependent on its gates' switching activity. We propose to implement the "novel and elegant" Generalized Local Decoding of Walsh codewords in an FPGA to determine the potential power savings of the algorithm in hardware.

In doing so, despread codewords from a test data set are processed by the Walsh decoder. Their output bit streams are checked against the known optimal decoding and the bit error rate is determined. This bit error rate is fed back to the decoder, which uses it to choose the fraction of the despread signal to process.

To validate the results, the test data set can be chosen from several of varying signal-to-noise ratio (SNR). In addition, the outer feedback loop can be turned off, so the corresponding bit error rate of the open loop system can be analyzed.

The results are shown in real time on the LCD display, simultaneously comparing the bit error rates and power usages of the optimal decoder, feedback-controlled suboptimal decoder, and open loop suboptimal decoder. Each codeword is processed slowly enough so that it is apparent that the feedback loop is keeping the bit error rate constant and using minimal power.

Project Files
-------------

Presentation ({{% resource_link 689141b2-3929-f6ca-86db-ebc290a23b39 "PDF" %}})

Report ({{% resource_link 3eb763d1-ab6c-3928-3a41-ea20661e9634 "PDF" %}})

Report Appendix ({{% resource_link ef2b9aa1-9e05-1d68-b9ac-04dc90e2f590 "PDF" %}})