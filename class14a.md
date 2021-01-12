# read 14 a

## CSS 
**transform syntax:**
The actual syntax for the transform property is quite simple, including the transform property followed by the value

* 2D Transforms
1. 2D rotate :The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. example :transform: rotate(20deg).

2. 2D scale: Using the scale value within the transform property allows you to change the appeared size of an element.he default scale value is 1, therefore any value between .99 and .01.Example :transform: scale(.75).or larger  transform: scale(1.25)

3. 2D Translate:The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
example :transform: translate(-10px, 25%).

4. 2D Skew: is used to distort elements on the horizontal axis, vertical axis, or both.
example: transform: skewX(5deg)

* we can combine the transformer togther, example : transform: rotate(25deg) scale(.75);


**Here are 8 really simple effects that will add life to your UI and smiles to your users’ faces.by hover**
 1. fade in :Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action. example :opacity:0.5;

 2.  Change color: Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them.example:color:hover  background:#53a7ea;

 3. Grow & Shrink:To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.

4. Rotate elements:ive your div the class “rotate” and add the following to your CSS:
    -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);

5. Square to circle:A really popular effect at the moment is transitioning a square element into a round one, and vice versa.example: border-radius:50%

6.  3D shadow:This effect is achieved by adding a box shadow, and then moving the element on the x axis using the transform and translate properties so that it appears to grow out of the screen.

7. swing: We can also create highly complex animations using @keyframes, animation and animation-iteration.example:hover
{
        -webkit-animation: swing 1s ease;
        animation: swing 1s ease;
        -webkit-animation-iteration-count: 1;
        animation-iteration-count: 1;
}

8.  Inset border:We could fix that problem using box sizing, but a far simpler solution is the transition in a border using an inset box shadow.example:box-shadow: inset 0 0 0 25px #53a7ea;

**Key frames rule** 
The animation is created by gradually changing from one set of CSS styles to anotherDuring the animation, you can change the set of CSS styles many times.
