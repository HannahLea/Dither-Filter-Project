# Title
Dither Filter 

## Repository
<https://github.com/HannahLea/Dither-Filter-Project.git>

## Description
This python tool will alow artist to apply custamizable dithering effects to images and videos. By being able to change the type of dithering, the color palettes, and amount of colors, it gives artist freedom to create retro-inspired visuals. 

## Features
- Different dithering effects
	- Based on how the dithering effect is calculated, there will be different final looks for each. It will include at least two different algorithms to switch between. 
- Number of color range and palette selection
	- User will have the chance to adjust from a small range of colors for the final ouput such as 2 to 6 colors. There will be premade color palettes to choose from. 
- Image Processing 
	- Users will be able to import images, apply their desired dither effect, and export the processed results with Pillow and NumPy
- Video Processing
    - Similarly to image processing, users import video and apply the dithering filter to an individual frame at a time with MoviePy. Then the individual image sequence will be reconstructed back into a video.
- Menu UI
    - By using PySide6, I will be able to create a user interface so that users can directly change the dither effect in the preview window without having to go into the code and hardcode their changes.
- Before and after preview
    -This will include side by side preview to see the difference between the original image and the new image with the filter added. 

## Challenges
- Research and implement dithering algorithims such as error diffusion and ordered dithering
- Learn how to apply dithering calculations to individual pixels using NumPy and Pillow to manipulate image data
- Learn how to make a GUI using PySide6 for simple buttons, preview windows, and sliders. 

## Outcomes
Ideal Outcome:
- Fully functioning application that allows image and video importing, lets users cutomize dithering algorthims, choose how many colors are between 2-6, and color palettes through a GUI menu.

Minimal Viable Outcome:
- A functional application that lets users import images. They are able to apply one dithering algorithm, adjust number of colors between 2-6, and select from a preset color palettes. 

## Milestones

- Week 1
  1. Research dithering techniques and implement 
  2. Implement adjustable amount of colors (2-6) and preset color palletes

- Week 2
  1. Implement image importing, processing, and exporting
  2. Implement video importing, processing, and exporting
  3. Start basic user interface 

- Week 3 (Final)
  1. Finalize user interface
  2. Fix bugs
  3. Write up README File