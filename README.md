# Stopwatch
A simple Stopwatch developed using Vanilla JS and styled using CSS, which ***starts, stops and resets*** the timer.

The display timer remains set to '00:00:00:000' initially i.e. (HH:MM:SS:MS) and changes according to the button clicked.

# FEATURES & FUNCTIONALITY :

  1. ## START BUTTON : 
     <p> Starts the timer as soon as it gets clicked. </p>
     <p> The time gets computed (initial milliseconds are 10, the respective time units get incremented and addition of zero for single digit number is taken care of)  and displayed in the output section. </p>
     
  2. ## STOP BUTTON :
     <p> Pauses the time interval and sets the inner text of the START button as RESUME. </p>
     <p> On clicking RESUME the time begins again from the point of time where it was paused initially. </p>
     
  3.  ## RESET BUTTON : 
      Resets the timer and time interval , displays '00:00:00:000' in the output section and resets the inner text of the RESUME button to START button.  
