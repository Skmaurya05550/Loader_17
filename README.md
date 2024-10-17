# Animated Loader with Rotating Squares and Text

This project showcases a creative loading screen with animated squares and a blinking text effect. The loader features four rotating squares, each with unique colors and shape modifications, along with a glowing "Loading..." text that blinks in and out.

## Project Preview
![17291722745207419672175379010942](https://github.com/user-attachments/assets/0110d69a-2ce6-4202-a038-1fc050b9da89)


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

   
