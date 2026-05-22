# responsive-design
A boilerplate for a responsive design website based on Sass. 

Example of usage
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

        // the responsive design type: choose layout-shift, mosly-fluid or column-drop
        layout-shift 
    );
}
```
