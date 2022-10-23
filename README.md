# HackGT9
Tree Ringer

## Inspiration
I have always had a passion for environmental science. If I was not doing computer science, I would be doing something in that science field related to geology, meteorology, or something similar. Earlier this week, my climate change professor showed me cores taken from trees in the Great Basin National Park. These trees show tree rings that have a record of climate based on the thickness of the tree rings.

## What it does
My program takes in an image of one of these cores and identifies how many tree rings there are and the thickness between each ring. The thickness of the rings determines the amount of precipitation or difference in average temperature throughout that year.

## How I built it
I built this program using Python and computer vision algorithms to detect the tree rings in each photo. Once the program was able to detect where the tree rings were, I used the ruler in the image to determine the distance between each ring by multiplying amount of pixels per millimeter

## Challenges I ran into
I am not that familiar with computer vision techniques. My first computer vision technique I attempted to use was called pytorch. It did not accurately grab the tree rings, rather it grabbed everything but the tree rings. I had to not only find another computer vision algorithm to use, but also learn how to use another one after my first attempt would not work.

## Accomplishments that I am proud of
What I'm proud of is how close to accurate my measurements have gotten. With a few precision changes I am able to get a range that grabs the correct amount of rings plus or minus a few. 

## What I learned
What I learned from this was a lot more about computer vision and data science processing. The images were all in array format of multiple dimensions. I had to learn to do multiple calculations, transformations, and filtering of these images to make this project work. I learned about convolution filters that change an image. In the process I also learned about the way tree rings record environmental data about an area through measurements of precipitation and temperature.

## What's next for Tree Ringer
There are many different types of trees. The tree core I used was from the Great Basin National Park. What is next for Tree Ringer is to make the measurements even more precise and to get it to work with other cores from different types of trees that have different tree ring sizes, colors, and shapes.
