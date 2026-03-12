# README.md 
**By: Denis Moroz**
**-----------------------------------------------------------------------------------------------------------------**
## Test Case 1 

**Input:** 
*Nickel -> Nickel -> Nickel -> Nickel*

**Expected Output:**
*Vend LED turns on after the 4th nickel*

**Rationale:**
*With 4*5 cents, it gives 20 cents, which would meet the vending condition*
**-----------------------------------------------------------------------------------------------------------------**
## Test Case 2 

**Input:** 
*Dime -> Dime*

**Expected Output:**
*Vend LED turns on after the 2nd dime*

**Rationale:**
*10 cent + 10 cent = 20 cents, which would meet the vending condition*
**-----------------------------------------------------------------------------------------------------------------**
## Test Case 3 

**Input:** 
*Dime -> Nickel -> Dime*

**Expected Output:**
*Vend LED turns on after the 2nd dime*
*Change LED turns on as well*

**Rationale:**
*10 cents + 5 cents + 10 cents = 25 cents, which triggers vend and 5-cent change (which triggers the change led)*
**-----------------------------------------------------------------------------------------------------------------**
