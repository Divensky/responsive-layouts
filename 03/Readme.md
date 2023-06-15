#challenge03

This is the third challenge from the Conquering Responsive Layouts course (https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts). 

It is based on a Figma file https://www.figma.com/file/hNpeusGLC0MQDlcIoJztLr/conquer-responsive-layout-week-1-final-challenge-(Copy)?type=design. 

I wanted to note down about it that this was my second experience of making an HTML/CSS file based on a Figma file from scratch. The first time I did it, I had horrible time at first. I spent nearly a week as I was figuring out all of the fundamentals: Figma itself, Emmet, connecting fonts, etc. etc. I put together a checklist as I did this because the steps seemed many and complicated. 

This time I did not need any checklist. I opened a blank file, typed "!" in Emmet, and went on from there. It was easy and relaxed. I felt I knew what I was doing and where I needed to look at each step. Sure I did not remember some of the CSS commands by heart, but I knew what they should be like and rapidly looked them up (in phind.com which works better than Google in my experience). 

I did not time the actual coding part but the entire assignment took me two hours: watching the assignment video (at least twice), downloading the relevant files, coding, checking the results in the dev tools and making any needed corrections, and then watching the video with Kevin's solution to the challenge. 

What I missed was styling the :hover, :focus, :active button styles. This was not required but I should have thought of it as a natural part of styling any button. 

He also set box-sizing: border-box as the default, I did not, but I guess I should keep this in mind as a preferred option. It did not matter for this project though. 

What I did differently than Kevin was I had one less div around the text. He set the text box to take 80% of the screen and then took 50% of that with the inner div. Instead, I set the padding-left to be 9% of the screen and then took the same 50%. I think the resulting output is the same with less code. What I missed was setting a max-width so the text does not grow too wide on very wide screens. I have now corrected that. I now put 50% as "width" instead of "max-width" and set the max-width in "ch" to allow for the same amount of text as in the design. With this, I still accomplish the same result with less code. 

I am happy he's using BEM, as I was taught to use that too and used it in my code. 

I also duplicated some of the color details according to Figma file (including colors of the text and the button), which he did not seem to do. 

I had to make adjustments for the browser styles which were adding margins between my paragraphs. Kevin did not seem to have done that and I wonder why. 

I think that's all the key differences. I will progress on the course to see if any other differences have an explanation.  


