# Sonntagswelt

This world is up & running on a template map.

## Tools

In order to build the map:

- „tiles“ (i.e. images) to create the map (the starter provides a default tileset) & a pixel editor (if you want to create an own tileset or alter an existing one, e.g. Photoshop or whatever you like)
- the [Tiled Map Editor](https://www.mapeditor.org/) software
- a web-server to serve the map (this world uses Github static pages as a web-server)


## Next up: Customizing the map

### Cloning the map

Start by cloning the map. If you are used to Git and GitHub, simply clone the map
to your computer using your preferred tool and [jump to the next chapter](#loading-the-map-in-tiled).

If you are new to Git, cloning the map means downloading the map to your computer.
To do this, you will need Git, or a Git compatible tool e.g. [GitHub Desktop](https://desktop.github.com/).

TODO: test & continue

### Loading the map in Tiled

The sample map is in the file `map.json`.
You can load this file in [Tiled](https://www.mapeditor.org/).

Now, it's up to you to edit the map and write your own map.

Some resources regarding Tiled:

- [Tiled documentation](https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Tiled video tutorials](https://www.gamefromscratch.com/post/2015/10/14/Tiled-Map-Editor-Tutorial-Series.aspx)

### About WorkAdventu.re maps

In order to design a map that will be readable by WorkAdventure, you will have to respect some constraints.

In particular, you will need to:

- set a start position for the players (e.g. an hallway, a garden &c)
- configure the „floor layer” (so that WorkAdventure can correctly display characters above the floor, but under the ceiling)
- eventually, you can place exits that link to other maps

All this is described in the [WorkAdventure documentation](https://github.com/thecodingmachine/workadventure/#designing-a-map).


### Pushing the map

When your changes are ready, you need to commit & push the changes back to GitHub.
Make sure, you include the .json-map & the .png-tiles.
Just wait a few minutes, and your map will be propagated automatically to the GitHub pages web-server.
