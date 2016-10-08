# Infograph-D3
Profile infograph using D3 js.
## Skill Level Graph
![alt text](https://github.com/kedarkrishnan/infograph-D3/blob/master/images/infograph-D3-SkillLevel.png)

[Demo](http://kedarkrishnan.github.io/infograph-D3/)

## Usage
`infoGraph.skillLevel.draw(<id>,<data>)`

## Data 
Format : JSON format

Data:  Array of object with 2 properties skill and level

`[{
  "skill":"<your skill>",
  "level":"<your level of expertise>"
}]`

Sample data:

[{
				"skill" : "Java",
				"level"	: "6"
			},
			{
				"skill" : "Spring",
				"level"	: "5"
			},
			{
				"skill" : "BIRT",
				"level"	: "9"
			}]

## Options 
1. Set Label Color `infoGraph.skillLevel.labelColor("<Hex Color code>")`
2. Set Starting poistion of label (from left) `infoGraph.skillLevel.labelStart(<position>)`
3. Set Bubble color `infoGraph.skillLevel.bubleColor("<Hex Color code>")`
4. Set Bubble radius `infoGraph.skillLevel.bubleRadius(<radius>)`
5. Set Bubble stroke color `infoGraph.skillLevel.bubleStrokeColor("<Hex Color code>")`
6. Set Skills maximum level `infoGraph.skillLevel.maxLevel(<maxLevel>)`
7. Set whether to show the max level `infoGraph.skillLevel.showMax(<true | false>)`

*Method chaining can be used to customize.*
`draw` method should be called after customization.

Ex:
`infoGraph.skillLevel.bubleColor("#3F51B5").bubleStrokeColor("#3F51B5").draw("skills",skillsData);`
