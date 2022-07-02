---
author: "Ajay Yadav 🎯"
handle: "@ATechAjay"
source: "https://twitter.com/ATechAjay/status/1476800839704453122"
date: "December 31, 2021 10:22 AM"
likes: 77
retweets: 28
replies: 7
---
![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav 🎯 ([@ATechAjay](https://twitter.com/ATechAjay)) - December 31, 2021 10:22 AM

💚 Day 4️⃣5️⃣ /  1️⃣0️⃣0️⃣ Master in CSS Design series!

💥Today we going to design grid layouts.

❓What's the main logic behind it with the codepen link?

💯 This is one of the best threads on social media!🙏🥰

[#100DaysOfCode](https://twitter.com/hashtag/100DaysOfCode)  
[[#webdev](https://twitter.com/hashtag/webdev) elopment](https://twitter.com/hashtag/webdevelopment)  
#webdev 

Let me explain!🧵👇 [pic.twitter.com/5huCMjFwEb](https://twitter.com/ATechAjay/status/1476800839704453122/photo/1)

![3_1476782522247770113](https://pbs.twimg.com/media/FH6V4TEVcAE9n68.jpg)

→ We are going to use only "4" CSS grid properties for these layout designs.

→ So for this, we should have a blueprint of the design.

→ suppose, this is our blueprint of the layout!👇

Let's start...
👇 [pic.twitter.com/hDYbub8HOn](https://twitter.com/ATechAjay/status/1476800848973893632/photo/1)

![3_1476783479832530946](https://pbs.twimg.com/media/FH6WwCWVUAI7Prl.jpg)

1️⃣ Define how many boxes are required for this design?

⇉ In my case, 6 boxes are required. [pic.twitter.com/0WFDFrvxkX](https://twitter.com/ATechAjay/status/1476800857110822912/photo/1)

![3_1476784477753929729](https://pbs.twimg.com/media/FH6XqH5VcAEq6rh.jpg)

2️⃣ Find the number of columns in your layout?

⇉ In my case, 3 columns are required. [pic.twitter.com/1erFfPrt1H](https://twitter.com/ATechAjay/status/1476800864497332227/photo/1)

![3_1476784931959296006](https://pbs.twimg.com/media/FH6YEj8VUAYtlBT.jpg)

3️⃣ Find the number of rows in your layout?

⇉ In my case, 3 rows are required. [pic.twitter.com/jcWZ8jv1x1](https://twitter.com/ATechAjay/status/1476800871740567553/photo/1)

![3_1476785238730698758](https://pbs.twimg.com/media/FH6YWawVcAYkp3k.jpg)

5️⃣ Find the index of the grid, row-wise.

⇉ In my case, 1, 2, 3, 4 are the index of rows for this layout. [pic.twitter.com/0VIYjNQuSq](https://twitter.com/ATechAjay/status/1476800878313029639/photo/1)

![3_1476786628349751299](https://pbs.twimg.com/media/FH6ZnTfVcAMPGPj.jpg)

6️⃣ Find the index of the grid, column-wise.

⇉ In my case, 1, 2, 3, 4 are the index of columns for this layout. [pic.twitter.com/9gsVh9O3Xj](https://twitter.com/ATechAjay/status/1476800885153955840/photo/1)

![3_1476786954410680321](https://pbs.twimg.com/media/FH6Z6SKUYAEemtV.jpg)

📌 Now we have to only play with rows and columns of the grid container.

📌 In other words, we have to adjust all boxes inside the grid container.

📌 Remember, 3 rows and columns are required to design our layout.

7️⃣ Now, how to make the columns of the grid?

⇉ well, using the "grid-template-column" property!

→ Always use this property in the container of the grid. [pic.twitter.com/fNUVdBokKV](https://twitter.com/ATechAjay/status/1476800897074167808/photo/1)

![3_1476789651469864963](https://pbs.twimg.com/media/FH6cXRfVkAMsdSY.jpg)

![3_1476789702610984960](https://pbs.twimg.com/media/FH6caQAVIAAJm0O.png)

→ width of the 1st & 2nd columns = 100px

→ width of the 3rd column = 1fr

→ 1fr = Remaining space of the container.

8️⃣ Now, how to make the rows of the grid?

⇉ well, using the "grid-template-row" property!

→ Always use this property in the container of the grid. [pic.twitter.com/m8R6IU5e3q](https://twitter.com/ATechAjay/status/1476800908184879105/photo/1)

![3_1476790770799575041](https://pbs.twimg.com/media/FH6dYbUVgAEIOOf.png)

![3_1476790893382299651](https://pbs.twimg.com/media/FH6dfj-VcAM14by.jpg)

→ Height of the 1sr row = 50px

→ Height of the 2nd row = 100px

→ Height of the 3rd row = 1fr

9️⃣ Now, we have to position all boxes inside the grid container.

→ Remember this is the desired output. [pic.twitter.com/V4vJcHIEWG](https://twitter.com/ATechAjay/status/1476800918582542337/photo/1)

![3_1476792255616729090](https://pbs.twimg.com/media/FH6eu2sVQAIDsTP.jpg)

📌 BOX-1

→ Find the starting index or point of the box - 1 column-wise = 1

→ Find the ending index or point of the box - 1 column-wise = 3

→ Find the starting index or point of the box - 1 row-wise = 1

→ Find the ending index or point of the box - 1 row-wise = 2

📌 TWO MORE CSS PROPERTIES FOR POSITIONING THE CHILD ELEMENT INSIDE THE GRID CONTAINER.

→ grid-row-start
→ grid-row-end
→ grid-column-start
→ grid-column-end

⇉ These properties are always placed inside the child element of the grid container.

→ So, in BOX -1 

row start = 1
row end = 2

column-start = 1
column-end = 3

→ we can write like this in the child of the container.

→ well done, box-1 has been placed as required position. [pic.twitter.com/bofYZMVgrT](https://twitter.com/ATechAjay/status/1476800935187783680/photo/1)

![3_1476796042850934784](https://pbs.twimg.com/media/FH6iLTPVIAAHadF.jpg)

![3_1476796300607700992](https://pbs.twimg.com/media/FH6iaTdVQAA2lzZ.png)

📌Shorthand property!

→ This is boring to write too much stuff like:

grid-row-start
grid-row-end
grid-column-start
grid-column-end

→ You can be written as

👀 grid-row-start + grid-row-end = grid row

👀 grid-column-start + grid-column-end = grid column

→ grid-row : start / end

→ grid-column : start / end

It's too easy to write, isn't it?🥰

📌BOX-2

→ Find the starting index or point of the box -2 column-wise = 1

→ Find the ending index or point of the box - 2 column-wise = 2

→ Find the starting index or point of the box - 2 row-wise = 2

→ Find the ending index or point of the box - 2 row-wise = 3

💚Output👇 [pic.twitter.com/arPx5F9RWU](https://twitter.com/ATechAjay/status/1476800950320844803/photo/1)

![3_1476798762219569153](https://pbs.twimg.com/media/FH6kplrVgAEgGjo.png)

![3_1476798793173504002](https://pbs.twimg.com/media/FH6krY_VEAIDkuF.jpg)

📌BOX-3

→ Find the starting index or point of the box - 3 column-wise = 2

→ Find the ending index or point of the box - 3 column-wise = 3

→ Find the starting index or point of the box - 3 row-wise = 2

→ Find the ending index or point of the box - 3 row-wise = 3 [pic.twitter.com/fHBvU50iuo](https://twitter.com/ATechAjay/status/1476804170204139526/photo/1)

![3_1476802234742497283](https://pbs.twimg.com/media/FH6nzt1UYAMHLkE.jpg)

![3_1476802269416869890](https://pbs.twimg.com/media/FH6n1vAVUAIBvNn.png)

📌BOX-4

→ Find the starting index or point of the box -4 column-wise = 3

→ Find the ending index or point of the box - 4 column-wise = 4

→ Find the starting index or point of the box - 4 row-wise = 1

→ Find the ending index or point of the box - 4 row-wise = 4 [pic.twitter.com/Yo9TZkx6qh](https://twitter.com/ATechAjay/status/1476804177703542785/photo/1)

![3_1476802684820750339](https://pbs.twimg.com/media/FH6oN6gVgAMQv3f.png)

![3_1476802709592281094](https://pbs.twimg.com/media/FH6oPWyVEAY7DVh.jpg)

BOOM 💥

👉 All child elements are placed as requirements.

👉 Many boxes have do not need to use grid-row or grid-column properties, because it automatically places as required position.

👉 I hope you find it useful:)

[Thread link](https://twitter.com/ATechAjay/status/1476800839704453122)