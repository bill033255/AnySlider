# AnySlider
AnySlider - Responsive image, content, video slider

AnySlider is FREE, it helps you to create any nice slider in seconds. It is a jquery plugin turning any Dom elements into slide easily. It does not require css markup, it has only small javascript file 32kb.

<a href="http://anyslider.com"><h3>Demo & Documents</h3></a>
Step 1: Include jquery plugin (you can include jquery directly from google)

<script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>
Step 2: Include anyslider plugin

<script src="/yourpath/anyslider.js"></script>
Step 3: HTML markup

<div class="anyslider">
    <img src="/images/image1.jpg" />
    <img src="/images/image2.jpg" />
    <img src="/images/image3.jpg" />
</div>
Step 4: Call anyslider plugin

$(document).ready(function(){    
    $('.anyslider').anyslider();
});


Please read document for how to use anyslider on your website

AnySlider has many features and options for easy customize your slider.

Multiple Slider Features:

Autoplay, infinite loop or 1 cycle.
More than 20 slide effects with 3D effect to let you choose.
Highly customize appearance.
Multiple sliders, instance on same page.
Navigation slide bullets.
Next, Previous, Play, Pause buttons
No CSS file required.
Slide any content image, text, remote source in iframe like Youtube, Vimeo...
Supported in all major browsers.
Touch device supports.
Stop slide when Tab, Window is invisible
Stop slide when slider is not visible on screen
Supports multiple captions
Supports caption animation with loop
Support 3D effect
Allow to add slide at run time
Multiple Slider Options:

Auto start Slide
Start at slide N on load
Allow set slider padding
Allow set slider background by color name, color code or image
Set delay time for all slides or each slide
Set effect duration for all slides or each slide
Show controls (navigate slide bullets, next, previous, play and pause buttons
Random select effects
Random select slide
Allow change effect at run time
Show or hide caption
Allow set caption position: top, left, right, bottom, top left, top right, bottom left, bottom right
Allow set caption color
Allow pause on hover slide and resume on leaving slide
Enable/ Disable touch device
Enable/ Disable loop, allow to set showing slide in one cycle
Multiple callback functions, onLoad, onCycleStart, onCycleEnd, onStartSlide
Slider with No CSS file

Most of image sliders use complex css markup theme and effect or animation but AnySlider does not use separated css file for that task. It even does not use image for any icon as next, previous, play or pause. It uses simple inline css to create icons to reduce loading time.

Using built-in jquery animation for slide effect

AnySlide uses jquery animation to produce slide effects. There are more than 20 effects and will be add more. AnySlide runs smoothly on all modern browsers and works well on smart phone.

Build image content slider in seconds

Using AnySlider is very easy, just put any elements (image, div, iframe...) inside a div with class or id and then call $(selector).anyslider({options}) that is.

Multiple slide captions with animation

One of the most useful feature of anyslider is multiple captions with animation options for caption on each slide. AnySlider also supports caption animates by multiple steps. You can define infinite caption animation loop or just animate one cycle. Slide captions can be place at top, left, bottom, right, top left, top right, bottom left or bottom right or at absolute position.

Responsive image content Slider

AnySlider is responsive slider and it also supports multiple slide size. It detects each slide content and adjust slider container size to fulfill the content. It is easy for you to wrap anyslider inside a small container to make small slider or put in page or container with width is 100% and let anyslider to fulfill space.

Multiple slider instances on same page

AnySlider allow you to have more than one slider instances on same page. Each slider has its own parameters and run/animate effect separately. Ex: you can set first slider will be autplay with effect duration is 2000ms (2 seconds) and slide show for 2500ms (2,5 seconds) and on second slider with effect duration 1000ms (1 second) and slider show for 2000ms (2 seconds)

Video (youtube, vimeo,...) slider

AnySlider supports to slide video from youtube, vimeo... It is easy to place video in anyslider. You only need to copy embed code and put inside anyslider.

Ex:

<div class="anyslider">
    <iframe width="560" height="315" src="youtube url" frameborder="0" allowfullscreen></iframe>
</div>


3D image, content slider

AnySlider support 3D view slider, you can check cube effect and flip effect which are 3D animations, it animates slides in X, Y and Z coordinates.

Multiple slide effects, more than 20 slide effects

fade effect
blind effect
blind bar effect
crunch bar effect
slider bars
appear effect
explode effect
jumble effect
diagonal effect
paint effect
rotate effect
zoom in effect
zoom in rotate effect
blur out effect
flip effect
turn in effect
turn out effect
door in effect
door out effect
shift effect
push effect
slide effect
cube effect
