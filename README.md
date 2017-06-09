# misc-files
Miscellaneous files of my coding endeavours.

## List of files: ##

* greek-flag-final.arr: A small [Pyret](http://www.pyret.org/) program that draws the [old greek flag](https://en.wikipedia.org/wiki/List_of_Greek_flags#/media/File:Flag_of_Greece_(1822-1978).svg).
* greek-flag-function-final.arr: A variation of the above program, now operating as a function. Can be executed by writing greek-flag(desired unit size) e.g. greek-flag(100).
* greek-flag-final.rkt: The [Racket](http://racket-lang.org/) version of greek-flag-final.arr.
* car-drawing.rkt: Drawing of a simple car in [Racket](http://racket-lang.org/), from the Part I, exercise 5 of [the book "How to Design Programs"](http://www.ccs.neu.edu/home/matthias/HtDP2e/index.html).
* tree-drawing.rkt: Drawing of a simple tree in [Racket](http://racket-lang.org/), from the Part I, exercise 5 of [the book "How to Design Programs"](http://www.ccs.neu.edu/home/matthias/HtDP2e/index.html).
* small-banner.rkt: A small banner with text in [Racket](http://racket-lang.org/), using the text-font property.
* traffic-lights.rkt: A [Racket](http://racket-lang.org/) program that prints the next color on a traffic light, depending of which is the current one. Partially based on an example in the section 1.6 of Part I of [the book "How to Design Programs"](http://www.ccs.neu.edu/home/matthias/HtDP2e/index.html), which didn't flesh out the example enough, so that the changes would be realistic and correct. Can be executed simply by invoking the next-color variable (optionally, after modifying the current-color variable).
* traffic-lights.scm: The Scheme version of the above program. Can be executed simply by invoking the next-color variable (optionally, after modifying the current-color variable).
* traffic-lights.arr: The [Pyret](http://www.pyret.org/) version of the above program. Can be executed by writing next-color("name of current color") e.g. next-color("red").
* traffice-lights-function.rkt: traffic-lights.rkt as a function. Can be executed by writing (next-color name of current color) e.g. (next-color "green").
* mall.rkt: A small [Racket](http://racket-lang.org/) program, inspired by exercise 7 of the Part I of [the book "How to Design Programs"](http://www.ccs.neu.edu/home/matthias/HtDP2e/index.html). It implements an if statement for the following hypothetical scenario: "Suppose you want to decide whether today is an appropriate day to go to the mall. You go to the mall if it is either not sunny or if today is Friday (because that is when stores post new sales items)."(ibid). Can be executed simply by invoking the decision variable (optionally, after modifying the sunny and friday variables).
* mall.arr: The [Pyret](http://www.pyret.org/) version of the above small program. Can be executed by writing decision(boolean value of sunny, boolean value of friday) e.g. decision(false, true).
* mall.scm: The Scheme version of the above small program. Can be executed simply by invoking the decision variable (optionally, after modifying the sunny and friday variables).
* shapes.rkt: A small [Racket](http://racket-lang.org/) program, based on the exercise 8 of the Part I of [the book "How to Design Programs"](http://www.ccs.neu.edu/home/matthias/HtDP2e/index.html). Decides on whether a rectangle or square shape is tall, wide, or square depending on its width and height. Includes sample examples for all 3 cases. Can be executed simply by invoking the dimensions variable.
* shapes.arr: The [Pyret](http://www.pyret.org/) version of the above program. Can be executed by writing dimensions(desired shape) e.g. dimensions(rectangle(90,20,"outline","black")).
* hours-to-wages.arr: A small [Pyret](http://www.pyret.org/) program that, given a number of hours worked, computes the corresponding salary, taking in account the premium offered for overtime. Based on the exercises of section 3.5 of [the book "Programming and Programming languages"](http://papl.cs.brown.edu/2016/index.html). The variables are the rate per hour, the number of hours, and the overtime threshold. Can be executed by writing hours-to-wages-at-rate(rate, hours, overtime threshold) e.g. hours-to-wages-at-rate(10,45,40). Care has been taken to disallow setting the value of hours, rate and/or overtime threshold to zero and below.
* hours-to-wages.rkt: The [Racket](http://racket-lang.org/) version of the above program. Executed by invoking the compute variable, optionally after modifying the hours, rate, and overtime-threshold variables.
* hours-to-wages.scm: The Scheme version of the above program. Execute as above.
* hours-to-wages-mark2.rkt: An extensive rewrite of hours-to-wages.rkt, consolidating the if statements that verified whether the numbers were above zero, and adding a way to flag any non-numeric input. Executed by invoking the compute variable, optionally after modifying the hours, rate, and overtime-threshold variables.
* hours-to-wages-mark2-function.rkt: Similar to above, but now as a function, which also changes its way of execution. Can be executed by writing (compute rate hours overtime-threshold), substituting as necessary e.g. (compute 10 45 40).
* switching-computer.arr: A small [Pyret](http://www.pyret.org/) program that says to switch on the computer if there are new messages in the inbox. Based on any real-life case where one might want to do that. Can be executed by writing switching-computer(boolean value of new-messages) e.g. switching-computer(true).
* switching-computer.rkt: The [Racket](http://racket-lang.org/) version of the above program. Can be executed simply by typing switching-computer, optionally after setting the new-messages boolean variable as desired.
* switching-computer.scm: The Scheme version of the above program. Can be executed the same way as above.
* switching-computer-function.rkt: switching-computer.rkt as a function. Can be executed by writing (switching-computer new-messages boolean) e.g. (switching-computer #true).
* value.rkt: A small [Racket](http://racket-lang.org/) program, based on the exercise 9 of the Part I of [the book "How to Design Programs"](http://www.ccs.neu.edu/home/matthias/HtDP2e/index.html). Its premise is as follows: "Exercise 9. Add the following line to the definitions area of DrRacket: (define in "hello"). Then create an expression that converts whatever in represents to a number. For a string, it determines how long the string is; for an image, it uses the area; for a number, it decrements the number, unless it is already 0 or negative; for #true it uses 10 and for #false 20."(ibid). Only difference is the renaming of the in variable to something somewhat more expressive. Also given in the comments is a sample shape.
