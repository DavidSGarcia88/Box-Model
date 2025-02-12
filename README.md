## Rothko Painting Project
This project was created as part of the FreeCodeCamp courses to practice web development, especially creating artistic representations using HTML and CSS.

## Description
This project is a representation of a Rothko-style painting using color blocks in HTML and CSS. Each block has visual effects like shadows, rounded borders, and a blur filter to emulate the abstract style of Mark Rothko's paintings.

## File Structure
- `index.html`: Contains the basic structure of the web page.
- `styles.css`: Contains the styles that apply visual effects and design, such as the blur and shadows to the color blocks.

## Installation
Clone or download this repository to your local machine.
Open the index.html file in your browser to view the result.

## Technologies Used
- HTML5
- CSS3

## Functionality
This project creates a visual representation of three color blocks. Each block has a blur effect (blur) and other visual properties like shadows and rounded borders.

## HTML
The index.html file creates the visual structure with three blocks inside a canvas container.

html
<div class="frame">
    <div class="canvas">
        <div class="one"></div>
        <div class="two"></div>
        <div class="three"></div>   
    </div>
</div>

## CSS
The styles.css file defines the colors, shadows, borders, and transformations for the blocks. Here are the key CSS classes:

- .canvas: Represents the area containing the blocks. It has a dark brown background, a slight blur, and limits the visibility of the blocks with overflow: hidden.
- .frame: This is the black border surrounding the entire "canvas", with thick borders and centered margins.
- .one, .two, .three: These are the color blocks with shadow effects and transformations to give them a sense of movement or distortion.

css
.canvas {
    width: 500px;
    height: 600px;
    background-color: #4d0f00;
    overflow: hidden;
    filter: blur(2px);
}

.frame {
    border: 50px solid black;
    width: 500px;
    padding: 50px;
    margin: 20px auto;
}

.one {
    width: 425px;
    height: 150px;
    background-color: #efb762;
    margin: 20px auto;
    box-shadow: 0 0 3px 3px #efb762;
    border-radius: 9px;
    transform: rotate(-0.6deg);
}

.two {
    width: 475px;
    height: 200px;
    background-color: #8f0401; 
    margin: 0 auto 20px;
    box-shadow: 0 0 3px 3px #8f0401;
    border-radius: 8px 10px;
    transform: rotate(0.4deg);
}

.one, .two {
    filter: blur(1px);
}

.three {
    width: 91%;
    height: 28%;
    background-color: #b20403;
    margin: auto;
    filter: blur(2px);
    box-shadow: 0 0 5px 5px #b20403;
    border-radius: 30px 25px 60px 12px;
    transform: rotate(-0.2deg);
}

## Author

Project developed by David Garcia as part of a FreeCodeCamp course.

## License

This project is licensed under the BSD-3-Clause License.
