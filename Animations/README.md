
#Animations
Explanation of how all this cool stuff works, so I don't forget. 

#####**Monkey Animation** 
*Animation and going through a lot of animation properties
*Show off how you can create animations using keyframes

#####**Logo**
* Logo created in Inkscape. Shapes rotate and animate the lines of the shape to appear as they rotate
* dashoffset - moves line from the current position, dasharray - controls length of the stroke or outline of shape
* keyFrames specifies animation code, animation begins in "from", and changes in "to"

#####**Signature** 
* Using offset in keyframes from 0 to full length, and animate in reverse to make it appear as if its being spawn

#####**Texture** 
* setting the mask as a url essentially acts as background or fill for the text

#####**Line - Animations**
* 4 examples of how animation and dash-offset function with different properties

#####**Social Icons Animation -Twitter, FB, Youtube **
* Transition - animation speed
* When you hover over the specified class of each icon, some css code executes on the different parts of each icon, creating a bunch of animations, pretty neat :D

#####**Gradient** 
* Defs element in SVG wraps the graphics
* Works like this: Linearly begins at 0% to 50% (length of object)  its going from #f8ED34 to #EA1180, then from 50-100% #EA1180 to #2E368F
* Apply fill = url(id of the gradient created in defs)

#####**Masking** 
* Everything placed into a mask by default if its black(fill) outside, it turns white inside the mask. So if its black outside, and turned white inside the mask, then it is revealed.
* SO we place a black object into the mask(circle) and when it hovers over the white objects(text and tube) they are revealed.  
* Outside(black) = Mask(white) hidden
* Outside(black) = Mask fill = black (black) - revealed
* Using animation, just have the circle move horizontally back and forth, pretty cool :D



