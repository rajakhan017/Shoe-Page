# Shoe-Page
## [Live Website Link!]https://rajakhan017.github.io/Shoe-Page/

### Structure of the web page

<img src="./public/webpage.png" width="700px" alt="structure of the webpage"  />

### Universal Selector `*`

| CSS Property | Value      | Explanation                                                                                                 |
| ------------ | ---------- | ----------------------------------------------------------------------------------------------------------- |
| margin       | 0          | Sets margin on all sides to 0.                                                                              |
| padding      | 0          | Sets padding on all sides to 0.                                                                             |
| box-sizing   | border-box | Makes sure that the element's total width and height include padding and border, not just the content area. |

### `body`

| CSS Property     | Value    | Explanation                                                             |
| ---------------- | -------- | ----------------------------------------------------------------------- |
| background-color | #d3d3d3  | Sets the background color of the entire page to a light gray (#d3d3d3). |
| position         | relative | The body is given a relative positioning context.                       |

### `.container`

| CSS Property | Value    | Explanation                                                           |
| ------------ | -------- | --------------------------------------------------------------------- |
| width        | 100%     | Sets the width of the container to 100% of its parent's width.        |
| height       | 100vh    | Sets the height of the container to 100% of the viewport height (vh). |
| position     | relative | The container is given a relative positioning context.                |
| overflow     | hidden   | Hides any content that overflows the container.                       |

### `.container::after`

| CSS Property | Value                | Explanation                                                                                       |
| ------------ | -------------------- | ------------------------------------------------------------------------------------------------- |
| content      | ''                   | Generates an empty content box.                                                                   |
| position     | absolute             | The pseudo-element is positioned absolutely.                                                      |
| inset        | 0                    | Sets the top, right, bottom, and left properties to 0, effectively covering the entire container. |
| transform    | skewY(10deg)         | Applies a skew transformation of 10 degrees along the Y-axis.                                     |
| background   | linear-gradient(...) | Sets a linear gradient background for the pseudo-element.                                         |
| z-index      | -1                   | Places the pseudo-element behind the container's content.                                         |
| box-shadow   | 0px 0px 10px black   | Adds a black shadow with a 10-pixel blur.                                                         |

### `.inner`

| CSS Property     | Value                | Explanation                                                                              |
| ---------------- | -------------------- | ---------------------------------------------------------------------------------------- |
| top              | 10%                  | Positions the inner element 10% from the top of its parent.                              |
| width            | 85%                  | Sets the width of the inner element to 85% of its parent's width.                        |
| height           | 75%                  | Sets the height of the inner element to 75% of its parent's height.                      |
| background-image | linear-gradient(...) | Sets a linear gradient background for the inner element.                                 |
| margin           | 7.5% auto auto       | Sets margins with 7.5% on top and auto on the sides, centering the element horizontally. |
| color            | #fff                 | Sets the text color to white (#fff).                                                     |
| padding          | 2%                   | Adds 2% padding to the inner element.                                                    |
| box-shadow       | 0 0 10px #000        | Adds a shadow with a 10-pixel blur and black color.                                      |
| z-index          | 1                    | Places the inner element above the container's content.                                  |

### `.inner .text`

| CSS Property | Value | Explanation                                                      |
| ------------ | ----- | ---------------------------------------------------------------- |
| width        | 40%   | Sets the width of the text element to 40% of its parent's width. |

### `.inner h1`

| CSS Property  | Value | Explanation                                       |
| ------------- | ----- | ------------------------------------------------- |
| margin-bottom | 30px  | Adds a bottom margin of 30 pixels to the heading. |
![image](https://github.com/rajakhan017/Shoe-Page/assets/135150598/03c735ba-7f28-4ad5-bcac-cc0287998878)


### `.text p`

| CSS Property  | Value | Explanation                                      |
| ------------- | ----- | ------------------------------------------------ |
| font-size     | 18px  | Sets the font size of paragraphs to 18 pixels.   |
| margin-bottom | 50px  | Adds a bottom margin of 50 pixels to paragraphs. |
| line-height   | 20px  | Sets the line height of paragraphs to 20 pixels. |

### `.inner img`

| CSS Property | Value    | Explanation                                         |
| ------------ | -------- | --------------------------------------------------- |
| position     | absolute | The image is positioned absolutely.                 |
| right        | 0        | Initially positioned at the right edge.             |
| top          | 10%      | Initially positioned 10% from the top.              |
| width        | 600px    | Sets the initial width of the image to 600 pixels.  |
| height       | 300px    | Sets the initial height of the image to 300 pixels. |
![image](https://github.com/rajakhan017/Shoe-Page/assets/135150598/0cea94d0-c163-49bb-9b80-f20a30ab527c)


### `.inner img:hover`

| CSS Property | Value | Explanation                                                   |
| ------------ | ----- | ------------------------------------------------------------- |
| right        | 0px   | Adjusts the right position when hovered.                      |
| top          | 15px  | Adjusts the top position when hovered.                        |
| width        | 900px | Increases the width of the image to 900 pixels when hovered.  |
| height       | 600px | Increases the height of the image to 600 pixels when hovered. |
![image](https://github.com/rajakhan017/Shoe-Page/assets/135150598/8286b98c-38ce-49af-a361-73d5276e49be)
