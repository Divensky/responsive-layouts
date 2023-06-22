
**What I found when I watched a solution to this challenge **

I missed an opportunity to use header and main tags. 

Missed a margin-top (did not notice it was different from the design) and missed an opportunity to use section-header for the header to avoid repeating the code for two headers; however, I did separate the color and other properties of the section-header in different tags to allow for re-use. 

And I used CSS custom properties which he is not showing, I assume he does not want to make it more complex; these help avoid repetition of the width in various sections. They also reduce the amount of code needed because instead of width + max-width I have one line with --width = max (value-in-percentages, max-value). 