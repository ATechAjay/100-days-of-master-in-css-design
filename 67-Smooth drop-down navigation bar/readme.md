---
author: "Ajay Yadav ๐ฏ"
handle: "@ATechAjay"
source: "https://twitter.com/ATechAjay/status/1485523443194146818"
date: "January 24, 2022 12:02 PM"
likes: 17
retweets: 2
replies: 8
---
![ATechAjay](https://pbs.twimg.com/profile_images/1485567675111981057/mLsrcZdB_normal.jpg)
Ajay Yadav ๐ฏ ([@ATechAjay](https://twitter.com/ATechAjay)) - January 24, 2022 12:02 PM

๐ Day 6๏ธโฃ7๏ธโฃ / 1๏ธโฃ0๏ธโฃ0๏ธโฃ Master in CSS Design series!

๐ฅ Today we are going to learn CSS selectors.

โ Selectors are one of the tricky concepts in CSS.

โ There are many ways to select an HTML element in CSS, using a CSS selector.

๐ The BEST thread!

[#webdev](https://twitter.com/hashtag/webdev) 

Let me explain!๐งต๐ [pic.twitter.com/rTKyK5fn15](https://twitter.com/ATechAjay/status/1485523443194146818/photo/1)

![3_1485487949857067009](https://pbs.twimg.com/media/FJ2Da4FakAEFYS_.jpg)

โ Why should we learn CSS selectors in our design series?

๐ค I think,

- If you want to become a good CSS developer, you must have to know CSS selectors.

- CSS selectors are many types, so you can be stuck during writing CSS code.

๐ I have one question for you!

๐ค What is the difference between the Descendent selector and child selectors?

๐ Notation
Descendent selector = {space}
child selectors = {>}

๐ค What are CSS selectors or what is the use of the CSS selectors?

โ CSS selector is used to select an HTML element, which we design that HTML element.

๐ CSS selectors are several types, we can divide them into 5 categories for our convenience.

1๏ธโฃ Combinator(Combination) Selector
2๏ธโฃ Simple Selector
3๏ธโฃ Pseudo element Selector(::)
4๏ธโฃ Pseudo class Selector(:)
5๏ธโฃ Attribute Selector

But in this thread, we are going to learn, 

1๏ธโฃ Combinator(Combination) Selector and its type.

โ Other selectors are going to learn in the next thread.

Let's start...

1๏ธโฃ Combinator(Combination) Selector

๐คSo, what is a combinator selector?

โ They combine other selectors in order to select HTML elements.

โ Or, these selectors are made up of two or more selectors.

โ Or, Combine means a ๐บ๐ถ๐ of 2 or more selectors.

hope you got my point

๐ Combinator selectors further can be divided into 4 parts.

๐ญ. Descendant combinator selector("space")

๐ฎ. Child combinator selector(>)

๐ฏ. Adjacent sibling combinator selector(+)

๐ฐ. General sibling combinator selector(~)

๐ญ. Descendant combinator selector("space")

โ It selects each and every HTML element of a defined or specified element.

โ Or, it selects all HTML elements, which is the descendant of a defined element.

โ Or, Descendant means "๐๐ฒ๐ฒ๐ฑ" or "๐ฐ๐ต๐ถ๐น๐ฑ" of the parent.

โ Here you can see, all p elements inside the div element have been selected. [pic.twitter.com/KXPhcFdvnY](https://twitter.com/ATechAjay/status/1485523475607736321/photo/1)

![3_1485502344582561792](https://pbs.twimg.com/media/FJ2QgwnagAAoTxx.jpg)

![3_1485502536983650306](https://pbs.twimg.com/media/FJ2Qr9XaIAIxSrN.jpg)

๐ Codepen link of Descendant combinator selector("space")

[codepen.io/atechajay/pen/โฆ](https://codepen.io/atechajay/pen/GROKjKW?editors=1100)

๐ฎ. Child combinator selector(>):

โ It is used to select the "direct child" element of the specified element.

โ Or, It selects only direct children, not indirect.

โ Or, not grand chid or great grande child.

see here!

โ Selects all p elements inside the div element.

โ Selects all p elements inside the section element. [pic.twitter.com/sVkHYDl8wX](https://twitter.com/ATechAjay/status/1485523488765263873/photo/1)

![3_1485508557084987394](https://pbs.twimg.com/media/FJ2WKX_akAIq_yn.jpg)

![3_1485508649925890051](https://pbs.twimg.com/media/FJ2WPx2aUAMegVJ.jpg)

๐ Codepen link of Child combinator selector(>)

[codepen.io/atechajay/pen/โฆ](https://codepen.io/atechajay/pen/bGYbwEv)

๐ Now, What is the difference between descendant and child selector?

๐ Descendant selector:

โ Selects all HTML element, either direct child, grandchild, great-grandchild.

โ Or, Select nested elements.

โ Or, selects direct and indirect elements of the specified element.

๐ Child selector(>)

โ It selects on a direct child element.

โ Suppose you are a father and have a son, Here, a son is your direct child of yours.

โ but, It does not select your daughter's son, because your daughter's son is not a direct child of yours.๐

Hope...my point

๐ฏ. Adjacent sibling combinator selector(+):

โ It selects the "next" element of the specified element.

โ Or, Selects "Very close" element of the defined selector, which is the first one.

โ Or, it selects only one element.

โ Or, it selects only the first element.

โ You can see here, it selects only the nearest / first element of the "div" element. [pic.twitter.com/PPtWeP7Ac3](https://twitter.com/ATechAjay/status/1485526884125659138/photo/1)

![3_1485526170779385857](https://pbs.twimg.com/media/FJ2mLoHaAAEepBh.jpg)

![3_1485526238651625473](https://pbs.twimg.com/media/FJ2mPk9aMAEryjP.jpg)

๐ codepen link of Adjacent sibling combinator selector(+):

[codepen.io/atechajay/pen/โฆ](https://codepen.io/atechajay/pen/JjOPROX)

๐ฐ. General sibling combinator selector(~):

โ It selects all elements "next" to the specified element.

โ Or, opposite to the adjacent selector.

โ Very simple, its selects all HTML elements of the defined element.

โ You can see here that all elements have been selected, which are nearest to the specified element. [pic.twitter.com/5fjYm8x0uR](https://twitter.com/ATechAjay/status/1485526897685856259/photo/1)

![3_1485526467270574081](https://pbs.twimg.com/media/FJ2mc4oagAEx1PA.jpg)

![3_1485526538259144706](https://pbs.twimg.com/media/FJ2mhBFaIAIb2v5.jpg)

๐ codepen link of General sibling combinator selector(~)

[codepen.io/atechajay/pen/โฆ](https://codepen.io/atechajay/pen/yLPBaxm)

[Thread link](https://twitter.com/ATechAjay/status/1485523443194146818)