
## CSS Transform

>The `transform` property comes in two different settings, two-dimensional and three-dimensiona.
>Two-dimensional transforms work on the x and y axes.
>Three-dimensional transforms work on both the x and y axes, as well as the z axis

> Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
~~~~
<figure class="box-1">Box 1</figure>
~~~~
~~~~
.box-1 {
  transform: rotate(20deg);
}


.box-1 {
  transform: scale(.75);
}
~~~~

![](https://mobile.htmlgoodies.com/imagesvr_ce/1608/ss_transform.png)

> Transitions provide a change from one state to another.
> not all properties may be transitioned.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQqXfHRAG3i3rpAcdde-3NiSLYsNmdHsIj0KoIfN-brEgO2-Tkk&usqp=CAU).

### Animations

> To set multiple points at which an element should undergo a transition, use the `@keyframes` rule.
> A timing function and delay can be declared using the `animation-timing-function` and `animation-delay` properties.

>it's pretty cool to use CSS animations to add interactivity to webpages.