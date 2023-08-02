﻿# Medisage_Assignment

Create a Countdown Timer component in React.js

Component should accept 3 props

1. Time in sec.
2. Timer Direction (clockwise or anti-clockwise) 3. Callback function
Note, the component should be reusable and can be able to render multiple components in single page with different props ie

Eg.

1. if i pass time 30 that is in seconds and direction clockwise than the timer should go from 0
to 30 and then it should stop and trigger the callback

Component should look something like this

<Countdown Timer time-(30) direction=(clockwise) callback=(()->console.log("Timer Completed"))>>

2. fi pass time 30 that is in seconds and direction anti-clockwise than the timer should go from 30 to 0 and then it should stop and trigger the callback
Component should look something like this

<Countdown Timer times(30) direction=(anti-clockwise) callback=(()>console.log("Timer Completed'))/>
