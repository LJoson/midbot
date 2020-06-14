                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


https://www.thingiverse.com/thing:2587684
midTbot by bartdring is licensed under the Creative Commons - Attribution - Share Alike license.
http://creativecommons.org/licenses/by-sa/3.0/

# Summary

This is a simple pen drawing bot. It is like a T-Bot (AxiDraw), but I moved the motors to the middle. This has the advantage of making the machine a little smaller and way cooler, in my opinion. See the video. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/AB4bb1G7DIs" frameborder="0" allowfullscreen></iframe>

I made mine really small, so it can fit in my backpack, but it is easily scaled up by using longer rods and a longer belt. With that said, the X axis rods will start to get springy above 200mm long.

The firmware is a special version of Grbl. The only change is the spindle PWM is used to raise and lower the pen. It also has the CoreXY features of Grbl enabled.

You can use just about any CNC controller that can run 2 steppers and a servo, but I made a [custom controller](https://www.tindie.com/products/33366583/midtbot-controller/) that sits in the center and makes the wiring super clean. A limited qty are for sale on [Tindie](https://www.tindie.com/products/33366583/midtbot-controller/).



See my [blog post](http://www.buildlog.net/blog/2017/10/the-midtbot-a-new-flavor-of-h-bot/) blog post on this for further details.
Follow me on [Twitter](https://twitter.com/buildlog) for announcement.

# Print Settings

Printer Brand: LulzBot
Printer: TAZ 6
Resolution: Standard
Infill: 20%

Notes: 
The Pen carriage requires support

# BOM

## Besides the 3D printed parts you will need these parts

.
<table border='1' cellpadding='3'>
    <tr>
        <th>Part</th>
        <th>Qty</th>
        <th>Source</th>
    </tr>
    <tr>
        <td>NEMA 14 x 20mm lg Stepper Motor</td>
        <td>2</td>
       <td>Amazon, eBay, omc-stepperonline.com</td>
    </tr>
    <tr>
        <td>Pulley GT2 x 16 tooth</td>
        <td>2</td>
       <td>Amazon, eBay</td>
    </tr>
    <tr>
        <td>Smooth Idler 3mm Bore</td>
        <td>6</td>
       <td>Amazon, eBay</td>
    </tr>
    <tr>
        <td>Linear Bearing 6mm Double (LM6LUU)</td>
        <td>4</td>
       <td>Amazon, eBay</td>
    </tr>
    <tr>
        <td>Linear Bearing 3mm (LM3UU)</td>
        <td>4</td>
       <td>Amazon, eBay</td>
    </tr>
    <tr>
        <td>Linera Bearing Shaft 6mm  (length 150mm-300mm)</td>
        <td>4</td>
       <td>Amazon, eBay</td>
    </tr>
 <tr>
        <td>Linera Bearing Shaft 3mm dia. x 40mm</td>
        <td>2</td>
       <td>Amazon, eBay</td>
    </tr>
<tr>
        <td>Micro Hobby Servo</td>
        <td>1</td>
       <td>Amazon, eBay</td>
    </tr>
<tr>
        <td>GT2 Belt 6mm wide</td>
        <td>length * W * 2 + some</td>
       <td>Amazon, eBay</td>
    </tr>
<tr>
        <td>CNC Controller</td>
        <td>1</td>
       <td>Tindie, Amazon, eBay</td>
    </tr>
<tr>
        <td>Screw M3 x 8</td>
        <td>6</td>
       <td>McMaster</td>
    </tr>
<tr>
        <td>Screw M3 x 18</td>
        <td>2</td>
       <td>McMaster</td>
    </tr>
<tr>
        <td>Screw M3 x 25</td>
        <td>4</td>
       <td>McMaster</td>
    </tr>
<tr>
        <td>Screw M5 x 10</td>
        <td>1</td>
       <td>McMaster</td>
    </tr>
<tr>
        <td>Rubber Feet</td>
        <td>4</td>
       <td>Home Depot</td>
    </tr>
</table>

# Video

<iframe src="//www.youtube.com/embed/AB4bb1G7DIs" frameborder="0" allowfullscreen></iframe>