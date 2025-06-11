# cs2050-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [CS2050 Lab 2 Solved](https://mantutor.com/product/cs2050-introduction-solved-5/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112848&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2050 Lab 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
In this lab you are asked to create two classes. The first one is called LightBulb and models a light bulb with a brightness in lumens (an integer value). A LightBulb object can be turned ON and OFF. The second class is called DimmableLightBulb and it should be specialized from LightBulb with an added feature: a dimmer to control the percentage of lumens emitted by the light. Complete the lab by finishing an application that allows interaction with a light bulb.

The LightBulb Class

Define a constructor that accepts the amount of lumens. If the informed value is smaller/greater than the minimum/maximum accepted value, have it default to the minimum/maximum accepted value, respectively. A light bulb should always be created in the OFF state. Add basic getter/setter methods like: isOn, turnOn, turnOff, and getLumens.

The DimmableLightBulb Class

As mentioned previously, the DimmableLightBulb class should be a specialization from LightBulb with an extra feature: an integer from 0 to 100 that defines the dimmer value. Define a constructor in DimmableLightBulb that accepts the amount of lumens. Use super to call the parentâ€™s constructor, forwarding the lumens informed value to it. Set the initial value for the dimmer to its maximum possible value. Add basic getter/setter methods like: getDimmer and setDimmer. Make sure setDimmer prevents the user to set a dimmer value that is invalid.

The RoomFrame Class

The RoomFrame class allows users to pick which type of light bulb to be created: the basic one or the dimmable one. Users also have the ability to choose the value for the amount of lumens.

The GUI is implemented for you and it has an ON and OFF switch to control the light. If the chosen light is dimmable, the GUI will also display a slider for the dimmer. The figure below shows the GUI for the two types of light. Follow the to doâ€™s embedded in the code to complete the lab. Hint: use the instanceof operator to determine if an object is of a particular type: LightBulb or DimmableLightBulb.

The actual lumens of a dimmable light bulb is adjusted based on the dimmer (a percent from 0-100). For example, if the factory’s lumen of a

dimmable light bulb is 1300 but the dimmer is set to 50, then the actual lumen displayed by the light bulb is adjusted to 50% of 1300 or 650 lumens.

Rubric

+1 TODO #1 (LightBulb class) +1 TODO #2 (DimmableLightBulb class) +1 TODO #3 (ON/OFF control) +1 TODO #4 (dimmer control) +1

TODO #5 (main)
