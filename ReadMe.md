# Project 1

# By John Valeriano

Demo link : https://jovaleri.github.io/Project1VR/      
Video link :  

## Features:
 **Scripts Used** 
```
<script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
    <script src="https://unpkg.com/aframe-environment-component@1.1.0/dist/aframe-environment-component.min.js"></script>
    <script src="https://cdn.rawgit.com/donmccurdy/aframe-extras/v3.3.0/dist/aframe-extras.min.js"></script>
    <script src="//cdn.rawgit.com/donmccurdy/aframe-physics-system/v4.0.1/dist/aframe-physics-system.min.js"></script>
    <script src="js/sky.js"></script>
    <script src="js/sunSetter.js"></script>
    <script src="https://unpkg.com/aframe-click-drag-component"></script>
    <script>
      registerAframeClickDragComponent(window.AFRAME);
    </script> 

<!-- Script to switch scenes when pressing the box -->
    <script type="text/javascript"> 
          function Covid() {
            document.getElementById('Covid').setAttribute('visible', 'true')
            document.getElementById('NonCovid').setAttribute('visible', 'false')
          }

          function NonCovid() {
        document.getElementById('NonCovid').setAttribute('visible', 'true')
        document.getElementById('Covid').setAttribute('visible', 'false')
  }
        </script> 

<!--Function levels of light when clicked -->
<script>
  function fourLevelLight() {
      var light = document.querySelector('#light');
      var current_intensity = light.getAttribute('intensity');

      if (current_intensity == 1)
          light.setAttribute('intensity', .5);
      else if (current_intensity == .5)
          light.setAttribute('intensity', 0);
      else if (current_intensity == 0)
          light.setAttribute('intensity', 2);
      else
          light.setAttribute('intensity', 1);
  }

</script>
```

## Intro
![Intro](https://github.com/jovaleri/Project1VR/blob/master/Project1Gifs/Introduction.gif)

## Animation
   
![Cat](https://github.com/jovaleri/Project1VR/blob/master/Project1Gifs/Cat_Animation.gif)  
```
 <a-entity id="update31"  
        rotation="0 .065 0" 
        scale="0.03 0.03 0.03" 
        position="-4.62619 0.07915 -0.63629"
        animation="dur: 5000; easing: linear; from: -4.62 0.079 -.636; loop: -1; to: -4.62 0.079 5; property: position; autoplay: true"
        gltf-model="#Cat"></a-entity>
```
## Interactions   
    **Click with the mouse, no need to use the circle to target!**

Switching Scenes
![Scene Change](https://github.com/jovaleri/Project1VR/blob/master/Project1Gifs/Switch_Scenes.gif)

![Light Interaction](https://github.com/jovaleri/Project1VR/blob/master/Project1Gifs/Light_Interaction.gif)

![Music Interaction](https://github.com/jovaleri/Project1VR/blob/master/Project1Gifs/Speakers.jpg)


## Grading  
For a C, you need to:
* Customize the TTU CS VR showroom into your environment settings with your own style of floor, ceiling, and decorations. You can also start from scratch
* Have at least unique 10 models (you can get free models online) at appropriate locations in your VR encironment. I don't simply count the number of objects
* Try your basic environment on a Google Cardboard
* Have appropriate lighting. Do not give me a complete dark screen.

For a B, you need to:
* Add an additional 5 unique models (that you build)
* Give the user control over the lighting: Change the color, brightness, Day/night simulation
* You should be able to navigate around the space. You can use teleporting if needed.
* User can select to turn on/of Covid mode by clicking on a button and/or splitting the screen.

For a A, you need to:
* Add one dynamic object~~
* Interact with certain objects
* Interact with certain objects


## Models Used
* Apartment
* Bed
* Bedroom Desk
* BedroomTV
* BedroomTV(Non Covid)
* Bodybags
* Cat
* Computer 
* Desktop
* Desktop(Non Covid)
* Door
* FaceMask
* Food
* Food_2
* Fridge
* GamingChair
* Guitar
* Kitchen
* LightSwitch
* LivingRoomTV
* LivingRoomTV(Non Covid)
* Motorcycle
* Roof
* Shower
* Sofa
* Speakers
* Speakers(Non Covid)
* Sun
* Toilet
* ToiletPaperSafe
* ToiletPaper
* Xbox

**A majority of the models are taken from Sketchfab**

## Audios Used 

:one:[Purge Audio](https://www.youtube.com/watch?v=us_0aLWOa8E)

:two:[Blue Monday](https://www.youtube.com/watch?v=FYH8DsU2WCk)


