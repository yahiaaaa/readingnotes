# CSS Transforms

![drawing](https://tipsmake.com/data/images/3d-transform-in-css-picture-1-jtznOkrOW.jpg)

With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

* Transform Syntax The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
* 2D Transforms Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.
 * Combining Transforms It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.

### Transforms
Transform Syntax
- 2D Transforms :2D Rotate, 2D Scale, 2D Translate, 2D Skew.
- Combining Transforms
- Transform Origin
- Perspective
- Perspective Depth Value
- Perspective Origin
- 3D Transforms:3D Rotate, 3D Scale, 3D Translate, 3D Skew, Shorthand 3D Transforms.
- Transform Style
- Backface Visibility

8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
1- Fade in
2- Change color
3- Grow & Shrink
4- Rotate elements
5- Square to circle
6- 3D shadow
7- Swing
7- Inset border

* To add a rotate to any element
* 
.box-1 {

  transform: rotate(20deg);
  
}

.box-2 {

  transform: rotate(-55deg);
  
}
 #### 3D Transforms
They work on the x (horizontal) and y axes (vertical) axes, as well as the z axis to define the depth.

* 3D Rotate - the same as 2D rotate but it can also rotate an element around any axes. To do so, set three new transform values, including rotateX, rotateY, and rotateZ.

* 3D Scale - the same as 3D scale but it can also scale the element on the z axis using scaleZ.

* 3D Translate - the same as 3D scale but elements may also be translated on the z axis using translateZ. A negative value here will push an element further away on the z axis, resulting in a smaller element. A positive value will pull an element closer on the z axis, resulting in a larger element.

There is no 3d skew transformation.

