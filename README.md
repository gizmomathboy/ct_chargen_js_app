# Character Generator for Classic Traveller

I think a "simple" javascript app should work.

This is also a way for me to get better at using jQuery/Javascript

The rough process goes something like this:

1. Generate states aka UPP
2. Select a service to try and enlist in
3. If enlistment is not successful then get drafted into one
4. Check to see if you survive the 4 year term
5. If the service has ranks check for commission. Skip if already have a commission
6. If you have a commission check for promotion
7. Select a skills table to roll on. Initial term of service you get 2 skills rolls.
  * Scouts always get 2 skill rolls per term
  * for each commission or promotion in a term another skill roll is done
8. Decide to whether to reenlist or muster out
  * reenlist roll is always done. On a 12 you are forced to reenlist
  * forced to muster out after the 7th term unless you are forced to reenlist
  * if this is the end of term 4 then aging effects are determined
  * if reenlisting go to step 4
9. Mustering out has similar complexity and not describing here just yet
