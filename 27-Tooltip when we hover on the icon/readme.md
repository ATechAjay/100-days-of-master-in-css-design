---
author: "Ajay Yadav 🎯"
handle: "@ATechAjay"
source: "https://twitter.com/ATechAjay/status/1470307079940304898"
date: "December 13, 2021 12:18 PM"
likes: 10
retweets: 15
replies: 5
---
![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

💚Day 2️⃣7️⃣ /  1️⃣ 0️⃣0️⃣ days of Master in CSS Design series!

💥 Today we going to design a tooltip when we hover on the icon.

❓What's the main logic behind it with the codepen link?

[#100DaysOfCode](https://twitter.com/hashtag/100DaysOfCode)  
[#webdevelopment](https://twitter.com/hashtag/webdevelopment)  
[#CodeNewbie](https://twitter.com/hashtag/CodeNewbie)  

Let me explain👇🧵 [pic.twitter.com/V4Oljwlp3Z](https://twitter.com/ATechAjay/status/1470307079940304898/video/1)

[Tweet link](https://twitter.com/ATechAjay/status/1470307079940304898)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢 The most complicated task is to design this tooltip.

👀Which you are seeing in red color.

👇 [pic.twitter.com/aSK6LH1RpH](https://twitter.com/ATechAjay/status/1470307087494250496/photo/1)

![3_1470293254956408833](https://pbs.twimg.com/media/FGeH7OlUYAEUWiO.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307087494250496)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢 Now we have to design it and keep it at the exact location.

🟢 So we can make it using before pseudo element.

🟢 So first we will set its height and width(red box).

👇
height = 10px
width = 10px

To make "square" [pic.twitter.com/Y0crRAydaa](https://twitter.com/ATechAjay/status/1470307093370458112/photo/1)

![3_1470295935456407552](https://pbs.twimg.com/media/FGeKXQOUcAAH5Wn.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307093370458112)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢 So this box has to take us to the bottom.

🟢 So for this, we have to set this property.

📌 bottom: 0;

👇 [pic.twitter.com/R5OynFTIiy](https://twitter.com/ATechAjay/status/1470307099288629248/photo/1)

![3_1470297402531672065](https://pbs.twimg.com/media/FGeLspgUcAEE2lv.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307099288629248)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢 Now we have to take this box to the center.

🟢 So for this, we have to set this property.

left : 50%;

🔴But this box is not in the center at all. [pic.twitter.com/aF3k8CtkhO](https://twitter.com/ATechAjay/status/1470307110525104129/photo/1)

![3_1470297978728423425](https://pbs.twimg.com/media/FGeMOMAVIAEEkbR.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307110525104129)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢So to center it, we have to use the transform property.

👇
transform: translate(-50%);

Great, now it is visible in the center.

👇 [pic.twitter.com/GWEVruYggg](https://twitter.com/ATechAjay/status/1470307116376203267/photo/1)

![3_1470298984577056770](https://pbs.twimg.com/media/FGeNIvFVQAIfAxR.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307116376203267)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢 Now we have to rotate this box.

🟢 Again, we have to use the transform property.

transform : rotate(45deg); [pic.twitter.com/VfmhV1pwM0](https://twitter.com/ATechAjay/status/1470307123938557953/photo/1)

![3_1470299721256214532](https://pbs.twimg.com/media/FGeNznbVIAQd5HJ.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307123938557953)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢 Now, this box has to be brought down, absolutely on edge.

👀 So I have 2 solutions for this.

1. set bottom value = height / 2
2. set bottom value = 0
👇
Then 

transform : translateY(50%) [pic.twitter.com/WEQocJUgBY](https://twitter.com/ATechAjay/status/1470307130427117571/photo/1)

![3_1470304036507176962](https://pbs.twimg.com/media/FGeRuy_VUAIoYrU.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307130427117571)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

🟢 And finally set the background color the same as the background color of the pseudo-element.

BOOM🎉

👇 [pic.twitter.com/1oIMfAKulS](https://twitter.com/ATechAjay/status/1470307137444192259/photo/1)

![3_1470304789288292352](https://pbs.twimg.com/media/FGeSanUVkAA7PKN.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307137444192259)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

Finale code is here for this tooltip!
👇 [pic.twitter.com/1zCDcJohbs](https://twitter.com/ATechAjay/status/1470307143513350146/photo/1)

![3_1470305459198312449](https://pbs.twimg.com/media/FGeTBm7VQAETRtL.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307143513350146)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

👀Now you can design your text as required.

🔴Don't forget to set opacity and transform property for this design.

👇 [pic.twitter.com/IerrQt9MeH](https://twitter.com/ATechAjay/status/1470307150593282048/photo/1)

![3_1470305881745068034](https://pbs.twimg.com/media/FGeTaNCVEAIGKOr.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307150593282048)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

Finally, design the hovering effect like this.

👇 [pic.twitter.com/tsXYGc9RdY](https://twitter.com/ATechAjay/status/1470307160508620802/photo/1)

![3_1470306413444419585](https://pbs.twimg.com/media/FGeT5JxVUAE2_p6.jpg)

[Tweet link](https://twitter.com/ATechAjay/status/1470307160508620802)

---

![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 13, 2021 12:18 PM

codepen:

[codepen.io/atechajay/pen/…](https://codepen.io/atechajay/pen/poWNKaG)

[Tweet link](https://twitter.com/ATechAjay/status/1470307163939561473)