# Launchpad Tecnical Challenge
Solution to the Front End Technical Challenge for UBC Launchpad

# Description
"You and your friends are developing a new start-up called DRUBER, a drone-based ride share application that carries you to your destination. The original specification was to develop a web page that works in 1920x1080 however your company has realized that it is missing an entire market of smartphone users. Describe how you can modify your code to work in smartphone resolutions e.g. 750x1334 (iPhone 8). Please give specific examples where possible, but do not implement an entire DRUBER clone!"

# Solution
I implemented the website with simple elements to show that the code works. It has a title and description at the top, as well as my name and a small explanation about what it is at the bottom. The main body consists 4 dynamic photos next to each other and depending on the screen size they go underneath eachother to fit. This is done with the following code snippet:
```css
    @media only screen and (min-width: 750px){
      .image_items {
      display: flex;
      }
```
The website also becomes vertical for mobile and smaller screens in general with the following code:
```html
    <meta name="viewport" content="width=device-width" />
```
