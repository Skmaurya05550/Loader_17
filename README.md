# Animated Loader with Rotating Squares and Text

This project showcases a creative loading screen with animated squares and a blinking text effect. The loader features four rotating squares, each with unique colors and shape modifications, along with a glowing "Loading..." text that blinks in and out.

## Project Preview

![Project Preview](URL-to-screenshot-or-gif)  
*(Replace with a screenshot or GIF of your project)*

## Features
- Rotating squares with unique animations for each.
- Glowing and blinking "Loading..." text effect.
- Smooth rotation and scale transformations using CSS keyframes.

## Code Explanation

1. **HTML Structure**:
   The loader consists of a main container (`.loading-screen`) that holds the rotating squares inside a `.loading` div. Additionally, a `h1` element displays the animated text.

   ```html
   <div class="loading-screen"> 
       <div class="loading"> 
           <span></span>
           <span></span>
           <span></span>
           <span></span>
       </div>
       <h1 class="text">Loading...</h1>
   </div>

   
