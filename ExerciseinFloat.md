
## Exercise 4: Float-based Gallery

### Introduction

Creating a gallery of images with consistent spacing is a common requirement in web design. This exercise will guide you in using basic CSS properties to achieve such a layout using the `float` property.

### HTML Structure:

Please use the following HTML structure for this exercise:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Float-based Gallery Exercise</title>
    <style>
        /* Your CSS goes here */
    </style>
</head>
<body>
    <div class="gallery">
        <img class="img-item" src="yourimagehere.jpg" alt="Image 1">
        <img class="img-item" src="yourimagehere.jpg" alt="Image 2">
        <img class="img-item" src="yourimagehere.jpg" alt="Image 3">
        <img class="img-item" src="yourimagehere.jpg" alt="Image 4">
    </div>
</body>
</html>
```

**Note:** Replace `image1.jpg`, `image2.jpg`, etc., with your image paths.

### Instructions:

1. All images should be of width `200px`.
2. Use the `float` property to make sure the images line up side by side.
3. Ensure each image has a padding of `10px` and a background color of your choice.
4. Use the `box-sizing` property so that padding and image content does not exceed the specified width of `200px`.
5. Add a `20px` margin to the right side of each image, except for the last one.
6. Clear the floats after the last image to ensure consistent behavior of any subsequent content.




