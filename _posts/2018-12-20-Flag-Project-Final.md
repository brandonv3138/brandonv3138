---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _United Kingdom_ by _Brandon V._

## Describe your program

-   What country did you design for? The country I have designed for is the United Kingdom.
-   What grade do you expect? The grade I expect is a 3 because there is a small error and it is hard to fix the issue.

<!--- Delete this comment and add your writing -->

## Current output
* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? _then delete this instruction_

<!--- Delete this comment and add your writing -->


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
Insert 10-15 line code section here _then delete this instruction_
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

(define UKflag  (put-image redstripe_1 300 150 (put-image redstripe_2 300 150 (put-image whitestripe_1 300 150 (put-image redstripe_3 480 250 (put-image redstripe_4 120 50 (put-image redstripe_5 525 50 (put-image redstripe_6 100 237 (put-image whitestripe_4 300 150 (put-image whitestripe_3 300 150 (put-image whitestripe_2 300 100  bluebackground)))))))))))
```
