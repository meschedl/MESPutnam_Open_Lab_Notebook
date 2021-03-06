---
layout: post
title: MBD of Samples for Methylation Comparison
category: [ Processing, Methylation ]
tags: [ DNA, Pocillopora, Montipora ]
---

## Methyl-Binding Domain Enrichment of Samples for Methylation Comparison

Samples for methylation comparison are from the Holobiont Integration Project, and were extracted by Emma Strand or myself, see her notebook posts for the extraction specifications: [20190805 and 20180823](https://emmastrand.github.io/EmmaStrand_Notebook/Holobiont-Integration-August-DNA-RNA-Extractions/), [20190718](https://emmastrand.github.io/EmmaStrand_Notebook/Holobiont-Integration-July-DNA-RNA-Extractions/) and [20190903](https://emmastrand.github.io/EmmaStrand_Notebook/Holobiont-Integration-September-DNA-RNA-Extractions/).

### Shearing Samples to ~500bp

1. Prepare samples for 1µg in 80µl of Tris HCl

|Sample|Volume DNA|Volume Tris HCl|
|---|---|---|
|1041|16.03|63.97|
|1471|18.25|61.75|
|1637|18.25|68.48|
|1101|36.9|43.1|
|1548|43.29|36.71|
|1628|58.82|21.18|

2. Prep Qsonica following [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qsonica/)
3. Set time for 1min 30 sec, 15 second on 15 seconds off, 25% amplitude
4. Check samples on tapestation after results [1]() [2]()
5. Samples 1637 and 1628 were in the more 600bp range average so were sonicated for 15 seconds more

### MBD Enrichment

_Made 43000µl of 1X Wash/Bind buffer from 5X concentrate before starting_

**Preparing Beads**

1. Pipetted up and down the Dynabeads M-280 Streptavidin to resuspend them
2. Made 6 1.5mL tubes, each with 10µl of Dynabeads (the amount recommended for less than or equal to 1µg of DNA input)
3. Brought volume up to a total of 100µl with 90µl of 1X bind/wash buffer to each tube
4. Pipetted to mix
5. Placed tubes on long magnet rack and removed and discarded supernatant when clear
6. Removed tubes from rack and resuspended beads in 100µl 1X bind/wash buffer
7. Placed tubes on long magnet rack and removed and discarded supernatant when clear
8. Removed tubes from rack and resuspended beads in 100µl 1X bind/wash buffer

**Coupling MBD-Biotin Protein to the Beads**

9. Thawed MBD-Biotin protein from -80 on ice
10. Made 6 new 1.5mL tubes, each with 7µl of MBD-Biotin protein (amount recommended for 1µg of DNA input)
11. Added 93µl of 1X bind/wash buffer to each tube to get up to a total of 100µl
12. Transferred diluted protein to the washed bead tubes for a total volume of 200µl in each of 2 tubes
13. Put samples on the rotisserie mixer for 1 hour at room temp

**Washing MBD-Biotin-Coupled Beads**

14. Spun down **briefly** tubes from above
15. Placed tubes on magnet rack for 1 minute
16. Removed supernatant when clear
17. Resuspended beads in 100µl 1X bind/wash buffer and pipetted to mix
18. Mixed beads on rotisserie mixer for 5 minutes at room temp
19. Repeated: Spun down tubes **briefly**
20. Placed tubes on magnet rack for 1 minute
21. Removed supernatant when clear
22. Resuspended beads in 100µl 1X bind/wash buffer and pipetted to mix
23. Mixed beads on rotisserie mixer for 5 minutes at room temp
24. Repeated again: Spun down tubes **briefly**
25. Placed tubes on magnet rack for 1 minute
26. Removed supernatant when clear
27. Resuspended beads in 100µl 1X bind/wash buffer and pipetted to mix
28. Mixed beads on rotisserie mixer for 5 minutes at room temp
29. Finally: Spun down tubes **briefly**
30. Placed tubes on magnet rack for 1 minute
31. Removed supernatant when clear
32. Resuspended beads in 100µl 1X bind/wash buffer and pipetted to mix

**Capture Reaction**

33. To 6 new 1.5mL tubes, added 20µl each of **5X** bind/wash buffer
34. To each appropriate tube, added the 80µl of the sheared DNA samples (above)
35. Transferred all of each diluted DNA sample to separate tubes with the MBD-Biotin bound beads for a total of 200µl in each tube and pipetted to mix
36. Mixed on rotisserie mixer overnight at 4 degrees C in the cold room

**September 24th 2019, Removing Non-Captured DNA**

38. Again started by writing out protocol to calculate how much 1X bind/wash buffer to dilute (25000µl needed and appropriately diluted)
39. Took tubes out of the cold room rotisserie and spun down **briefly**
40. Placed tubes on magnet rack for 1 minute
41. Removed clear supernatant and **SAVED** in tubes labeled non-captured DNA and sample number
42. Resuspended beads in 200µl of 1X bind/wash buffer and placed on rotisserie mixer for 3 minutes
43. Spun down tubes **briefly**
44. Placed tubes on magnet rack for 1 minute
45. Removed clear supernatant and **SAVED** in tubes labeled wash and the sample number
46. Repeated: added 200µl 1X bind/wash buffer and placed on rotisserie mixer for 3 minutes
47. Spun down tubes **briefly**
48. Placed tubes on magnet rack for 1 minute
49. Removed clear supernatant and **SAVED** in the same tubes labeled wash and the sample number for a total of 400µl in each tube

**Single Fraction Elution**

50. Resuspended beads in 200µl each High Salt Elution buffer
51. Incubated on rotisserie mixer for 3 minutes
52. Spun down tubes **breifly** and placed on magnet rack for 1 minute
53. Removed supernatant when clear and **SAVED** in a new 1.5mL tube labeled captured DNA and the sample number
54. Repeated: added 200µl High Salt Elution Buffer to resuspended beads in each tube
55. Incubated tubes on rotisserie mixer for 3 minutes
56. Spun down tubes **briefly** and placed on magnet rack for 1 minute
57. Removed clear supernatant and **SAVED** in each sample tube for captured DNA, for a total of 400µl in each tube

**Ethanol Precipitation**

Each tube for ethanol precipitation gets 1µl of glycogen (co-precipitator), 1/10th the volume of the sample of 3M sodium acetate pH 5.2, and 2 volumes of the sample 100% ethanol:

_note, 3M sodium acetate is kept in the acid cabinet and volumes were added to samples in the hood_

|Sample|vol glycogen (µl)|vol sodium acetate (µl)| vol 100% EtOH (µl)|
|----|-----|----|----|
|1041 Captured|1|40|800|
|1471 Captured|1|40|800|
|1637 Captured|1|40|800|
|1101 Captured|1|40|800|
|1548 Captured|1|40|800|
|1628 Captured|1|40|800|

58. Vortexed to mix and spun down
59. Placed tubes in the -80 freezer for 3.5 hours
60. Set centrifuge to 1 degrees C  with about 15 min time left and let it run to get down to temp
61. Put 70% EtOH in -20 to chill down
62. Took sample tubes out of -80 and centrifuged for **15 minutes** at 1 degrees C and 14,000 rcf
63. Took tubes out of centrifuge **one at a time** to keep cold, looked at tubes to see if there was a pellet. The non-captured 1431 sample did not have a visible pellet. In all these steps tubes were taken out of the centrifuge one at a time to keep them cold
64. Removed the supernatant and discarded **very carefully**. All samples had a very very small visible pellet
65. Added 500µl of **cold** 70% EtOH to each tube carefully
66. Centrifuged for **5 minutes** at 1 degrees C and 14,000 rcf
67. **Very carefully** removed supernatant from pellet
68. Centrifuged tubes for **5 minutes** at 1 degrees C at 14,000 rcf
69. Removed any remaining supernatant as best as possible with the smallest pipette tip and making sure to not removed the pellet
70. Air dried pellet for 3 minutes
71. Resuspended pellets in 25µl of ultra pure water

**High Sensitivity DNA Qubit**

Followed [Qubit protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/) for HS reagents

|Sample|Standard 1 (RFU)| Standard 2 (RFU)| 1st reading (ng/ul)|Second reading (ng/ul)| Average ng/ul|
|----|-----|-----|-----|-----|----|
|1041 Captured|44.62|25969|0.998|0.993|0.995|
|1471 Captured|44.62|25969|0.846|0.85|0.848|
|1637 Captured|44.62|25969|2.1|2.1|2.1|
|1101 Captured|44.62|25969|0.14|0.14|0.14|
|1548 Captured|44.62|25969|0.172|0.174|0.173|
|1628 Captured|44.62|25969|0.13|0.132|0.131|
