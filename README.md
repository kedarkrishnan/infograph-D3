# Infograph-D3
Profile infograph using D3 js.

## Usage
`infoGraph.skillLevel.draw(<id>,<data>)`

## Options 
1. Set Label Color `infoGraph.skillLevel.labelColor("<Hex Color code>")`
2. Set Starting poistion of label (from left) `infoGraph.skillLevel.labelStart(<position>)`
3. Set Bubble color `infoGraph.skillLevel.bubleColor("<Hex Color code>")`
4. Set Bubble radius `infoGraph.skillLevel.bubleRadius(<radius>)`
5. Set Bubble stroke color `infoGraph.skillLevel.bubleStrokeColor("<Hex Color code>")`
6. Set Skills maximum level `infoGraph.skillLevel.maxLevel(<maxLevel>)`
7. Set whether to show the max level `infoGraph.skillLevel.showMax(<true | false>)`

*Mehtod changing can be used to customize.*
`draw` method should be called after customization.

Ex:
`infoGraph.skillLevel.bubleColor("#3F51B5").bubleStrokeColor("#3F51B5").draw("skills",skillsData);`
