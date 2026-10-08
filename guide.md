# merbl

<img width="684" height="744" alt="image" src="https://github.com/user-attachments/assets/d3239a8e-6b6e-4a39-b35c-60f66c4f04ad" />


Hii!!!! This is a guide on how to make your own 3D-Printed Marble Race!!!
This guide covers the CAD-ing process for the marble race.

You will learn how to CAD a marble race from scratch on Onshape.

### What is Onshape?
-   Onshape is a cloud-based CAD-ing software that runs completely on browser. So it is very versatile and beginner friendly.
-   To use onshape, just go to [this](cad.onshape.com) link and sign up for onshape. 

## Parts- 
i. Base \
ii. Tracks \
iii. Custom Tracks \
iv. Finishing Touches \

#### Before we start
The flow of a marble race is basically: \
**Plan → Sketch Path → Sweep The Path With Track Profile → Reinforce The Tracks → Add Supports → Text → Repeat**

You'll start by thinking how you want the marble to move and then actually turn that into tracks and stuff.

### You will be working with:
- **Sketches** : drawings  on a 2d plane
- **Sweep** : this actually makes the track, by extending a 2d sketch shape along a 3d path
- **Transform** : moves, rotates and scales the parts
- **Extrude** : just extends the specific 2d shape in a straight perpendicular line
- **Revolve** : sketch profile around an axis at a particular angle

alralr so lets actually get started

# 0. SETUP
if you haven't already, signup for onshape. after that, make a new document by clicking on the create → new document. name it anything you want

<img width="290" height="436" alt="image" src="https://github.com/user-attachments/assets/cc6a0ada-bf60-4530-b7d3-3e63c7855223" />

<img width="639" height="573" alt="image" src="https://github.com/user-attachments/assets/f220b6f7-bd3f-4f77-9118-7709c708daf2" />

this should be your screen:

<img width="1718" height="1028" alt="image" src="https://github.com/user-attachments/assets/d127d524-649f-47c8-9b28-dfafa6025b33" />

you have probably selected which type of movement you have, a list of those [here](https://cad.onshape.com/help/Content/View/view_navigation_and_the_view_cube.htm)

> #### Sketching on Onshape
> sketching in onshape is very basic, just click on the sketch tool on top-left corner and select a plane:
> 
> <img width="369" height="240" alt="image" src="https://github.com/user-attachments/assets/ef1a328a-7a5e-4e4d-a794-a8a501cd15d6" />
>
> <img width="1484" height="918" alt="image" src="https://github.com/user-attachments/assets/727b49ae-87f9-4713-a1ec-ed3a36605744" />


# I.BASE
the base is pretty simple, just sketch any type of base under 150x150x4 mm. for mine, i used a 180x180x3 rectangle. pick a plane, and sketch on it, and just make a rectangle, circle or any shape you want.

like these for example:

<img width="783" height="477" alt="image" src="https://github.com/user-attachments/assets/924b9061-a260-4e15-ab95-9caa16d4600d" />

<img width="578" height="361" alt="image" src="https://github.com/user-attachments/assets/d98f6611-b5f1-49f3-a2a4-68a83244441e" />

<img width="668" height="440" alt="image" src="https://github.com/user-attachments/assets/0227d86a-b239-44c2-8366-5474cded8545" />

im just tryna say you can make it whatever you want.

# II.TRACKS

tracks are made by first, having a path and then having a profile perpendicular to the start of the path.

first make a sketch:

<img width="336" height="143" alt="image" src="https://github.com/user-attachments/assets/4ede3e70-b0ef-49aa-a997-af48ff2b1930" />

> #### Sketches on Onshape:
> a detailed guide about sketches are [here](https://cad.onshape.com/help/Content/Sketch/sketch_tools.htm?TocPath=Part%20Studios%7CSketch%20Tools%7C_____0)


and place it on a plane:

<img width="1233" height="909" alt="image" src="https://github.com/user-attachments/assets/87157cb1-c3aa-46b6-949f-f946348fa509" />

and then draw any line shape like this:

<img width="1489" height="915" alt="image" src="https://github.com/user-attachments/assets/5ecbd4c4-1acd-45d7-a57a-eedc924309bf" />

> #### Shapes on Onshape:
> there are many types of shapes and line which are necessary for this tutorial, more info [here](https://cad.onshape.com/help/Content/Sketch/sketch_tools.htm?TocPath=Part%20Studios%7CSketch%20Tools%7C_____0)

after that, to edit the length of the line, you can press 'd' or this icon:

<img width="102" height="89" alt="image" src="https://github.com/user-attachments/assets/693888ab-4008-4ace-8270-c66b85ff54e7" />

and select the line, and click again. you can double click that constraint value to edit it.

all together:

https://github.com/user-attachments/assets/daba3795-5428-42c3-92bc-7ec49f04fc53

> also you can hide the planes and all from the left hand sided features panel:
> 
> <img width="470" height="958" alt="image" src="https://github.com/user-attachments/assets/579ace92-77ed-4079-9c1d-5943323e268f" />

then for the sweep profile, we have to first make a plane:

> #### Making Planes on Onshape:
> planes are a very important part of this tutorial, you have to use them as where the sketch is actually drawn. there are multiple ways of making a plane, [this](https://cad.onshape.com/help/Content/PartStudio/plane.htm) guide shows all the different types of planes and how they are made. 

use the plane tool and select the point normal plane, and after that select any point of the line and the line itself. you should see a plane being formed perpendicular to the line at the point you've selected

like this:
<img width="1499" height="920" alt="image" src="https://github.com/user-attachments/assets/e4ff8045-a1e9-4f48-b277-7475a201f7c3" />

and make another sketch on that. then were gnna make the profile that will sweep and actually make the tracks, here it means the track shape. so this is a very important step. anyways make the sketch.
so we are using marbles that are 16mm in diameter. so my tracks have 18mm inner diameter to have some tolerance and slack. my tracks outer diameter is 23mm, so with that the track is 2.5mm thick. heres my sketch of a track:

<img width="780" height="580" alt="image" src="https://github.com/user-attachments/assets/4399d854-a39f-4320-b818-03300145f793" />

> you can cut the lines using the trim tool (m)

<img width="469" height="375" alt="image" src="https://github.com/user-attachments/assets/a91ac7c2-0849-44c0-9bd0-170112f76b6b" />

then after that lets make the track by sweeping. search up sweep in the top right search bar. select the sketch profile we just made and then the line we drew.

<img width="621" height="322" alt="image" src="https://github.com/user-attachments/assets/77fe8f16-636b-4f57-8fc5-415cbed0d898" />

<img width="859" height="588" alt="image" src="https://github.com/user-attachments/assets/72227708-9469-497f-958c-826f58127694" />

and thats how to make a basic track! the next thing you learn is how to make advanced path sketches:

delete the part we just made. at the bottom left there should be a parts window, where you can see all the parts in the design. just right click on that part and click on delete.
then unhide your old sketches (the path and the profile) from the features tab. 
now we need to make a new plane. this time select line angle. then select the line, and specify the angle you want the plane to be at, this will make it more steeper/flatter. 

this is what I did:

<img width="598" height="345" alt="image" src="https://github.com/user-attachments/assets/71f4d0ff-4627-4e02-968d-031870117e68" />

after that, make a sketch on it. from the end point, you can start drawing your tilted track. use tools like splines, circles, tangent lines, etc. (you can refer to the onshape help guide)

this is what i did:

<img width="442" height="497" alt="image" src="https://github.com/user-attachments/assets/b27937eb-66d7-44e6-9b95-e27803f2a5aa" />

then make a composite curve out of it. search up 'Composite Curve' and select all the lines in the path:

<img width="590" height="503" alt="image" src="https://github.com/user-attachments/assets/099f09a6-4413-42ee-992e-5b492e494184" />

again, try sweeping. use the old profile you made and select the path we just made: 

this is what i got:

<img width="668" height="576" alt="image" src="https://github.com/user-attachments/assets/08383d70-7e0b-4711-8062-cc823cb7bfe2" />

and thats how to make paths! you just have to keep making new planes and sketch and planes and sketch and yeah. 

heres a vid based tutorial:

https://github.com/user-attachments/assets/f152d832-c026-4709-a9e1-cb710bd09956

# III. CUSTOM TRACKS
so we've learnt how to make normal tracks, but we can also add some different tracks. for example we can make a plinko track, or many others like these::

<img width="163" height="225" alt="image" src="https://github.com/user-attachments/assets/99bd1494-3b88-46dc-912f-49b84278d4f1" />

<img width="239" height="374" alt="image" src="https://github.com/user-attachments/assets/cc4cd793-5386-4514-ba8f-7f8a9ad2363e" />

<img width="441" height="231" alt="image" src="https://github.com/user-attachments/assets/30746cd2-4953-45b8-b7b6-a3471f353649" />

<img width="352" height="280" alt="image" src="https://github.com/user-attachments/assets/bc1be77b-cb6e-4610-8356-c35bbf144fcb" />

heres how to make some:

### Plinko Track
first create a sketch on any plane. then draw a straight line, make it 100mm long. 

<img width="816" height="132" alt="image" src="https://github.com/user-attachments/assets/2ed655d0-a016-4161-8fff-8f405dd9fc7b" />

then select aligned rectangle and draw a rectangle from one end of the line, after you draw it make it 3x3mm and the opposite point, make it coincident with the line like this:

<img width="340" height="457" alt="image" src="https://github.com/user-attachments/assets/b59e068c-cc46-413f-9367-57a61e22a69b" />

after that, draw a line from the opposite end that we just coincidented. this line should be 20mm long and on the earlier line we make:

<img width="693" height="535" alt="image" src="https://github.com/user-attachments/assets/53b796b5-d3be-4c25-b138-de0c954f88c1" />

repeat making the rectangle. this determines the width of the plinko. im just going to do this 1 more time.

<img width="679" height="255" alt="image" src="https://github.com/user-attachments/assets/0555daa2-3b47-4398-9b73-c94d5956e911" />

you can just trim whatevers left of the line.

okay now for making the plinko edges, first on either ends of the line, extend the square a bit, by 4mm. like this:

<img width="956" height="309" alt="image" src="https://github.com/user-attachments/assets/20202d64-c99c-46d4-a383-1c850eca49a0" />

now were gonna make more pegs above and below that. first, draw a line from the center of the middle peg to the top or bottom side that is 20mm long and is perpendicular to our first line:

<img width="1009" height="630" alt="image" src="https://github.com/user-attachments/assets/7e43a398-d252-4905-80bc-0324d4e89006" />

after that, draw another line there like this which is equal to the distance between the leftmost point and rightmost point. you can use the vertical tool for this, first select the new lines point and then the point just below that, which we want to make equal:

<img width="804" height="428" alt="image" src="https://github.com/user-attachments/assets/708fa3f8-829e-4d40-a6ca-dfbcb881791c" />


