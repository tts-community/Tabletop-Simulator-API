
This page has information on each type of non-custom object, including the `type` strings used to designate the type of Object to spawn using the [spawnObject()](base.md#spawnobject) function.

For Custom Objects, see [Custom Game Objects](custom-game-objects.md).

Each item listed here is treated as a unique object type. (ie. A red checker tinted black will not stack on top of a regular black checker.)

## Object Types

### Game Boards

All boards spawn locked by default.

Type | Description | Notes
-- | -- | --
<a class="anchor" id="Backgammon_Board"></a>Backgammon_Board | The fold-open board of Backgammon. | Includes snap-points along each triangle.
<a class="anchor" id="CardBot_Board"></a>CardBot_Board | The main board and 4 player boards of CardBots, Build & Destroy. | Includes snap-points on each card and deck location.
<a class="anchor" id="Checker_Board"></a>Checker_Board | The 8x8 board of Checkers. | Includes snap-points on each grid square.
<a class="anchor" id="Chess_Board"></a>Chess_Board | The 8x8 board of Chess. | Includes snap-points on each grid square.
<a class="anchor" id="Chinese_Checkers_Board"></a>Chinese_Checkers_Board | The 6-pointed board of Sternhalma, or Chinese Checkers. | Includes snap-points on each indent.
<a class="anchor" id="Go_Board"></a>Go_Board | The 9-starred board of Go. | Includes snap-points on each line intersection.
<a class="anchor" id="Pachisi_Board"></a>Pachisi_Board | A 6-player Pachisi board. | Includes snap-points on each indent.
<a class="anchor" id="Reversi_Board"></a>Reversi_Board | The 8x8 board of Reversi. | Includes snap-points on each grid square.

### Containers

Type | Description | Notes
-- | -- | --
<a class="anchor" id="Bag"></a>Bag | A pouch that objects can be stored in and taken from. |
<a class="anchor" id="Bowl"></a>Bowl | A wooden bowl that objects can be dropped in. | The bowl does not have an inventory, objects merely rest within it visually.
<a class="anchor" id="Go_Game_Bowl_Black"></a>Go_Game_Bowl_Black | A bowl that any number of [Black Go Stones](#Go_Game_Piece_Black) can be taken from and dropped back into. |
<a class="anchor" id="Go_Game_Bowl_White"></a>Go_Game_Bowl_White | A bowl that any number of [White Go Stones](#Go_Game_Piece_White) can be taken from and dropped back into. |
<a class="anchor" id="Infinite_Bag"></a>Infinite_Bag | A pouch that infinite copies of a single object can be taken from and dropped back into. | An object must be put into the bag to become the source object. 

### Figures

Type | Description | Notes
-- | -- | --
<a class="anchor" id="Figurine_Card_Bot"></a>Figurine_Card_Bot | A rectangle-based figurine of a CardBot from CardBots, Build & Destroy. | Faces visually to the side.
<a class="anchor" id="Figurine_Kimi_Kat"></a>Figurine_Kimi_Kat | A rectangle-based figurine of two sitting cats. |
<a class="anchor" id="Figurine_Knil"></a>Figurine_Knil | A baseless figurine of a sword-wielding knight in full-plate armor. |
<a class="anchor" id="Figurine_Mara"></a>Figurine_Mara | A baseless figurine of a bearded man in slacks. |
<a class="anchor" id="Figurine_Sir_Loin"></a>Figurine_Sir_Loin | A rectangle-based figurine of a sword-wielding warrior with a shield on his back. | Faces visually backwards.
<a class="anchor" id="Figurine_Zeke"></a>Figurine_Zeke | A baseless figurine of a cloaked character wielding a sword. |
<a class="anchor" id="Figurine_Zomblor"></a>Figurine_Zomblor | A baseless figurine of a zombified riot-officer with knives for hands, wearing a skirt. |

### Game Pieces

Type | Description | Notes
-- | -- | --
<a class="anchor" id="Backgammon_Piece_Brown"></a>Backgammon_Piece_Brown | A brown Backgammon piece. |
<a class="anchor" id="Backgammon_Piece_White"></a>Backgammon_Piece_White | A white Backgammon piece. |
<a class="anchor" id="BlockRectangle"></a>BlockRectangle | A blue rectangular prism. |
<a class="anchor" id="BlockSquare"></a>BlockSquare | A red cube. |
<a class="anchor" id="BlockTriangle"></a>BlockTriangle | A green triangular prism. |
<a class="anchor" id="Card"></a>Card | A card that is blank on both sides. | It is the size of a playing card, but will not stack into a deck.
<a class="anchor" id="Checker_Black"></a>Checker_Black | A black checker with a crown emblem on the top side. |
<a class="anchor" id="Checker_Red"></a>Checker_Red | A black checker with a crown emblem on the top side. |
<a class="anchor" id="Checker_White"></a>Checker_White | A black checker with a crown emblem on the top side. |
<a class="anchor" id="Chess_Bishop"></a>Chess_Bishop | A chrome Chess bishop. | Faces visually to the left.
<a class="anchor" id="Chess_King"></a>Chess_King | A chrome Chess King. |
<a class="anchor" id="Chess_Knight"></a>Chess_Knight | A chrome Chess knight. | Faces visually backward (a common chess practice).
<a class="anchor" id="Chess_Pawn"></a>Chess_Pawn | A chrome Chess pawn. |
<a class="anchor" id="Chess_Queen"></a>Chess_Queen | A chrome Chess queen. |
<a class="anchor" id="Chess_Rook"></a>Chess_Rook | A chrome Chess rook. |
<a class="anchor" id="Chinese_Checkers_Piece"></a>Chinese_Checkers_Piece | A marble for use in Sternhalma, or Chinese Checkers. |
<a class="anchor" id="Metal-Ball"></a>Metal Ball | A marble, identical to `Chinese_Checkers_Piece` aside from shading. | This object type has a space in it, not an underscore.
<a class="anchor" id="Chip_10"></a>Chip_10 | A blue poker chip worth $10 | Faces visually to the left.
<a class="anchor" id="Chip_50"></a>Chip_50 | A green poker chip worth $50 | Faces visually to the left.
<a class="anchor" id="Chip_100"></a>Chip_100 | A red poker chip worth $100 | Faces visually to the left.
<a class="anchor" id="Chip_500"></a>Chip_500 | A silver poker chip worth $500 | Faces visually to the left.
<a class="anchor" id="Chip_1000"></a>Chip_1000 | A gold poker chip worth $1000 | Faces visually to the left.
<a class="anchor" id="Deck"></a>Deck | A deck of the 52 standard playing cards. | Spawns face-up. Shuffles immediately when spawned.
<a class="anchor" id="Die_4"></a>Die_4 | A 4-sided die. | Spawns with 2 facing toward positive Z.
<a class="anchor" id="Die_6"></a>Die_6 | A 6-sided die with dots. | Spawns with 2 facing upwards.
<a class="anchor" id="Die_6_Rounded"></a>Die_6_Rounded | A 6-sided die with dots and rounded corners. | Spawns with 1 facing upwards.
<a class="anchor" id="Die_8"></a>Die_8 | An 8-sided die. | Spawns with the edge between 6 and 7 facing upwards.
<a class="anchor" id="Die_10"></a>Die_10 | A 10-sided die. | Spawns with the edge between 3 and 4 facing upwards.
<a class="anchor" id="Die_12"></a>Die_12 | A 12-sided die. | Spawns with the corner between 7, 9 and 11 facing upwards.
<a class="anchor" id="Die_20"></a>Die_20 | A 20-sided die. | Spawns with the edge between 1 and 17 facing upwards.
<a class="anchor" id="Die_Piecepack"></a>Die_Piecepack | A wooden 6-sided die. | Spawns with 2 facing upwards.
<a class="anchor" id="Domino"></a>Domino | A blank domino. |
<a class="anchor" id="Go_Game_Piece_Black"></a>Go_Game_Piece_Black | A black Go stone. | Spawned from a [black Go bowl](#Go_Game_Bowl_Black).
<a class="anchor" id="Go_Game_Piece_White"></a>Go_Game_Piece_White | A white Go stone. | Spawned from a [white Go bowl](#Go_Game_Bowl_White).
<a class="anchor" id="Mahjong_Coin"></a>Mahjong_Coin | A coin used in Mahjong. |
<a class="anchor" id="Mahjong_Stick"></a>Mahjong_Stick | A stick used in Mahjong. |
<a class="anchor" id="Mahjong_Tile"></a>Mahjong_Tile | A tile used in Mahjong. |
Metal Ball | A marble. | This type includes a space character and not an underline.
<a class="anchor" id="PiecePack_Arms"></a>PiecePack_Arms | A wooden coin with a blue fleur-de-lis on the underside. |
<a class="anchor" id="PiecePack_Crowns"></a>PiecePack_Crowns | A wooden coin with a green crown on the underside. |
<a class="anchor" id="PiecePack_Moons"></a>PiecePack_Moons | A wooden coin with a black moon on the underside. |
<a class="anchor" id="PiecePack_Suns"></a>PiecePack_Suns | A wooden coin with a red sun on the underside. |
<a class="anchor" id="PlayerPawn"></a>PlayerPawn | A small game piece representing a player. |
<a class="anchor" id="Quarter"></a>Quarter | An american quarter minted in 1942. | Spawns tails-up, facing to the right.
<a class="anchor" id="Reversi_Chip"></a>Reversi_Chip | A dual-colored Reversi chip. | Spawns white-side up.

### RPG Figurines

Type | Description | Notes
-- | -- | --
<a class="anchor" id="rpg_BARGHEST"></a>rpg_BARGHEST | An animated figurine of a mythical barghest. |
<a class="anchor" id="rpg_BASILISK"></a>rpg_BASILISK | An animated figurine of a mythical basilisk (a.k.a. cockatrice). |
<a class="anchor" id="rpg_BEAR"></a>rpg_BEAR | An animated figurine of a bear. |
<a class="anchor" id="rpg_BLACK_DRAGON"></a>rpg_BLACK_DRAGON | An animated figurine of an eastern dragon. |
<a class="anchor" id="rpg_CENTAUR"></a>rpg_CENTAUR | An animated figurine of an armoured centaur. |
<a class="anchor" id="rpg_CERBERUS"></a>rpg_CERBERUS | An animated figurine of an infernal 3-headed dog. |
<a class="anchor" id="rpg_CHIMERA"></a>rpg_CHIMERA | An animated figurine of a mythical chimera. |
<a class="anchor" id="rpg_CRASC"></a>rpg_CRASC | An animated figurine of a one-eyed manta-like creature. |
<a class="anchor" id="rpg_CYCLOP"></a>rpg_CYCLOP | An animated figurine of a club-wielding cyclops. |
<a class="anchor" id="rpg_DARKNESS_WARLORD"></a>rpg_DARKNESS_WARLORD | An animated figurine of an armoured, morningstar-wielding orc. |
<a class="anchor" id="rpg_DRAGONIDE"></a>rpg_DRAGONIDE | An animated figurine of an armored humanoid lizard. |
<a class="anchor" id="rpg_EVIL_WATCHER"></a>rpg_EVIL_WATCHER | An animated figurine of a cycloptic scaled head with eye-stalks and bat-wings. |
<a class="anchor" id="rpg_GHOUL"></a>rpg_GHOUL | An animated figurine of an undead humanoid |
<a class="anchor" id="rpg_GIANT_VIPER"></a>rpg_GIANT_VIPER | An animated figurine of a large snake. |
<a class="anchor" id="rpg_GOBLIN"></a>rpg_GOBLIN | An animated figurine of a lightly-armored goblin with two knives. |
<a class="anchor" id="rpg_GOLEM"></a>rpg_GOLEM | An animated figurine of a large earthen golem. |
<a class="anchor" id="rpg_GRIFFON"></a>rpg_GRIFFON | An animated figurine of a mythical griffon. |
<a class="anchor" id="rpg_HYDRA"></a>rpg_HYDRA | An animated figurine of a large 3-headed lizard. |
<a class="anchor" id="rpg_KNIGHT"></a>rpg_KNIGHT | An animated figurine of a knight in full-plate armor wielding a sword and shield. |
<a class="anchor" id="rpg_KOBOLD"></a>rpg_KOBOLD | An animated figurine of a small helmeted humanoid. |
<a class="anchor" id="rpg_LIZARD_WARRIOR"></a>rpg_LIZARD_WARRIOR | An animated figurine of a sword-wielding lizard-like humanoid |
<a class="anchor" id="rpg_MAGE"></a>rpg_MAGE | An animated figurine of a staff-wielding mage. |
<a class="anchor" id="rpg_MANTICORA"></a>rpg_MANTICORA | An animated figurine of a mythical manticore. | This type is spelled with an A.
<a class="anchor" id="rpg_MUMMY"></a>rpg_MUMMY | An animated figurine of a living mummy. |
<a class="anchor" id="rpg_OGRE"></a>rpg_OGRE | An animated figurine of a large boiled humanoid. |
<a class="anchor" id="rpg_ORC"></a>rpg_ORC | An animated figurine of an axe-wielding orc. |
<a class="anchor" id="rpg_RANGER"></a>rpg_RANGER | An animated figurine of a bow-wielding ranger. |
<a class="anchor" id="rpg_RAT"></a>rpg_RAT | An animated figurine of a giant rat. |
<a class="anchor" id="rpg_SKELETON_KNIGHT"></a>rpg_SKELETON_KNIGHT | An animated figurine of an armored living skeleton. |
<a class="anchor" id="rpg_TEMPLATE"></a>rpg_TEMPLATE | The base of an RPG figurine. | It has the same animatable triggers as any other RPG Figurine, but no associated animations.
<a class="anchor" id="rpg_THIEF"></a>rpg_THIEF | An animated figurine of a cowled knife-wielding thief. |
<a class="anchor" id="rpg_TREE_ENT"></a>rpg_TREE_ENT | An animated figurine of a large tree creature. |
<a class="anchor" id="rpg_TROLL"></a>rpg_TROLL | An animated figurine of a large green humanoid. |
<a class="anchor" id="rpg_VAMPIRE"></a>rpg_VAMPIRE | An animated figurine of a large wingless bat. |
<a class="anchor" id="rpg_WARRIOR"></a>rpg_WARRIOR | An animated figurine of a stout, bearded, axe-wielding warrior in scale mail. |
<a class="anchor" id="rpg_WEREWOLF"></a>rpg_WEREWOLF | An animated figurine of a mythical werewolf. |
<a class="anchor" id="rpg_WYVERN"></a>rpg_WYVERN | An animated figurine of a mythical wyvern. |

### Tilesets

Type | Description | Notes
-- | -- | --
<a class="anchor" id="Tileset_Barrel"></a>Tileset_Barrel | A small barrel for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Chair"></a>Tileset_Chair | A small chair for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Chest"></a>Tileset_Chest | A small chest for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Corner"></a>Tileset_Corner | A floor tile with two walls for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Floor"></a>Tileset_Floor | A floor tile for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Rock"></a>Tileset_Rock | A small rock for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Table"></a>Tileset_Table | A small table for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Tree"></a>Tileset_Tree | A small tree for use in RPG Tilesets. |
<a class="anchor" id="Tileset_Wall"></a>Tileset_Wall | A floor tile with a wall for use in RPG Tilesets. |

### Devices

Type | Description | Notes
-- | -- | --
<a class="anchor" id="Calculator"></a>Calculator | A useable calculator. | Faces visually backwards.
<a class="anchor" id="Counter"></a>Counter | A useable digital counter. |
<a class="anchor" id="Digital_Clock"></a>Digital_Clock | A useable digital clock. |
<a class="anchor" id="Notecard"></a>Notecard | An editable notecard. |
<a class="anchor" id="Tablet"></a>Tablet | A tablet that displays a webpage. |

### Triggers

Type | Description | Notes
-- | -- | --
<a class="anchor" id="ScriptingTrigger"></a>ScriptingTrigger | A Scripting Zone, a zone used for scripting. |
<a class="anchor" id="FogOfWarTrigger"></a>FogOfWarTrigger | A [Hidden Zone](https://kb.tabletopsimulator.com/game-tools/zone-tools/#hidden-zone) |
<a class="anchor" id="FogOfWar"></a>FogOfWar | A [Fog of War Zone](https://kb.tabletopsimulator.com/game-tools/zone-tools/#fog-of-war-zone) |

### Other

Type | Description | Notes
-- | -- | --
<a class="anchor" id="3DText"></a>3DText | The text that the [Text Tool](https://kb.tabletopsimulator.com/game-tools/text-tool/) spawns. |

## Spawnable Names

### Blocks

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Red-Square"></a>Red Square | [`BlockSquare`](#BlockSquare) |
<a class="anchor" id="Blue-Rectangle"></a>Blue Rectangle | [`BlockRectangle`](#BlockRectangle) |
<a class="anchor" id="Green-Triangle"></a>Green Triangle | [`BlockTriangle`](#BlockTriangle) |

### Boards

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Backgammon-Board"></a>Backgammon Board | [`backgammon_board`](#backgammon_board) | Spawns at table level regardless of input Y position.
<a class="anchor" id="Checkers-Board"></a>Checkers Board | [`Checker_Board`](#Checker_Board) | Spawns at table level regardless of input Y position.
<a class="anchor" id="Chess-Board"></a>Chess Board | [`Chess_Board`](#Chess_Board) | Spawns at table level regardless of input Y position.
<a class="anchor" id="Chinese-Checkers-Board"></a>Chinese Checkers Board | [`Chinese_Checkers_Board`](#Chinese_Checkers_Board) | Spawns at table level regardless of input Y position.
<a class="anchor" id="Custom-Board"></a>Custom Board | [`Custom_Board`](#Custom_Board) | Spawns at table level regardless of input Y position.

### Cards

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Standard-Deck"></a>Standard Deck | [`Deck`](#Deck) |
<a class="anchor" id="Custom-Deck"></a>Custom Deck | [`DeckCustom`](#DeckCustom) |
<a class="anchor" id="Random-Card"></a>Random Card | [`Card`](#Card) | Random `CardID` value between `0` and `51` (inclusive).
<a class="anchor" id="Joker"></a>Joker | [`Card`](#Card) | `CardID` value of `52`.
<a class="anchor" id="CardBots-Main-Deck"></a>CardBots Main Deck | [`Deck_CardBot_Main`](#Deck_CardBot_Main) |
<a class="anchor" id="CardBots-Head-Deck"></a>CardBots Head Deck | [`Deck_CardBot_Head`](#Deck_CardBot_Head) |

### Checkers

<a class="anchor" id="Type"></a>Type | Description
-- | --
<a class="anchor" id="Red-Checker"></a>Red Checker | [`Checker_red`](#Checker_red) |
<a class="anchor" id="Black-Checker"></a>Black Checker | [`Checker_black`](#Checker_black) |
<a class="anchor" id="White-Checker"></a>White Checker | [`Checker_white`](#Checker_white) |

### Chess

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Pawn-Chrome"></a>Pawn Chrome | [`Chess_Pawn`](#Chess_Pawn) | `MaterialIndex` value of `0`.
<a class="anchor" id="Rook-Chrome"></a>Rook Chrome | [`Chess_Rook`](#Chess_Rook) | `MaterialIndex` value of `0`.
<a class="anchor" id="Knight-Chrome"></a>Knight Chrome | [`Chess_Knight`](#Chess_Knight) | `MaterialIndex` value of `0`.
<a class="anchor" id="Bishop-Chrome"></a>Bishop Chrome | [`Chess_Bishop`](#Chess_Bishop) | `MaterialIndex` value of `0`.
<a class="anchor" id="Queen-Chrome"></a>Queen Chrome | [`Chess_Queen`](#Chess_Queen) | `MaterialIndex` value of `0`.
<a class="anchor" id="King-Chrome"></a>King Chrome | [`Chess_King`](#Chess_King) | `MaterialIndex` value of `0`.
<a class="anchor" id="Pawn-Cast-Iron"></a>Pawn Cast Iron | [`Chess_Pawn`](#Chess_Pawn) | `MaterialIndex` value of `1`.
<a class="anchor" id="Rook-Cast-Iron"></a>Rook Cast Iron | [`Chess_Rook`](#Chess_Rook) | `MaterialIndex` value of `1`.
<a class="anchor" id="Knight-Cast-Iron"></a>Knight Cast Iron | [`Chess_Knight`](#Chess_Knight) | `MaterialIndex` value of `1`.
<a class="anchor" id="Bishop-Cast-Iron"></a>Bishop Cast Iron | [`Chess_Bishop`](#Chess_Bishop) | `MaterialIndex` value of `1`.
<a class="anchor" id="Queen-Cast-Iron"></a>Queen Cast Iron | [`Chess_Queen`](#Chess_Queen) | `MaterialIndex` value of `1`.
<a class="anchor" id="King-Cast-Iron"></a>King Cast Iron | [`Chess_King`](#Chess_King) | `MaterialIndex` value of `1`.
<a class="anchor" id="Pawn-Light-Wood"></a>Pawn Light Wood | [`Chess_Pawn`](#Chess_Pawn) | `MaterialIndex` value of `2`.
<a class="anchor" id="Rook-Light-Wood"></a>Rook Light Wood | [`Chess_Rook`](#Chess_Rook) | `MaterialIndex` value of `2`.
<a class="anchor" id="Knight-Light-Wood"></a>Knight Light Wood | [`Chess_Knight`](#Chess_Knight) | `MaterialIndex` value of `2`.
<a class="anchor" id="Bishop-Light-Wood"></a>Bishop Light Wood | [`Chess_Bishop`](#Chess_Bishop) | `MaterialIndex` value of `2`.
<a class="anchor" id="Queen-Light-Wood"></a>Queen Light Wood | [`Chess_Queen`](#Chess_Queen) | `MaterialIndex` value of `2`.
<a class="anchor" id="King-Light-Wood"></a>King Light Wood | [`Chess_King`](#Chess_King) | `MaterialIndex` value of `2`.
<a class="anchor" id="Bishop-Dark-Wood"></a>Bishop Dark Wood | [`Chess_Bishop`](#Chess_Bishop) | `MaterialIndex` value of `3`.
<a class="anchor" id="King-Dark-Wood"></a>King Dark Wood | [`Chess_King`](#Chess_King) | `MaterialIndex` value of `3`.
<a class="anchor" id="Knight-Dark-Wood"></a>Knight Dark Wood | [`Chess_Knight`](#Chess_Knight) | `MaterialIndex` value of `3`.
<a class="anchor" id="Pawn-Dark-Wood"></a>Pawn Dark Wood | [`Chess_Pawn`](#Chess_Pawn) | `MaterialIndex` value of `3`.
<a class="anchor" id="Queen-Dark-Wood"></a>Queen Dark Wood | [`Chess_Queen`](#Chess_Queen) | `MaterialIndex` value of `3`.
<a class="anchor" id="Rook-Dark-Wood"></a>Rook Dark Wood | [`Chess_Rook`](#Chess_Rook) | `MaterialIndex` value of `3`.

### Custom

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Custom-Model"></a>Custom Model | [`Custom_Model`](#Custom_Model) |

### Dice

Name | Type | Differences
-- | -- | --
<a class="anchor" id="D4"></a>D4 | [`Die_4`](#Die_4) | `MaterialIndex` value of `0`.
<a class="anchor" id="D6"></a>D6 | [`Die_6`](#Die_6) | `MaterialIndex` value of `0`.
<a class="anchor" id="D8"></a>D8 | [`Die_8`](#Die_8) | `MaterialIndex` value of `0`.
<a class="anchor" id="D10"></a>D10 | [`Die_10`](#Die_10) | `MaterialIndex` value of `0`.
<a class="anchor" id="D12"></a>D12 | [`Die_12`](#Die_12) | `MaterialIndex` value of `0`.
<a class="anchor" id="D20"></a>D20 | [`Die_20`](#Die_20) | `MaterialIndex` value of `0`.
<a class="anchor" id="D6-Black"></a>D6 Black | [`Die_6_Rounded`](#Die_6_Rounded) | `MaterialIndex` value of `0`.
<a class="anchor" id="D6-Red"></a>D6 Red | [`Die_6_Rounded`](#Die_6_Rounded) | `MaterialIndex` value of `1`.
<a class="anchor" id="D6-Green"></a>D6 Green | [`Die_6_Rounded`](#Die_6_Rounded) | `MaterialIndex` value of `2`.
<a class="anchor" id="D6-Blue"></a>D6 Blue | [`Die_6_Rounded`](#Die_6_Rounded) | `MaterialIndex` value of `3`.
<a class="anchor" id="D4-Chrome"></a>D4 Chrome | [`Die_4`](#Die_4) | `MaterialIndex` value of `1`, `AltSound` value of `true`.
<a class="anchor" id="D6-Chrome"></a>D6 Chrome | [`Die_6`](#Die_6) | `MaterialIndex` value of `1`, `AltSound` value of `true`.
<a class="anchor" id="D8-Chrome"></a>D8 Chrome | [`Die_8`](#Die_8) | `MaterialIndex` value of `1`, `AltSound` value of `true`.
<a class="anchor" id="D10-Chrome"></a>D10 Chrome | [`Die_10`](#Die_10) | `MaterialIndex` value of `1`, `AltSound` value of `true`.
<a class="anchor" id="D12-Chrome"></a>D12 Chrome | [`Die_12`](#Die_12) | `MaterialIndex` value of `1`, `AltSound` value of `true`.
<a class="anchor" id="D20-Chrome"></a>D20 Chrome | [`Die_20`](#Die_20) | `MaterialIndex` value of `1`, `AltSound` value of `true`.

### Figurines

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Custom-Figurine"></a>Custom Figurine | [`Figurine_Custom`](#Figurine_Custom) |
<a class="anchor" id="Knight-of-Knil"></a>Knight of Knil | [`Figurine_Knil`](#Figurine_Knil) |
<a class="anchor" id="Kimi-Kat"></a>Kimi Kat | [`Figurine_Kimi_Kat`](#Figurine_Kimi_Kat) |
<a class="anchor" id="Sir-Loin"></a>Sir Loin | [`Figurine_Sir_Loin`](#Figurine_Sir_Loin) |
<a class="anchor" id="Mara"></a>Mara | [`Figurine_Mara`](#Figurine_Mara) |
<a class="anchor" id="Zomblor"></a>Zomblor | [`Figurine_Zomblor`](#Figurine_Zomblor) |
<a class="anchor" id="Zeke-Kodoku"></a>Zeke Kodoku | [`Figurine_Zeke`](#Figurine_Zeke) |
<a class="anchor" id="CardBot"></a>CardBot | [`Figurine_Card_Bot`](#Figurine_Card_Bot) |

### Go

Name | Type | Differences
-- | -- | --
<a class="anchor" id="GO-Piece-White"></a>GO Piece White | [`go_game_piece_white`](#go_game_piece_white) |
<a class="anchor" id="GO-Piece-Black"></a>GO Piece Black | [`go_game_piece_black`](#go_game_piece_black) |
<a class="anchor" id="GO-Bowl-White"></a>GO Bowl White | [`go_game_bowl_white`](#go_game_bowl_white) |
<a class="anchor" id="GO-Bowl-Black"></a>GO Bowl Black | [`go_game_bowl_black`](#go_game_bowl_black) |

### Marbles

Name | Type | Differences
-- | -- | --
<a class="anchor" id="White-Ball"></a>White Ball | [`Chinese_Checkers_Piece`](#Chinese_Checkers_Piece) | `MaterialIndex` value of `0`.
<a class="anchor" id="Red-Ball"></a>Red Ball | [`Chinese_Checkers_Piece`](#Chinese_Checkers_Piece) | `MaterialIndex` value of `1`.
<a class="anchor" id="Yellow-Ball"></a>Yellow Ball | [`Chinese_Checkers_Piece`](#Chinese_Checkers_Piece) | `MaterialIndex` value of `2`.
<a class="anchor" id="Green-Ball"></a>Green Ball | [`Chinese_Checkers_Piece`](#Chinese_Checkers_Piece) | `MaterialIndex` value of `3`.
<a class="anchor" id="Blue-Ball"></a>Blue Ball | [`Chinese_Checkers_Piece`](#Chinese_Checkers_Piece) | `MaterialIndex` value of `4`.
<a class="anchor" id="Pink-Ball"></a>Pink Ball | [`Chinese_Checkers_Piece`](#Chinese_Checkers_Piece) | `MaterialIndex` value of `5`.
<a class="anchor" id="Black-Ball"></a>Black Ball | [`Chinese_Checkers_Piece`](#Chinese_Checkers_Piece) | `MaterialIndex` value of `6`.

### Miscellaneous

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Quarter"></a>Quarter | [`Quarter`](#Quarter) |
<a class="anchor" id="Reversi-Chip"></a>Reversi Chip | [`reversi_chip`](#reversi_chip) |
<a class="anchor" id="Random-Domino"></a>Random Domino | [`Domino`](#Domino) | Random `MeshIndex` value between `0` and `27` (inclusive).
<a class="anchor" id="Random-Mahjong"></a>Random Mahjong | [`Mahjong_Tile`](#Mahjong_Tile) | Random `MeshIndex` value between `0` and `35` (inclusive).
<a class="anchor" id="Brown-Backgammon"></a>Brown Backgammon | [`backgammon_piece_brown`](#backgammon_piece_brown) |
<a class="anchor" id="White-Backgammon"></a>White Backgammon | [`backgammon_piece_white`](#backgammon_piece_white) |

### Piecepack

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Arms-Dice"></a>Arms Dice | [`Die_Piecepack`](#Die_Piecepack) | `MaterialIndex` value of `0`.
<a class="anchor" id="Crowns-Dice"></a>Crowns Dice | [`Die_Piecepack`](#Die_Piecepack) | `MaterialIndex` value of `1`.
<a class="anchor" id="Moons-Dice"></a>Moons Dice | [`Die_Piecepack`](#Die_Piecepack) | `MaterialIndex` value of `2`.
<a class="anchor" id="Suns-Dice"></a>Suns Dice | [`Die_Piecepack`](#Die_Piecepack) | `MaterialIndex` value of `3`.

### Player Pawns

Name | Type | Differences
-- | -- | --
<a class="anchor" id="White-Pawn"></a>White Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `0`.
<a class="anchor" id="Red-Pawn"></a>Red Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `1`.
<a class="anchor" id="Orange-Pawn"></a>Orange Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `2`.
<a class="anchor" id="Yellow-Pawn"></a>Yellow Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `3`.
<a class="anchor" id="Green-Pawn"></a>Green Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `4`.
<a class="anchor" id="Blue-Pawn"></a>Blue Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `5`.
<a class="anchor" id="Purple-Pawn"></a>Purple Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `6`.
<a class="anchor" id="Pink-Pawn"></a>Pink Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `7`.
<a class="anchor" id="Black-Pawn"></a>Black Pawn | [`PlayerPawn`](#PlayerPawn) | `MaterialIndex` value of `8`.

### Poker Chips

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Blue-10"></a>Blue 10 | [`Chip_10`](#Chip_10) |
<a class="anchor" id="Green-50"></a>Green 50 | [`Chip_50`](#Chip_50) |
<a class="anchor" id="Red-100"></a>Red 100 | [`Chip_100`](#Chip_100) |
<a class="anchor" id="Silver-500"></a>Silver 500 | [`Chip_500`](#Chip_500) |
<a class="anchor" id="Gold-1000"></a>Gold 1000 | [`Chip_1000`](#Chip_1000) |

### RPG Kit

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Bear"></a>Bear | [`rpg_BEAR`](#rpg_BEAR) |
<a class="anchor" id="Giant-Rat"></a>Giant Rat | [`rpg_RAT`](#rpg_RAT) |
<a class="anchor" id="Giant-Viper"></a>Giant Viper | [`rpg_GIANT_VIPER`](#rpg_GIANT_VIPER) |
<a class="anchor" id="Wolf"></a>Wolf | [`rpg_WOLF`](#rpg_WOLF) |
<a class="anchor" id="Evil-Watcher"></a>Evil Watcher | [`rpg_EVIL_WATCHER`](#rpg_EVIL_WATCHER) |
<a class="anchor" id="Golem"></a>Golem | [`rpg_GOLEM`](#rpg_GOLEM) |
<a class="anchor" id="Tree-Ent"></a>Tree Ent | [`rpg_TREE_ENT`](#rpg_TREE_ENT) |
<a class="anchor" id="Dragonide"></a>Dragonide | [`rpg_DRAGONIDE`](#rpg_DRAGONIDE) |
<a class="anchor" id="Hydra"></a>Hydra | [`rpg_HYDRA`](#rpg_HYDRA) |
<a class="anchor" id="Lizard-Warrior"></a>Lizard Warrior | [`rpg_LIZARD_WARRIOR`](#rpg_LIZARD_WARRIOR) |
<a class="anchor" id="Wyvern"></a>Wyvern | [`rpg_WYVERN`](#rpg_WYVERN) |
<a class="anchor" id="Ghoul"></a>Ghoul | [`rpg_GHOUL`](#rpg_GHOUL) |
<a class="anchor" id="Mummy"></a>Mummy | [`rpg_MUMMY`](#rpg_MUMMY) |
<a class="anchor" id="Skeleton-Knight"></a>Skeleton Knight | [`rpg_SKELETON_KNIGHT`](#rpg_SKELETON_KNIGHT) |
<a class="anchor" id="Vampire"></a>Vampire | [`rpg_VAMPIRE`](#rpg_VAMPIRE) |
<a class="anchor" id="Cyclops"></a>Cyclops | [`rpg_CYCLOP`](#rpg_CYCLOP) |
<a class="anchor" id="Goblin"></a>Goblin | [`rpg_GOBLIN`](#rpg_GOBLIN) |
<a class="anchor" id="Kobold"></a>Kobold | [`rpg_KOBOLD`](#rpg_KOBOLD) |
<a class="anchor" id="Ogre"></a>Ogre | [`rpg_OGRE`](#rpg_OGRE) |
<a class="anchor" id="Orc"></a>Orc | [`rpg_ORC`](#rpg_ORC) |
<a class="anchor" id="Troll"></a>Troll | [`rpg_TROLL`](#rpg_TROLL) |
<a class="anchor" id="Chimera"></a>Chimera | [`rpg_CHIMERA`](#rpg_CHIMERA) |
<a class="anchor" id="Griffon"></a>Griffon | [`rpg_GRIFFON`](#rpg_GRIFFON) |
<a class="anchor" id="Manticora"></a>Manticora | [`rpg_MANTICORA`](#rpg_MANTICORA) |
<a class="anchor" id="Werewolf"></a>Werewolf | [`rpg_WEREWOLF`](#rpg_WEREWOLF) |
<a class="anchor" id="Floor"></a>Floor | [`Tileset_Floor`](#Tileset_Floor) |
<a class="anchor" id="Wall"></a>Wall | [`Tileset_Wall`](#Tileset_Wall) |
<a class="anchor" id="Corner"></a>Corner | [`Tileset_Corner`](#Tileset_Corner) |
<a class="anchor" id="Chest"></a>Chest | [`Tileset_Chest`](#Tileset_Chest) |
<a class="anchor" id="Barrel"></a>Barrel | [`Tileset_Barrel`](#Tileset_Barrel) |
<a class="anchor" id="Table"></a>Table | [`Tileset_Table`](#Tileset_Table) |
<a class="anchor" id="Chair"></a>Chair | [`Tileset_Chair`](#Tileset_Chair) |
<a class="anchor" id="Tree"></a>Tree | [`Tileset_Tree`](#Tileset_Tree) |
<a class="anchor" id="Rock"></a>Rock | [`Tileset_Rock`](#Tileset_Rock) |

### Tools

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Tablet"></a>Tablet | [`Tablet`](#Tablet) |
<a class="anchor" id="Digital-Clock"></a>Digital Clock | [`Digital_Clock`](#Digital_Clock) |
<a class="anchor" id="Loot-Bag"></a>Loot Bag | [`Bag`](#Bag) |

### Unlisted

Name | Type | Differences
-- | -- | --
<a class="anchor" id="Go-Board"></a>Go Board | [`Go_Board`](#Go_Board) | Spawns at table level regardless of input Y position.
<a class="anchor" id="Pachisi-Board"></a>Pachisi Board | [`Pachisi_board`](#Pachisi_board) | Spawns at table level regardless of input Y position.
<a class="anchor" id="Reversi-Board"></a>Reversi Board | [`reversi_board`](#reversi_board) | Spawns at table level regardless of input Y position.
