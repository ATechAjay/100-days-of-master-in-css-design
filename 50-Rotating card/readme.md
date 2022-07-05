---
author: "Ajay Yadav 🎯"
handle: "@ATechAjay"
source: "https://twitter.com/ATechAjay/status/1478676280593682434"
date: "January 5, 2022 2:34 PM"
---
![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - January 5, 2022 2:34 PM

💚 Day 5️⃣0️⃣ / 1️⃣0️⃣0️⃣ Master in CSS Design series!

💥Today we going to design an rotating card using CSS!

❓What's the main logic behind it with the codepen link?

⛔ The BEST thread ever for learning!!!!!

[#100DaysOfCode](https://twitter.com/hashtag/100DaysOfCode)  
[[#webdev](https://twitter.com/hashtag/webdev) elopment](https://twitter.com/hashtag/webdevelopment)  
#webdev 

Let me explain!👇🧵 [pic.twitter.com/z4xPkl4Zb8](https://twitter.com/ATechAjay/status/1478676280593682434/video/1)

📌 There are the 3 most important CSS properties for this design.

1️⃣ perspective: 700px;

2️⃣ transform-style: preserve-3d;

3️⃣ backface-visibility: hidden;

Let's start...

1️⃣ perspective: 700px; ???

→ Perspective defines the distance(length) between user(eye) and object(screen).

→ Lower values are very close to our eyes.

→ Higher values are the far distance between eyes and objects.

→ It is used to give the 3D position to the element.

→ We define perspective in the parent element.

→ We have to set only +VE values of the perspective because distance can not be negative.

2️⃣ transform-style: preserve-3d; ???

→ If you want to position the child element in 3d, 
then "preserve-3d" can be used as the value of the "transform-style" property.

3️⃣ backface-visibility: hidden; ???

→ It defines the back part of the element.

→ or, Its mirror image of the front image.

→ or, A backface or back part can be visible when the user rotates or flip an element.

→ If you want to visible the back part of an element to the user, then you have to use "visible" as the values of the "backface-visibility" property.

→ And, If you want to hide the back part of an element to the user, then you have to use "hidden" as the values of the "backface-visibility" property.

📌Now come to the topic...

→ This is the simple layout of the design. [pic.twitter.com/1fGPQU3vpz](https://twitter.com/ATechAjay/status/1478676310150971392/photo/1)

![3_1478663271620038657](https://pbs.twimg.com/media/FIVEaUdUUAEWj4P.png)

→ Then we have to set the perspective property.

→ And approx 700px distance between the user and the object. [pic.twitter.com/YIoynWVHWf](https://twitter.com/ATechAjay/status/1478676316967043073/photo/1)

![3_1478671064125218819](https://pbs.twimg.com/media/FIVLf5zVIAMXE9d.jpg)

→ transform-style: preserve-3d;

→ Because we want the 3D effect of the child element inside the container. [pic.twitter.com/wrQ3BxyE32](https://twitter.com/ATechAjay/status/1478676323669200899/photo/1)

![3_1478671589897957379](https://pbs.twimg.com/media/FIVL-gdUcAMt0x1.jpg)

→ When we hover over the container, then the child element will rotate to 180 degrees. [pic.twitter.com/Fielwleaz2](https://twitter.com/ATechAjay/status/1478676329931280386/photo/1)

![3_1478672175884242947](https://pbs.twimg.com/media/FIVMgnbVkAMvHzX.jpg)

→ Then we have to set "hidden" as a value of "backface-visibility" of the front images.

→ Because we do not want to see the mirror image of the front image. [pic.twitter.com/7XlQtunhWy](https://twitter.com/ATechAjay/status/1478676336570892288/photo/1)

![3_1478672614906232836](https://pbs.twimg.com/media/FIVM6K6VgAQl2hT.jpg)

❓Mirror image??

This is the real image.👇 [pic.twitter.com/vMgsBox2po](https://twitter.com/ATechAjay/status/1478676343361400833/photo/1)

![3_1478673674513182721](https://pbs.twimg.com/media/FIVN32QUcAEHvyQ.png)

→ And it is the mirror image of the above image.

👇 [pic.twitter.com/Kxy7szyMyZ](https://twitter.com/ATechAjay/status/1478676349694844933/photo/1)

![3_1478673799675482112](https://pbs.twimg.com/media/FIVN_IhVkAAM8Zo.png)

→ And finally, we have to also rotate the backface of the element to 180 degrees.

→ That's why it's visible to the user without a mirror image. [pic.twitter.com/WgMHEGBfyw](https://twitter.com/ATechAjay/status/1478676356825108484/photo/1)

![3_1478674323627859969](https://pbs.twimg.com/media/FIVOdoZUYAEMSl_.jpg)

codepen link:

[codepen.io/atechajay/pen/…](https://codepen.io/atechajay/pen/LYzrRbe?editors=1000)

[Thread link](https://twitter.com/ATechAjay/status/1478676280593682434)