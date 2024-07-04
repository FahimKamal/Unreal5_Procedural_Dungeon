# Unreal5 Procedural Dungeon
 It is as the name says, each time the game will generate new dungeon map procedurally. It has a
`BP_Master_Room` `Blueprint` class and I have created few more `child` classes from that class. 
To create more variations you can create more `child` classes. 

The `BP_DungeonGenerator` `Blueprint` class will do all the heavy lifting. All you have to set a int
value in `RoomAmount` variable. And when you run the game it will generate that about of rooms connected
with each other and create a Dungeon. Fully random. 

I create this with the help for a Youtube tutorial. Watch it [here](https://youtu.be/4ddbnQIuwAM?si=A9lRDaPQUDQacMFB).
