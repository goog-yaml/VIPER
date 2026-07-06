# July 6th: Second revision

Today I redid the board again, following my normal routine redo to get the size smaller and smaller.

Rev1 was large and rev1.1 adopted a stick like shape while rev1.2 got wider by around 2 mm but a lot shorter.
![revision1](viperv1.png)
As seen here Revision one is very big, with that LiPo holder on board a lot of the footprint is dedicated to that and that only. Making it very clunky for it's intended purpose.
![revision1.1](viperv1.1.png)
Revision 1.1 fixes this by adding a two pin JST connector to save space with the added complexity of now needing to find the correct battery and tuning the board for it. And also the extra connectors adds more complexity requiring another component to be on the edge.
![revision1.2](viperv1.2.png)
Revision 1.2 fixes the issue of the USB serial chip and mitigates a possible manufacturing issue considering the chip used (FTDI FT231XQ) is outdated and expesive. To combat this I replaced the old IC with a new CH340X that has less pins and an arguably easier to work with MSOP-10 package. The package does come with gullwing pins, now most people would think of this as a size increase but considering my (questionable) soldering skills I consider it a pro.
So far the project seems to be going good, I think I'm going to split this repo for different models of VIPER. See you!

-Matias

[Total time spent: 48 mins]
