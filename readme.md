## SansaGrid
**Super light-weight grid system made with sass**

### What?

**SansaGrid** came from the need of making a custom website thus there was a need for a custom grid tailored to my needs. This grid is inspired and partially based on a tutorial **Seb Kay** made at inspirationalpixels.com 
***"How to Create a 12 Column Grid System with Sass"***

*Disclaimer:This is a work in progress and its not production-grade code.*

### Getting Started ###

You can start using SansaGrid by implementing the **grid.css** into your **index.html**

    <link rel="stylesheet" href="/*PATH*/grid.css"/>

*change *PATH* with the path where grid.css is located*

Now all you have to do is use a wrapper for the columns named *row* like this

    <div class="row">
    	Columns in here
    </div>

since SansaGrid is a **12-column** grid you have a variety of column classes from 1-12 like this

    <div class="col-1"> through <div class="col-12">

*Also you have the ability to center your columns using **offsets** which are basically a percentage value on margin-left property.*

### Basic Example & Usage###

Below you can see a basic usage example where two columns of size 4 are centered in the screen using offset class

    <div class="row">
	    <div class="col-4 offset-2">col-4</div>
	    <div class="col-4">col-4</div>
    </div>

### Attention

The columns themselves are responsive because they are based off percentage values but for smaller devices its not quite ideal. Mobile-friendly responsiveness is in my to-do list.

### Credits TO

Seb Kay - http://sebkay.com/