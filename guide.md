# merbl
<img width="684" height="744" alt="image" src="https://github.com/user-attachments/assets/d3239a8e-6b6e-4a39-b35c-60f66c4f04ad" />


Hii!!!! This is a guide on how to make your own 3D-Printed Marble Race!!!
This guide covers the CAD-ing process for the marble race.

You will learn how to CAD a marble race from scratch on Onshape.

### What is Onshape?
-   Onshape is a cloud-based CAD-ing software that runs completely on browser. So it is very versatile and beginner friendly.
-   To use onshape, just go to [this](https://cad.onshape.com) link and sign up for onshape. 

## Parts- 
i. Base \
ii. Tracks \
iii. Custom Tracks 

#### Before we start
The flow of a marble race is basically: \
**Plan → Sketch Path → Sweep The Path With Track Profile → Reinforce The Tracks → Add Supports → Text → Repeat**

You'll start by thinking how you want the marble to move and then actually turn that into tracks and stuff.

### You will be working with:
- **Sketches** : drawings on a 2d plane
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

> #### Planes on Onshape:
> we sketch on planes, a plane is an invisible sheet of glass floating in 3D space. onshape has 3 basic planes, front, top and right.
> planes are a very important part of this tutorial, you have to use them as where the sketch is actually drawn. there are multiple ways of making a plane, [this](https://cad.onshape.com/help/Content/PartStudio/plane.htm) guide shows all the different types of planes and how they are made. 

> #### Sketching on Onshape
> a sketch is a flat 2d drawing on a plane, kinda like a thin sheet of paper but it has no thickness. its job is to make 2d outlines we can form into 3d shapes.
> after we make a sketch we use operations such as extrude, revolve or sweep to make it 3d.
> 
> sketching in onshape is very basic, just click on the sketch tool on top-left corner and select a plane:
> 
> <img width="369" height="240" alt="image" src="https://github.com/user-attachments/assets/ef1a328a-7a5e-4e4d-a794-a8a501cd15d6" />
>
> <img width="1484" height="918" alt="image" src="https://github.com/user-attachments/assets/727b49ae-87f9-4713-a1ec-ed3a36605744" />

# I.BASE
the base is pretty simple, just sketch any type of base under 150x150x4 mm. for mine, i used a 180x180x3 rectangle. pick a plane, and sketch on it, and just make a rectangle, circle or any shape you want. im gonna show you how to make a base that is a rectangle, and circle.
to make a plane, first make a sketch:
click on the sketch icon on the top-left corner:

<img width="369" height="240" alt="image" src="https://github.com/user-attachments/assets/ef1a328a-7a5e-4e4d-a794-a8a501cd15d6" />

then sketching needs a plane. click on any of the default planes of onshape (top, right, front):

<img width="1566" height="922" alt="image" src="https://github.com/user-attachments/assets/39ad72f1-4d21-4d75-8601-5cfd99964fed" />

after that, draw your base shape, you can use these tools:

#### rectangle
there are 2 types of rectangles on onshape - center rect, 2-point rect, and aligned rect. center rect allows you to determine the centre of the rectangle and one of the corner points. then there is a 2-point rect which just lets you determine 2 opposite corners of a rectangle. then aligned rectangle allows you to determine the angle of one point, and the length of both sides. 

in this tutorial we will use all three. the rectangle tools are here, use the drop down:

<img width="159" height="68" alt="image" src="https://github.com/user-attachments/assets/cb88b366-6792-4ce8-aaf3-8ac472d9c8c4" />

this is what they form:

<img width="355" height="375" alt="image" src="https://github.com/user-attachments/assets/f6e9b4d3-af07-4f36-91bc-b71d3f8a0b4a" />

(centre rect, 2-point rect, aligned rect)

to make the base, first select your rectangle tool, both center rect and corner rect work, if your confused just use centre rect tool. click anywhere to first mark the center. then just click again farther from that point to determine the corner. and yeah thats a rect! then we will use the dimension tool to determine its length and breadth

dimension tool is a sketching tool that sets the distance of 2 points, length of line, angle between 2 lines, or diameter of circle.

select the dimension tool:

<img width="188" height="119" alt="image" src="https://github.com/user-attachments/assets/24c699e9-63dd-4c9f-a6d4-9d8c3c1a7525" />

and click on any edge. then click again a little bit farther from it. then type in your desired value, for this tutorial use 100mm. if the size dialog goes away, double click the number you just got:

<img width="382" height="482" alt="image" src="https://github.com/user-attachments/assets/a9e258c8-c603-48f2-a146-9ed2b0aba014" />

then do the same thing for the other side and make it 100mm again:

<img width="362" height="405" alt="image" src="https://github.com/user-attachments/assets/46dd0ff2-3804-49dc-a2c3-35e5ffe3abbc" />

#### circle
circle just makes a perfect circle. there are 2 types of circles, center circle which is the same as center rectangle, it decides the centre of the circle and the distance from its circumference aka radius. then we have 3 point circle. it determines 3 points that should be on the circumference and forms a circle from that. this is how the circle tool dropdown thing looks like:

<img width="179" height="81" alt="image" src="https://github.com/user-attachments/assets/f66909d1-d532-4f27-a041-a4f83d3fea5b" />

were mainly gnna use the center tool. heres what each circle tool does:

<img width="666" height="427" alt="image" src="https://github.com/user-attachments/assets/abc108ab-24f1-479c-ad40-b88d63fef407" />

(center, 3-point)

just choose the center circle and draw a circle of any size:

<img width="363" height="411" alt="image" src="https://github.com/user-attachments/assets/e66ee847-39a1-4c9c-afdf-74c9f736e3af" />

then use the dimension tool, and select the edge of the circle. set the measurement to 75mm. like this:

<img width="641" height="601" alt="image" src="https://github.com/user-attachments/assets/9cee9d2b-aca3-4400-ac0a-10f6821e8d15" />

thats the circle tool!

> #### Sketches on Onshape:
> a detailed guide about sketches are [here](https://cad.onshape.com/help/Content/Sketch/sketch_tools.htm?TocPath=Part%20Studios%7CSketch%20Tools%7C_____0)

> #### Shapes on Onshape:
> there are many types of shapes and line which are necessary for this tutorial, more info [here](https://cad.onshape.com/help/Content/Sketch/sketch_tools.htm?TocPath=Part%20Studios%7CSketch%20Tools%7C_____0)

after making the shape, click the green check mark to finish sketch:

<img width="176" height="91" alt="image" src="https://github.com/user-attachments/assets/812fe321-348e-41f9-b27a-abb4381475bf" />

after that, we will be using the extrude tool to convert this sketch into an actual 3d shape. it pushes the sketch profiles (closed sketch shapes) straight out, perpendicular to the sketch plane, to give it thickness. 
select the extrude tool:

<img width="128" height="74" alt="image" src="https://github.com/user-attachments/assets/4d409a5f-a088-42dc-a78e-253c1faca5df" />

after you select the extrude tool, select the profile (closed shape) we made:

<img width="966" height="831" alt="image" src="https://github.com/user-attachments/assets/8e312ad6-0362-43df-bb44-b32be354b323" />

then the depth of the sketch (the actual thickness) make it 4mm:

<img width="256" height="84" alt="image" src="https://github.com/user-attachments/assets/cd5ddeff-6e3d-4624-a474-1e558bc2115c" />

and click on the green check:

<img width="80" height="73" alt="image" src="https://github.com/user-attachments/assets/f3aed8a0-4d23-4708-9435-673085d8ca9c" />


# II.TRACKS

tracks need two things - a path and a profile. a profile is a closed 2d sketch shape that were gnna be using for the sweep. a path is lines on a 2d plane that the sweep is actually gnna follow. first we will make a path. 

start by selecting the sketch tool:

<img width="336" height="143" alt="image" src="https://github.com/user-attachments/assets/4ede3e70-b0ef-49aa-a997-af48ff2b1930" />

and then click on any of the default onshape planes (top, right, front). it doesnt matter which of the 3 planes you are choosing:

<img width="1233" height="909" alt="image" src="https://github.com/user-attachments/assets/87157cb1-c3aa-46b6-949f-f946348fa509" />

and then select the line tool:

<img width="204" height="71" alt="image" src="https://github.com/user-attachments/assets/ae848891-56d1-4c93-b4ac-b1b7b1c013ef" />

and place a line. to place a line just click anywhere on the sketch plane and then it should form a line from where you clicked till your mouse pointer. then make sure the line is horizontal and click again. 

<img width="1489" height="915" alt="image" src="https://github.com/user-attachments/assets/5ecbd4c4-1acd-45d7-a57a-eedc924309bf" />

after that, we have to edit the length of the line using the dimension tool. the dimension tool sets distance between 2 points, length of line, angle between 2 lines, diameter of circle and more. you can press 'd' or this icon:

<img width="102" height="89" alt="image" src="https://github.com/user-attachments/assets/693888ab-4008-4ace-8270-c66b85ff54e7" />

and select the line, and click again, a little bit away from the line. 

<img width="434" height="110" alt="image" src="https://github.com/user-attachments/assets/c3a04f09-1bd1-441f-aa60-163dca77971c" />

it should bring up a window where you can put in a numerical value. im using 50mm. if the window goes away you can double click on the number to bring it back again.

<img width="436" height="154" alt="image" src="https://github.com/user-attachments/assets/a29fac1f-c663-493e-8b5b-72430b8b39ba" />

after that, click on the green checkmark to finish the sketch, make sure you get a line that is 50mm long.

<img width="77" height="96" alt="image" src="https://github.com/user-attachments/assets/c54c0145-7e30-4c43-af1b-c104b92b0a64" />

all together:

https://github.com/user-attachments/assets/daba3795-5428-42c3-92bc-7ec49f04fc53

> also you can hide the planes and sketches from the left hand sided features panel:
> the features panel shows you a timeline of features such as plane, extrude, revolve, etc and you can manage these operations (hide, delete, edit) from this window
> 
> <img width="470" height="958" alt="image" src="https://github.com/user-attachments/assets/579ace92-77ed-4079-9c1d-5943323e268f" />


use the plane tool:

<img width="108" height="97" alt="image" src="https://github.com/user-attachments/assets/db6cb0b7-2c11-4aa1-ac69-8b170d4c9513" />

it should bring up the planes window:

<img width="225" height="171" alt="image" src="https://github.com/user-attachments/assets/6fe3f2a5-754f-4293-ab2e-73f712512b9a" />

here the entities are stuff that we selected, such as points, lines and planes.

then select the point normal, from this dropdown:

<img width="270" height="52" alt="image" src="https://github.com/user-attachments/assets/050ca412-6469-4bd0-b42e-afee336d1c47" />

<img width="262" height="45" alt="image" src="https://github.com/user-attachments/assets/936763e9-bf1e-4b77-a860-1225c5b3020d" />

the point normal tool makes a plane, and the planes normal is the line. the plane is positioned at the point we have picked. so select the plane we just made, and a point on the end of the plane, these:

<img width="443" height="142" alt="image" src="https://github.com/user-attachments/assets/96b4b669-618e-401c-b6d3-151b3d4ccc0c" />

<img width="460" height="114" alt="image" src="https://github.com/user-attachments/assets/292b4b67-b707-4b38-8df7-7690dd59a530" />

select those and then it should give something like this:

<img width="631" height="711" alt="image" src="https://github.com/user-attachments/assets/0880c49f-9e07-43b7-a9fa-df948ebd147d" />

and your plane window should be like this:

<img width="224" height="183" alt="image" src="https://github.com/user-attachments/assets/cf67be79-7a5d-4468-ad00-c867f3411286" />

now were gnna make the profile that will sweep and actually make the tracks, here it means the track shape. so this is a very important step. make a sketch on the plane we just made:

<img width="175" height="64" alt="image" src="https://github.com/user-attachments/assets/0454716c-aa0c-4a8a-9092-9cc5cf4c7b38" />

<img width="1276" height="718" alt="image" src="https://github.com/user-attachments/assets/220e143a-814c-4c8e-9796-dc49d8ed3036" />


so we are using marbles that are 8mm in diameter. so my tracks have 9mm inner diameter to have some tolerance and slack. my tracks outer diameter is 14mm, so with that the track is 2.5mm thick. heres my sketch of a track:

first select the center point circle tool:

<img width="140" height="67" alt="image" src="https://github.com/user-attachments/assets/b3cf8f74-b6fa-4703-8b8e-bb8048656d8b" />

remember the line we had made at the start, in this view, that becomes a point. then draw the circles center at that point:

<img width="199" height="194" alt="image" src="https://github.com/user-attachments/assets/ba421299-68af-4e48-a978-a98947b84c29" />

then click anywhere:

<img width="462" height="506" alt="image" src="https://github.com/user-attachments/assets/c26aadad-ad69-4fd4-89fd-95338101e722" />

select the dimension tool then select the circles edge:

<img width="137" height="77" alt="image" src="https://github.com/user-attachments/assets/652e6187-777d-40c9-8e16-5b0a576fbcc6" />

and click anywhere. it should bring up a dialog like before. make this 9mm:

<img width="491" height="402" alt="image" src="https://github.com/user-attachments/assets/d0c28983-3216-4fb4-9eed-8586944f2996" />

(if the dialog dissapears just double click the number again)

then draw another circle with 14mm diamater, using the same process:

<img width="469" height="469" alt="image" src="https://github.com/user-attachments/assets/39093418-ef54-4aba-aeff-706a63f17edb" />

this gives us a thickness of 23-18 / 2 which is 2.5mm (i used the dimension tool to measure):

<img width="534" height="495" alt="image" src="https://github.com/user-attachments/assets/fd11e37a-296f-496c-8622-7be9e671c8cb" />

then make a horizontal line using the line tool:

<img width="107" height="75" alt="image" src="https://github.com/user-attachments/assets/000b705f-2208-457b-a7b0-27e5ca546aac" />

like this:

<img width="522" height="528" alt="image" src="https://github.com/user-attachments/assets/32756136-8287-4b42-b379-7cd8b95302c0" />

then make another line similar, but dont make it horizontal. like this:

<img width="501" height="521" alt="image" src="https://github.com/user-attachments/assets/484a23a5-3740-4860-a265-fb986f73d1dc" />

then again, use the dimension tool. this time we will be using it to set the angle between 2 lines. select the dimension tool:

<img width="109" height="77" alt="image" src="https://github.com/user-attachments/assets/a37dbf45-047e-477d-82d8-c2f6a8a0d005" />

select both lines:

<img width="562" height="489" alt="image" src="https://github.com/user-attachments/assets/869165fc-679e-428d-9fd2-dbb0ca3fdb18" />

then click again between the line, it brings up a dialog. this value determines the angle between these 2 lines:

<img width="597" height="510" alt="image" src="https://github.com/user-attachments/assets/f4296010-0d14-4096-8a88-21f33a63f98d" />

then set this to 20degrees:

<img width="505" height="518" alt="image" src="https://github.com/user-attachments/assets/556c2225-c606-4fbc-a45c-8148fee8f966" />

after that, we will use the mirror tool to replicate this on the other side. first draw a small line that goes either downwards or upwards like this:

<img width="515" height="512" alt="image" src="https://github.com/user-attachments/assets/c259f783-c431-40a9-bfdb-f23cf5509d3a" />

then select the mirror tool:

<img width="171" height="112" alt="image" src="https://github.com/user-attachments/assets/57ba327a-eb0c-4c97-9bbf-94f84ba0ce15" />

the mirror tool basically mirrors sketch lines along an axis. so it takes in a axis line first then objects to be mirrored. we made that small line to be the mirror axis. so select that line:

<img width="543" height="549" alt="image" src="https://github.com/user-attachments/assets/6e6f36cb-2728-4abf-9992-99c7cfb53165" />

then the other line that we angled:

<img width="505" height="491" alt="image" src="https://github.com/user-attachments/assets/7644d3aa-6932-4e37-8384-0e75272d9159" />

and it should form a replica:

<img width="564" height="515" alt="image" src="https://github.com/user-attachments/assets/9cae62a1-6157-4590-a7cf-4d7d8ba1b0d7" />

right now it looks really messy. so we will use the trim tool to tidy it up. select the trim tool:

<img width="173" height="83" alt="image" src="https://github.com/user-attachments/assets/349e8a0e-548d-4a60-9276-e2cf36ef6230" />

then cut out the useless lines by dragging your mouse on them. like this:

https://github.com/user-attachments/assets/caa1a6d4-f8b2-48d7-8523-cfd61a985c23

this should remain:

<img width="477" height="403" alt="image" src="https://github.com/user-attachments/assets/58354668-55e3-4de8-8c4a-f69eaa71ce5e" />

and thats the track profle! now we will lets make the track by sweeping.

first select the sweep tool in the top bar:

<img width="80" height="70" alt="image" src="https://github.com/user-attachments/assets/5fabbf62-f8c4-49e5-bc07-69b0d507a12d" />

the sweep tool takes lines and curves as a path and a profile. so first after selecting the sweep tool, lets select the profile we just made:

<img width="816" height="563" alt="image" src="https://github.com/user-attachments/assets/9d74d462-0e8b-4a07-87de-23f6ba1ace46" />

then click on the sweep path, in the sweep window:

<img width="418" height="145" alt="image" src="https://github.com/user-attachments/assets/8b22a75e-642c-41d2-b6f6-bf177f6d0a56" />

<img width="399" height="98" alt="image" src="https://github.com/user-attachments/assets/02cab674-6981-4a38-b8d4-2c5faf760a18" />

and click on that line:

<img width="565" height="559" alt="image" src="https://github.com/user-attachments/assets/a0b88923-fe72-4b39-a0b5-9ab05de2fe39" />

it should give this:

<img width="859" height="588" alt="image" src="https://github.com/user-attachments/assets/72227708-9469-497f-958c-826f58127694" />

click on the green tick to confirm:

<img width="99" height="95" alt="image" src="https://github.com/user-attachments/assets/4d6afbae-d0b7-4cb8-b32a-2f9227ea0357" />

and thats how to make a basic track! the next thing you learn is how to make advanced path sketches:

first we will delete the track we just made. to delete, there is a parts window which has a list of all our 3d parts in the bottom left, we can delete and hide stuff here:

<img width="357" height="355" alt="image" src="https://github.com/user-attachments/assets/9139d657-6fd1-428c-af58-98ac227f93be" />

to delete, just right click on the part, a window should pop up:

<img width="279" height="345" alt="image" src="https://github.com/user-attachments/assets/a950b24d-3554-41a4-a0a5-73311740ea8d" />

and click on delete. it should bring up a window like this:

<img width="214" height="134" alt="image" src="https://github.com/user-attachments/assets/0b807af3-6daf-4c50-98aa-8621a467fbb4" />

then just click the green checkmark:

<img width="74" height="58" alt="image" src="https://github.com/user-attachments/assets/a9996bc2-27ab-490b-9414-0b73540d776c" />

and the part gets deleted! to hide/show the part just click on this eye icon:

<img width="258" height="87" alt="image" src="https://github.com/user-attachments/assets/aa4a505d-149f-42e7-8043-0153d6aebd8c" />

were gnna make an advanced track now. first we will make a slanting plane, after that we will sketch on it.

to make a plane first select the plane tool:

<img width="128" height="83" alt="image" src="https://github.com/user-attachments/assets/5b1e3ad2-0a6a-4e7a-bddb-8d74f97b0605" />

and then select the line angle tool (use this dropdown):

<img width="266" height="37" alt="image" src="https://github.com/user-attachments/assets/2eff2d33-c21d-42c6-a06d-e3b80867766e" />

and set it to line angle:

<img width="269" height="60" alt="image" src="https://github.com/user-attachments/assets/7383f466-107d-4f6f-9f83-eedd96493fad" />

and select the line you have made from the sketch. we are angle-ing this so that the track leads downward, thus the ball goes down using gravity. 

to determine how much the plane should slant, edit the angle here:

<img width="276" height="193" alt="image" src="https://github.com/user-attachments/assets/9ef1e8c6-52ce-4b44-97b5-ee21ac82dbd1" />

i used 70degrees:

<img width="861" height="543" alt="image" src="https://github.com/user-attachments/assets/8aa5cd1c-3c7a-4dd1-aff9-24b4bdc25435" />

after that, make a sketch on it:

<img width="567" height="562" alt="image" src="https://github.com/user-attachments/assets/6475c50c-5f8b-4ba6-9da0-a159b64e022f" />

you can see the line that we made previously (earlier path for sweep). we have to continue building in front of it. so theres tools like spline, circle, lines, fillet etc we can use. ill show you how to use each.
so for the ball to actually travel, it needs to slope down. here, we tilted the plane to help create that slope. so if i draw lines that go down the plane, it will make the ball move. and if i draw it above it creates and upward slope. 

these are some techniques to help you:

### Line + Fillet
this method allows you to determine the strength of the curve and control direction really well while keeping the space taken small. so first you extend your existing line, then make another line that coincidents that, and then give an angle between those lines and then fillet those.
so first use the line tool and dimension tool:

<img width="596" height="519" alt="image" src="https://github.com/user-attachments/assets/e26e4d10-57c4-433c-8082-da359bb1e523" />

then draw another line to your specific angle. im using 40degrees here. again use line and dimension tool:

<img width="597" height="497" alt="image" src="https://github.com/user-attachments/assets/c15d5546-1aa8-4ccc-8c08-80a91ff5b128" />

then use the fillet tool. the fillet tool takes in 2 edges and the edges should coincident somewhere too. so select the fillet tool:

<img width="177" height="87" alt="image" src="https://github.com/user-attachments/assets/c36c211d-01ec-49fa-92b8-3fa1dcf95620" />

and select both the edges:

<img width="623" height="508" alt="image" src="https://github.com/user-attachments/assets/e743d833-7719-4c34-a6ce-4b52990f8996" />

and fillet and make it smooth as possible, this value has to be above 12 or it wont work (atleast for the profile we made, it will intersect itself and cause error):

<img width="542" height="452" alt="image" src="https://github.com/user-attachments/assets/579acb76-b8cf-487a-9a1c-8d00b03e7d16" />

and thats it. thats one way of making good curves. remember that the radius should be more than 12.

### Lines + Circles
this method is fairly simple. it has more control but takes more time. first we are going to use the center circle. first mark a centre. we will use the line tool to determine the radius, and the position of the circle.

select the line tool and draw a line from the end of the line:

<img width="588" height="547" alt="image" src="https://github.com/user-attachments/assets/6c6c0b4c-cedf-42fa-8ccf-784fa1778658" />

use the dimension tool to determine the length of the line. this will also be the radius of our circle. im using 20mm:

<img width="299" height="315" alt="image" src="https://github.com/user-attachments/assets/8334e47d-f2dd-4e0c-a10c-c97002bf1411" />

then use the dimension tool again to determine the angle:

<img width="592" height="538" alt="image" src="https://github.com/user-attachments/assets/77dc67ec-d3c3-4e70-b7bd-80df1ed35067" />

then make a center circle from that endpoint of the line till the line like this:

<img width="752" height="514" alt="image" src="https://github.com/user-attachments/assets/9452e666-6ced-4f79-bfa7-355aa0fce2b5" />






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

take 16.5mm from both sides and draw an aligned rectange towards the center, the same way we did before:

<img width="864" height="539" alt="image" src="https://github.com/user-attachments/assets/17aa0f7c-de45-4c22-95f2-ac16a67b0eac" />

yeah thats the sketch, okay also if u wanna extend above and below first select the mirror tool. then select either of the lines, then select the aligned rectangles and stuff of the other line:

<img width="808" height="653" alt="image" src="https://github.com/user-attachments/assets/dfff945a-b990-46aa-9e25-5576ffcc9535" />

keep doing that to determine how big you want your track to be. this is my track:

<img width="452" height="572" alt="image" src="https://github.com/user-attachments/assets/4186e0be-4f11-4ecf-9746-06d71254c3a8" />

after that, draw a rectangle:

<img width="398" height="579" alt="image" src="https://github.com/user-attachments/assets/85594914-6d89-4156-bea1-0057033520fc" />

extend the rectangles from the top and bottom so we have space for the marble:

<img width="430" height="725" alt="image" src="https://github.com/user-attachments/assets/5fee903d-d85f-4961-9c9b-1e2b8542c089" />

now we have to make an enterance. just make a line that is 17mm long on the top and bottom side, this determines where exactly your marble enters:

<img width="446" height="797" alt="image" src="https://github.com/user-attachments/assets/947c3c5a-140d-4533-a089-8eb0f66b6101" />

okay so now, we have to make the wall thickness and all, draw a center rectangle, and use the dimension tool to set the distance between the inner rects edges and the outer rects edges 3mm. 

<img width="432" height="672" alt="image" src="https://github.com/user-attachments/assets/e1195372-c52c-464d-ac34-0dede082a943" />

you can use trim to neaten it up a bit if u want, make rects for the enterance and the exit too. we have to extrude now. extrude every profile by 3mm, and the walls by 16mm totally:

<img width="906" height="717" alt="image" src="https://github.com/user-attachments/assets/6d949d5a-de0a-467c-8b97-bc61f136e080" />

finally, just chamfer all the corners, select the chamfer tool and select these corners:
chamfer them such that the marble wont be able to get stuck in a corner

<img width="462" height="499" alt="image" src="https://github.com/user-attachments/assets/ba01df9e-ec8c-465f-a0c2-bc81d8138d56" />

and thats the plinko track! for the entry of the marble you can either use that entrance or just make it so the end of the track is above the plinko so that the ball just falls in, same with the exit.


### Staircase Track

first make a sketch on a plane. then im using this for the steps:
use tools like the equal tool (makes any 2 lines equal), dimension tool, and also copy and paste, which is very easy to use. just drag on what u want to copy and paste, make sure its all selected and then ctrl + c, ctrl + v. 

<img width="640" height="558" alt="image" src="https://github.com/user-attachments/assets/2f6f2986-c3ad-4d70-a785-cc0a35bdd500" />

then draw a line from the start point of the steps to the end point. this will make the steps actually thick and strong. this is what ive done:

<img width="764" height="619" alt="image" src="https://github.com/user-attachments/assets/1b983f4f-40ab-4dcf-9311-a6873a7d9dda" />

then extrude these parts by 18mm:

<img width="686" height="556" alt="image" src="https://github.com/user-attachments/assets/b9d08f22-53ae-4b97-b4bc-b28170ecd638" />

after that, extrude all the parts, in the opposite direction by 3mm:

> to switch direction click this:
> <img width="134" height="90" alt="image" src="https://github.com/user-attachments/assets/ae43a4a4-eedf-4052-b2a1-c1a536fb4843" />

<img width="1167" height="816" alt="image" src="https://github.com/user-attachments/assets/74adb9c3-5922-4805-9791-a0305153f95d" />

then extrude those same parts, but this time tick the starting offset. make the offset the thickness of the track (18mm), and depth 3mm:

<img width="943" height="730" alt="image" src="https://github.com/user-attachments/assets/59595237-f50d-41b8-8d4d-71f2f454cfe6" />

finally this is what you should get!

<img width="593" height="473" alt="image" src="https://github.com/user-attachments/assets/abeb40d8-1132-4ef9-b52f-17dd25aaf860" />

you can edit the entrance and exit to your will/use. 

### Funnel
making a funnel is pretty easy, we are going to use revolve, fillet and  with the sketch. first start by making a sketch and and make a line. the length of the line doesnt really matter, we will be using this as an axis for revolve

after that, make another line that is 8.5mm far from the first line. also make sure that this like is parallel to the first line. the length of this line actually matters, as this is the drop of our marble. so you have to minimally make it 20mm. like this:

<img width="392" height="483" alt="image" src="https://github.com/user-attachments/assets/10849778-ecb1-4ee0-9bad-91e47f67af66" />

then make another line that is angled from the top. make this line at least 50mm long, this determines how many times the ball will revolute around the hole before falling into it. make it angled anywhere from 90 to 115 degrees, but you can do it max till 180. i recommend 95 to 115 degrees:

<img width="792" height="645" alt="image" src="https://github.com/user-attachments/assets/1418596d-2e3c-4401-9992-a3980f3d26c4" />

after that, fillet the edges (shift + f) or this:

<img width="196" height="101" alt="image" src="https://github.com/user-attachments/assets/dc79226b-46dd-401e-9f15-5c8a8d93d59e" />

this affects when the ball really falls in the hole. so im using 5mm here, it depends on your angle too:

<img width="747" height="631" alt="image" src="https://github.com/user-attachments/assets/11dc1695-c9f1-4f59-b350-1fc2f4632fa5" />

after that, offset it. what offset does is copy the same sketch/curve at a distance.
click o or this button to offset

<img width="167" height="66" alt="image" src="https://github.com/user-attachments/assets/9623a050-6410-4935-bd8f-9ce07e96665d" />

so select offset and then the lines we made. this determines the thickness of the wall. so im offsetting it by 3mm. make sure it gets offset on the side opposite to the first line:

<img width="869" height="625" alt="image" src="https://github.com/user-attachments/assets/66f0925a-480f-47db-b99a-dd20e706146f" />

you can fillet it again to make it look better:

<img width="552" height="534" alt="image" src="https://github.com/user-attachments/assets/a054aeb2-674f-4be6-be38-30263e073b01" />

after that, draw a line at the bottom that connects the offset line and the base line:

<img width="364" height="414" alt="image" src="https://github.com/user-attachments/assets/8c25a4eb-ebe7-4245-b079-5f4a6afd4c3f" />

then we need to edit the edge of the funnel. this makes sure the marble doesnt just fall off. first go here and make a corner-point rectangle:

<img width="437" height="566" alt="image" src="https://github.com/user-attachments/assets/db6da3a7-eebf-495a-9eae-48e328b2414a" />

then extend the other line so it intersects this rectangle:

<img width="360" height="525" alt="image" src="https://github.com/user-attachments/assets/7b17bf3b-224b-497e-a55f-e11f9588f3e0" />

after that, specify the rectangles dimension. using the dimension tool, make the thickness of the rectangle atleast 3mm and the height by 12:

<img width="387" height="407" alt="image" src="https://github.com/user-attachments/assets/8ddb5d70-3722-4f85-861f-b991d16add59" />

then extend the first line like this:

<img width="478" height="677" alt="image" src="https://github.com/user-attachments/assets/8f79199b-7458-4f66-b8f7-1ac00abd7caa" />

and cut off the other part of the rect:

<img width="393" height="561" alt="image" src="https://github.com/user-attachments/assets/64579f63-bf25-4681-92f6-41f2d979a463" />

after that, the sketch is finished. you can tidy it up a bit by trim tool. then select the revolve tool, select the profiles we made and then the first ever line we made as axis. like this:

<img width="738" height="634" alt="image" src="https://github.com/user-attachments/assets/3c45cc02-e3e3-4904-bc4f-8dddac0dcf1c" />

then, you can fillet these edges to make it look better. im filleting it by 13.5mm:

<img width="586" height="360" alt="image" src="https://github.com/user-attachments/assets/098bee83-d307-43d1-876a-a672fcdacdde" />

fillet this bottom thing too, im filleting it by 1mm:

<img width="602" height="373" alt="image" src="https://github.com/user-attachments/assets/512f06fa-9646-43fd-ac51-3b71a1eafc24" />

and were done! this is what you should get:

<img width="540" height="330" alt="image" src="https://github.com/user-attachments/assets/01b47066-dbde-4ae9-aa9e-c3528f8e41db" />

## Finishing
so that is how you make basic parts of a marble track. its up to you how you want to integrate these. you can make ideas of your own too, heres some i thought of-
- make it modular!
- add a motor and an archimedes screw to bring the motor back to the beginning!
- make your own custom track!
etcetc. its up to you and your creativity. 

after you do make the marble track, dont add supports. we are gnna use the generated supports from the slicer. 

heres a list of stuff to ~~steal~~ get inspired from!:

<img width="1657" height="1486" alt="image" src="https://github.com/user-attachments/assets/2f73be81-49be-4766-aa8c-e9b8bf3ef34c" />

<img width="213" height="453" alt="image" src="https://github.com/user-attachments/assets/1da0796c-e24c-48c4-a158-e71e11a5eb9f" />

<img width="426" height="457" alt="image" src="https://github.com/user-attachments/assets/8ee0e6e4-3400-4f17-895c-7cf1ddb9c5be" />

