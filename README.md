# jenny-javascript-variables

var monkeys = 5;


var jumpingOnTheBed = monkeys;


var status = " little monkeys jumping on the bed";


var bumpedHead = 0;


var d = jumpingOnTheBed + status;


//what is the value of d at this point? 5 little monkeys jumping on the bed


jumpingOnTheBed -= 1;


bumpedHead = monkeys-jumpingOnTheBed;


d = jumpingOnTheBed + status;


//what is the value of d at this point? 4 lmjotb


//what is the value of bumpedHead? 1


jumpingOnTheBed -= 1;


bumpedHead = monkeys-jumpingOnTheBed;


d = jumpingOnTheBed + status;

//what is the value of d at this point? 3 lmjotb


//what is the value of bumpedHead? 2

//How long can this go on? ∞, as far as the program is concerned, we can have a negitive number of little monkeys jumping on the bed (ghosts of little monkeys?) unless we tell the program to stop at 0 little monkeys on the bed, it will just continue to count negitive monkeys forever and ever (assumeing we loop the program) if we stop at zero, there are three more little monkeys something like  if monkeys == 0 break; I'm sure the syntax is wrong. but then again, we haven't introduced a loop, so the answer is either 3 more times, or as many as we like depending on whether or not we're willing to go into little monkey debt. 
