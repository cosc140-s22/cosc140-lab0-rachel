# COSC140 lab 0

## Lab feedback

 * How long did you spend on this lab?
I'm finishing the lab at 2:41pm, but I don't quite remember what time we started it in class. I only did questions 1 and 2, since I have a pretty bad headache right now, so I didn't really want to try the challenge problem.


 * What did you think about it?  What was good?  What could be improved?

Well, I found it difficult because of course I'm on Zoom and it's hard to get help/feedback from you and my peers. If I was in class, I think it would be much easier. However, I did find it a little frustrating, as I ended up just googling lots of things, but still don't feel as though I fully understand it. For instances, I'm still a bit confused on why I had to set position to absolute for the second problem, as I don't understand how that changed the 'button' from the whole line to just around the text. 

## Feedback

S

We should talk about the position: absolute thing, because for the button you shouldn't have to do that.  I'm not really sure you even need a positioning directive for the button; you can accomplish the look with a padding directive, a border-radius directive, and a background-color.  The padding directive just creates some "space" around the text.   Also important: if you make the tag be a `<span>` instead of `<div>` you can get rid of the positioning; the `<div>` tag will cause the element to consume the full "line", whereas a `<span>` (as an "inline" as opposed to a "block" element) will just be around the text and that's it.  Again, we can talk more about this in person.  


