---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of United Kingdom by Brandon V.

## Describe your program

The country I have designed for is the United Kingdom, it has took me about 1 week, it started off very easy. Blue background and 2 white stripes, then I was struggling because I didn't know how to make it accurate as the UK flag. As I progressed, I learned more about the flag. The name of the flag is called "Union Jack", it represents the 3 countries. England, Ireland and Scotland. Later on, I added 2 crosses which represents Scotland. Rotating it was difficult since it was a rectangle flag. I tried many attempts so it can look accurate as possible. It took me some time but I got the right rotation, I repeated with the red stripes, different rotation number although. I finished up, colors were off and there was a problem. Another student helped me with changing the colors to look more accurate. Replacing "blue" with "navy", "red" with "crimson". It looked better and completed, I was proud of doing this. I expect that my grade is a 4 because I had try my best to make a accurate version of the United Kingdom flag.

## Current output
* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

I asked another peer to change the colors to look more realistic, I also used images from the internet to give me references of the Union Jack flag.


## Explain your code.
-   Explain each argument in the code section.
-   Tell us how it functions independently and within the whole program.

* * *

```
(define size 300)
(define width 600)
(define height 300)
(define stripeheight (* height 2))
(define stripewidth (* height 0.22))
(define bluebackground (rectangle width height "solid" "navy"))
(define whitestripe_1 (rectangle stripeheight 100 "solid" "white"))
(define whitestripe_2 (rectangle 100 stripeheight "solid" "white"))
(define redstripe_1 (rectangle stripeheight stripewidth "solid" "crimson"))
(define redstripe_2 (rectangle stripewidth stripeheight "solid" "crimson"))
(define whitestripe_3 (rotate 27 (rectangle 700 60 "solid" "white")))
(define whitestripe_4 (rotate -27 (rectangle 700 60 "solid" "white")))
(define redstripe_3 (rotate -63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_4 (rotate -63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_5 (rotate 63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_6 (rotate 63 (rectangle 20 300 "solid" "crimson")))

```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
(define size 300)
(define width 600)
(define height 300)
(define stripeheight (* height 2))
(define stripewidth (* height 0.22))
(define bluebackground (rectangle width height "solid" "navy"))
(define whitestripe_1 (rectangle stripeheight 100 "solid" "white"))
(define whitestripe_2 (rectangle 100 stripeheight "solid" "white"))
(define redstripe_1 (rectangle stripeheight stripewidth "solid" "crimson"))
(define redstripe_2 (rectangle stripewidth stripeheight "solid" "crimson"))
(define whitestripe_3 (rotate 27 (rectangle 700 60 "solid" "white")))
(define whitestripe_4 (rotate -27 (rectangle 700 60 "solid" "white")))
(define redstripe_3 (rotate -63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_4 (rotate -63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_5 (rotate 63 (rectangle 20 300 "solid" "crimson")))
(define redstripe_6 (rotate 63 (rectangle 20 300 "solid" "crimson")))

(define UKflag  (put-image redstripe_1 300 150 (put-image redstripe_2 300 150 
(put-image whitestripe_1 300 150 (put-image redstripe_3 480 250 
(put-image redstripe_4 120 50 (put-image redstripe_5 525 50 
(put-image redstripe_6 100 237 (put-image whitestripe_4 300 150 
(put-image whitestripe_3 300 150 (put-image whitestripe_2 300 100  bluebackground)))))))))))
```
