# README.md 
**By: Denis Moroz**
**-----------------------------**
## Test Case 1 

**Input:** 
*Nickel -> Nickel -> Nickel -> Nickel*

**Expected Output:**
*Vend LED turns on after the 4th nickel*

**Rationale:**
*With 4*5 cents, it gives 20 cents, which would meet the vending condition*
**----------------------------------------------------------------------------**
## Test Case 2 

**Input:** 
*Dime -> Dime*

**Expected Output:**
*Vend LED turns on after the 2nd dime*

**Rationale:**
*10 cent + 10 cent = 20 cents, which would meet the vending condition*
**----------------------------------------------------------------------------**
## Test Case 3 

**Input:** 
*Dime -> Nickel -> Dime*

**Expected Output:**
*Vend LED turns on after the 2nd dime*
*Change LED turns on as well*

**Rationale:**
*10 cents + 5 cents + 10 cents = 25 cents, which triggers vend and 5-cent change (which triggers the change led)*
**-----------------------------------------------------------------------------------------------------------------**
## Reflection

**Challenging part of the Assignment**
*Quite simply, I don't want to do this ever again. It took a good while to figure out what to do (half a day!), and even then, I did it wrong twice (yep, not once, but twice!), which I restarted from scratch because it no longer looked like a circuit but a pair of wired headphones that have been entangled with multiple other wired headphones in a teenager's drawer (backtracking wasn't an option). Anyways, outside the coping, the hard part was definitely the brainstorming and figuring out what to do. But after drawing out the tables and the FSM, it looked possible, and of course, trial and error. Overall, I give this assignment: 10/10 for helping one understand how to use D flip-flops and ticking, but a -10/10 for sanity. 
