# animation

Hosted link:https://rajkumarrj.github.io/animation/

![image](https://github.com/RajkumarRj/animation/assets/142428565/fa5659c0-6c53-4524-a91b-4c895c0dec21)


1. **HTML Structure:**
   - The code starts with the usual `<!DOCTYPE html>` declaration, specifying that it's an HTML5 document.
   - The `<html>` element defines the root of the HTML document, and `lang="en"` is set to indicate that the document is in English.
   - The `<head>` section contains metadata about the document, including character encoding, viewport settings, and the document's title.
   - The `<body>` section contains the visible content of the web page.

2. **CSS Styling:**
   - The CSS styles are embedded within a `<style>` element in the HTML document.
   - The `*` selector is used to reset margin, padding, and box-sizing for all elements on the page, ensuring consistent styling.

3. **Body Styling:**
   - The `<body>` element is styled to have a flexbox layout.
   - It's centered both horizontally and vertically using `justify-content` and `align-items`.
   - The background color is set to black (`#000`), and the minimum height is set to 100 viewport height units (`vh`).

4. **Image Container:**
   - The `<div>` with the class `.container` is used to group images.
   - It's styled as a flex container with images distributed evenly (`space-between`) horizontally.
   - It also includes a reflection effect using `-webkit-box-reflect`. This creates a subtle reflection beneath the images.

5. **Image Styling:**
   - `<img>` elements inside the `.container` are styled.
   - The `max-width` is set to 350px, ensuring images don't exceed this width.
   - The `transform-origin` is set to the center of the images.
   - A 3D perspective rotation effect is applied to the images using `transform`. They initially have a 20-degree rotation on the Y-axis, giving them a tilted appearance.
   - There's a smooth transition effect of 0.5 seconds when the images change.
   - A box shadow is added to create a subtle shadow effect.
   - A border-radius of 5px rounds the corners of the images.

6. **Image Hover Effects:**
   - When hovering over the `.container`, the images inside it have their opacity reduced to 0.3, making them semi-transparent.

7. **Image Hover Transition:**
   - When an individual image is hovered over, it returns to its original perspective (0-degree rotation) and full opacity (1), creating a "flip" effect.
