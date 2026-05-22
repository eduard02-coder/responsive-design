# responsive-design
A boilerplate for a responsive design website based on Sass. 

Example of usage, the same content of the mains.scss file
```
body {
    @include responsive(

        // the max width of each device
        (
            smartphone: 480px,
            tablet: 768px,
            desktop: 1279px,
            largedesktop: 1920px,
        ),

        // the responsive design type: choose layout-shift, mostly-fluid or column-drop
        layout-shift 
    );
}
```
To get this working properly, inside your body tag on index.html you must have at least 3 block-type tags (div, section, aside, or a mixture thereof). No matter the inner blocks class names, they may not have a class.
