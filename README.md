# cuie-canton-map-example

## Getting Started
1. Download zip: https://github.com/m-bug/cuie-canton-map-example-gradle/blob/main/cuie-cantonMap-example.zip
2. Go into .zip and navigate to "src\main\resources" and copy folder "fonts" and file "canton_data.txt" to your "src\main\resources"
3. Copy folder "cuie" to your "src\main\java\"
4. Adjust your Presentation model with another property: Example inside zip file
5. Add binding pm <-> cantonMap like: `cantonMapControl.textProperty().bindBidirectional(pm.cantonTextProperty());`
