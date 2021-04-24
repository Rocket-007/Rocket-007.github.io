---

### WeDraw

 
**A Mutiplayer Drawing Project**  
This is basically the second project i worked on for close to a month after i made [2d Blobs](/2dBlobs_page).  
Its actually one of my dream apps/game that I plan on continueing/recreating when I switch to an engine.  

This project was where I used another dope feature of Love2d, <b>"NETWORKING"</b>.  
Through the use of this feature and some really cool	libraries made by some guys at the forum,  

<i>I made a local multiplayer drawing project that would allow two or more devices  
to draw on a canvas while also previewing the intups and updated the canvas in real time.</i>  

I wont go in depth on how the code works but **BaSicALiy**  
<i>each pen stroke is generated form drawing lines continiously on the moving path  
while also storing those line cordinates in tables variables  
that would be read and sent through  
the local network to the server which will  
then send these packets to each client so that those clients would  
also draw the cordinates of all the other clients stoke input on the network.</i>  

I drew the assets myself <b>with my phone</b>(again), but the colour palletes were gotten from online sources  


A terrible accident happened that made me lose most of my files  
including the server file of the project but apart from that the code still works swell with the client tho.  


you can view the code repository [here](https://github.com/Rocket-007/WeDraw)  


<b>Below are some of the screenshots of the game s development and progress with description</b>  
<br>

The very early stage of the development where the ineffective dot drawing method was used<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/WeDraw_img1.jpg?raw=true)<br>


Using the 'sock' library for the local networking <br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/WeDraw_img3.png?raw=true)<br>


The long strip of values on the left shows the beginning and the ending of stroke gestures{I have to print them to screen because I use mobile}  
(false and true values respectively)- Will use this to create an undo feature someday,  
and the strip of values on the right are the coordinates of each line attached to a stoke gesture table
<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing9.png?raw=true)<br>


 Hard coding a prototype of a pinch zoom and pan code
<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing8.png?raw=true)<br>


The value strip on the right were used when I was to HARD CODE a PINCH ZOOM and PAN feature (tho most of the code is disabled now)
<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing12.png?raw=true)<br>
 


...And are some of my drawing atrocities too, to balance the mix :-D<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing3.png?raw=true)<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing16.png?raw=true)<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing14.png?raw=true)<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing13.png?raw=true)<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing19.png?raw=true)<br>
![alt text](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS/dummyDrawing23.png?raw=true)<br>
<i>there are afew more screenshots in the images source code directory at this [repo](https://github.com/Rocket-007/Rocket-007.github.io/blob/master/images/WeDraw_IMGS)<i/>

<br><br>









you can view the code repository [here](https://github.com/Rocket-007/WeDraw)
```lua
if isAwesome then
  return true
end
```
