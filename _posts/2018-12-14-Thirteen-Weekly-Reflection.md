---
layout: post
title: "Thirteen Weekly Reflection"
date: 2018-12-14
---
Currerently, I am still in progress in my flag project, it is the United Kingdom flag. Here is the code of the flag 
(define size 300)
(define width 600)
(define height 300)
(define stripeheight (* height 2))
(define stripewidth (* height 0.22))
(define bluebackground (rectangle width height "solid" "blue"))
(define whitestripe_1 (rectangle stripeheight 100 "solid" "white"))
(define whitestripe_2 (rectangle 100 stripeheight "solid" "white"))
(define redstripe_1 (rectangle stripeheight stripewidth "solid" "red"))
(define redstripe_2 (rectangle stripewidth stripeheight "solid" "red"))
(define whitestripe_3 (rotate 27 (rectangle 700 60 "solid" "white")))
(define whitestripe_4 (rotate -27 (rectangle 700 60 "solid" "white")))

(define UKflag  (put-image redstripe_1 300 150 (put-image redstripe_2 300 150 (put-image whitestripe_1 300 150 (put-image whitestripe_4 300 150 (put-image whitestripe_3 300 150 (put-image whitestripe_2 300 150 bluebackground)))))))

Running it would look something like this ![United Kingdom Flag in Progress](/images/Flagv2.png)
