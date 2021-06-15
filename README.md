# cuie-canton-map-example
![thumbnail_image001](https://user-images.githubusercontent.com/62279352/122012348-5bf18500-cdbd-11eb-939d-1f00ee30987b.png)

Version 1) Normal version, with normal canton names ("Aargau", "Zug") - https://github.com/m-bug/cuie-canton-map-example-gradle/raw/main/CantonMap.zip

Version 2) Alternative version, with short canton names ("AG", "ZG") - https://github.com/m-bug/cuie-canton-map-example-gradle/raw/main/CantonMap_shortname.zip

## Getting Started
1. Download one of the zip from above
2. Go into .zip and navigate to "src\main\resources" and copy folder "fonts" and file "canton_data.txt" to your "src\main\resources"
3. Copy folder "cuie" to your "src\main\java\"
4. Adjust your Presentation model with another property: Example inside zip file
5. Add binding pm <-> cantonMap like: `cantonMapControl.textProperty().bindBidirectional(pm.cantonTextProperty());`

## Creating an instance of CantonMapControl
``` java
var pm = new PresentationModel();
var cantonMapControl = new CantonMapControl();
// Replace your TextField with cantonMapControl

// don't forget to add the binding
cantonMapControl.textProperty().bindBidirectional(pm.cantonTextProperty());
```

## Adjusting width and other style
The styling can easily be adjusted by editing the file `cuie/project/cantonmap/style.css`

## I need Help
Please contact us on Teams or write us an E-Mail ;)

If you implemented the control on your own without our help, please let us know :)
