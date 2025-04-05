Create html app using p5.js.
Please use classes for javascript.
Please use single responsibility 

Acceptance Criteria for Legend of Zelda Dungeon Exploration User Stories
Find the entrance to the dungeon

GIVEN Link is in the overworld
WHEN Link walks onto the dungeon entrance location
THEN Link descends into the first room of the dungeon

Navigate through rooms with different layouts

GIVEN Link is in a dungeon room
WHEN Link walks through a door
THEN Link enters a new room with a different enemy arrangement and/or puzzle
AND the camera transitions to show the new room

Defeat Stalfos enemies using sword

GIVEN Link encounters Stalfos enemies
WHEN Link strikes a Stalfos with his sword
THEN the Stalfos takes damage
AND after sufficient hits, the Stalfos is defeated and may drop an item

Avoid or block projectiles from Keese

GIVEN Keese are flying and attacking Link
WHEN a Keese launches a projectile toward Link
THEN Link can either move out of the way OR
WHEN Link raises his shield in the direction of the projectile
THEN the projectile is blocked without Link taking damage

Discover and collect a map

GIVEN Link enters a room containing the map
WHEN Link collects the map
THEN the map icon appears in the HUD
AND Link can now view the dungeon layout when pausing the game

Find a compass

GIVEN Link enters a room containing the compass
WHEN Link collects the compass
THEN the compass icon appears in the HUD
AND the location of the Triforce fragment is marked on the dungeon map

Push blocks to reveal hidden passages

GIVEN Link is in a room with suspicious-looking blocks
WHEN Link pushes against a movable block
THEN the block slides to reveal a hidden passage
AND Link can access the newly revealed area

Collect keys from defeated enemies

GIVEN Link defeats designated enemies
WHEN an enemy drops a key
THEN Link's key count increases by one
AND the key disappears from the room when collected

Find a special item (the bow)

GIVEN Link enters the room containing the bow
WHEN Link collects the bow
THEN the bow is added to Link's inventory
AND Link can now select and use the bow when B button is pressed
AND arrows consume rupees when fired

Use bombs to blast open cracked walls

GIVEN Link has bombs in inventory
WHEN Link places a bomb near a cracked wall
THEN the bomb explodes after a short delay
AND the cracked wall is destroyed
AND a new passage is revealed

Find and collect the boomerang

GIVEN Link enters the room containing the boomerang
WHEN Link collects the boomerang
THEN the boomerang is added to Link's inventory
AND Link can now select and use the boomerang when B button is pressed
AND the boomerang returns to Link after being thrown

Restore health by collecting hearts

GIVEN Link defeats an enemy that drops a heart
WHEN Link collects the heart
THEN Link's health increases by one heart unit
AND the heart disappears from the room

Navigate through dark rooms using a candle

GIVEN Link has a candle and enters a dark room
WHEN Link uses the candle
THEN a temporary light illuminates the surrounding area
AND Link can see enemies, items, and walls within the illuminated area
AND the light fades after a set duration

Defeat the dungeon boss (Aquamentus)

GIVEN Link enters the boss room containing Aquamentus
WHEN Link deals sufficient damage to Aquamentus with sword or arrows
THEN Aquamentus is defeated
AND Aquamentus disappears in the standard enemy defeat animation
AND a heart container appears in the center of the room

Collect the Triforce fragment

GIVEN Link has defeated the dungeon boss
WHEN Link enters the final room containing the Triforce fragment
AND Link touches the Triforce fragment
THEN the Triforce fragment is collected with a celebratory animation and sound
AND Link is transported back to the overworld
AND the dungeon is marked as completed on the overworld map
