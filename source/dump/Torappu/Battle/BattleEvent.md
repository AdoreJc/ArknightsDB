# BattleEvent

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | ON_GAME_READY |

| 1 | ON_GAME_PRE_START |

| 2 | ON_GAME_START |

| 3 | ON_GAME_OVER |

| 4 | ON_UNIT_POST_INIT |

| 5 | ON_UNIT_BORN |

| 6 | ON_UNIT_FINISH |

| 7 | ON_ENEMY_REACHED_EXIT |

| 8 | ON_ENEMY_RECYCLED |

| 9 | ON_BOSS_ENTER |

| 10 | ON_GIANTBOSS_INIT |

| 11 | ON_CHARACTER_LOCATE |

| 12 | ON_BEFORE_APPLYING_MODIFIER |

| 13 | ON_APPLYING_MODIFIER |

| 14 | ON_APPLIED_MODIFIER |

| 15 | ON_ABILITY_CASTED |

| 16 | ON_STATE_CHANGED |

| 17 | ON_PAUSE_TOGGLED |

| 18 | ON_AUTO_REPLAY_TOGGLED |

| 19 | ON_AUTO_REPLAY_FINISHED |

| 20 | ON_SPEED_LEVEL_CHANGED |

| 21 | ON_PREDEFINED_LOCATION_REACHED |

| 22 | ON_DISPLAY_ENEMY_INFO |

| 23 | ON_BLOCK_ANY_ROUTES |

| 24 | ON_PREVIEW_CURSOR_SPAWND |

| 25 | ON_SKILL_CASTED |

| 26 | ON_CHARACTER_ATK_OR_CBT |

| 27 | ON_ACTIVATE_INTERNAL_HIDDEN_CARD |

| 28 | ON_RALLYPOINT_REBORN |

| 29 | ON_RALLYPOINT_DEAD |

| 30 | ON_RALLYPOINTLIKE_SWITCH |

| 31 | ON_SNAP_SHOT |

| 32 | ON_PLAYER_OPERATION |

| 33 | ON_GAME_GIVE_UP |

| 34 | ON_LIFE_POINT_CHANGED |

| 35 | ON_UNIT_SWITCH_SIDE |

| 36 | ON_UNIT_REPLACED |

| 37 | ON_WAVE_WILL_FINISH |

| 38 | ON_SPECIAL_UI_TRIGGER |

| 39 | ON_DISPLAY_LEGION_BLAST_CARD |

| 40 | ON_DISPLAY_DECK_BUFF_EFFECT |

| 41 | ON_DIALOGUE_START |

| 42 | ON_ATTACK_RANGE_UPDATED |

| 43 | ON_UNIT_REBORN |

| 44 | ON_WAVE_WILL_START |

| 45 | ON_DUMMY_LOCATE |

| 46 | ON_COOPERATE_LEVEL_UP |

| 47 | ON_COOPERATE_PLAYER_LIFE_TO_ZERO |

| 48 | ON_COOPERATE_PLAYER_REVIVE |

| 49 | ON_BATTLE_CTRL_DISPOSE |

| 50 | ON_DECK_CREATED |

| 51 | ON_GAMECITY_SCORE_CHANGE |

| 52 | ON_BEFORE_LEVEL_ACTION_EXECUTE |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public enum BattleEvent
{
	public Int32 value__; // 0x10
	public const BattleEvent ON_GAME_READY = 0; // 0x0
	public const BattleEvent ON_GAME_PRE_START = 1; // 0x0
	public const BattleEvent ON_GAME_START = 2; // 0x0
	public const BattleEvent ON_GAME_OVER = 3; // 0x0
	public const BattleEvent ON_UNIT_POST_INIT = 4; // 0x0
	public const BattleEvent ON_UNIT_BORN = 5; // 0x0
	public const BattleEvent ON_UNIT_FINISH = 6; // 0x0
	public const BattleEvent ON_ENEMY_REACHED_EXIT = 7; // 0x0
	public const BattleEvent ON_ENEMY_RECYCLED = 8; // 0x0
	public const BattleEvent ON_BOSS_ENTER = 9; // 0x0
	public const BattleEvent ON_GIANTBOSS_INIT = 10; // 0x0
	public const BattleEvent ON_CHARACTER_LOCATE = 11; // 0x0
	public const BattleEvent ON_BEFORE_APPLYING_MODIFIER = 12; // 0x0
	public const BattleEvent ON_APPLYING_MODIFIER = 13; // 0x0
	public const BattleEvent ON_APPLIED_MODIFIER = 14; // 0x0
	public const BattleEvent ON_ABILITY_CASTED = 15; // 0x0
	public const BattleEvent ON_STATE_CHANGED = 16; // 0x0
	public const BattleEvent ON_PAUSE_TOGGLED = 17; // 0x0
	public const BattleEvent ON_AUTO_REPLAY_TOGGLED = 18; // 0x0
	public const BattleEvent ON_AUTO_REPLAY_FINISHED = 19; // 0x0
	public const BattleEvent ON_SPEED_LEVEL_CHANGED = 20; // 0x0
	public const BattleEvent ON_PREDEFINED_LOCATION_REACHED = 21; // 0x0
	public const BattleEvent ON_DISPLAY_ENEMY_INFO = 22; // 0x0
	public const BattleEvent ON_BLOCK_ANY_ROUTES = 23; // 0x0
	public const BattleEvent ON_PREVIEW_CURSOR_SPAWND = 24; // 0x0
	public const BattleEvent ON_SKILL_CASTED = 25; // 0x0
	public const BattleEvent ON_CHARACTER_ATK_OR_CBT = 26; // 0x0
	public const BattleEvent ON_ACTIVATE_INTERNAL_HIDDEN_CARD = 27; // 0x0
	public const BattleEvent ON_RALLYPOINT_REBORN = 28; // 0x0
	public const BattleEvent ON_RALLYPOINT_DEAD = 29; // 0x0
	public const BattleEvent ON_RALLYPOINTLIKE_SWITCH = 30; // 0x0
	public const BattleEvent ON_SNAP_SHOT = 31; // 0x0
	public const BattleEvent ON_PLAYER_OPERATION = 32; // 0x0
	public const BattleEvent ON_GAME_GIVE_UP = 33; // 0x0
	public const BattleEvent ON_LIFE_POINT_CHANGED = 34; // 0x0
	public const BattleEvent ON_UNIT_SWITCH_SIDE = 35; // 0x0
	public const BattleEvent ON_UNIT_REPLACED = 36; // 0x0
	public const BattleEvent ON_WAVE_WILL_FINISH = 37; // 0x0
	public const BattleEvent ON_SPECIAL_UI_TRIGGER = 38; // 0x0
	public const BattleEvent ON_DISPLAY_LEGION_BLAST_CARD = 39; // 0x0
	public const BattleEvent ON_DISPLAY_DECK_BUFF_EFFECT = 40; // 0x0
	public const BattleEvent ON_DIALOGUE_START = 41; // 0x0
	public const BattleEvent ON_ATTACK_RANGE_UPDATED = 42; // 0x0
	public const BattleEvent ON_UNIT_REBORN = 43; // 0x0
	public const BattleEvent ON_WAVE_WILL_START = 44; // 0x0
	public const BattleEvent ON_DUMMY_LOCATE = 45; // 0x0
	public const BattleEvent ON_COOPERATE_LEVEL_UP = 46; // 0x0
	public const BattleEvent ON_COOPERATE_PLAYER_LIFE_TO_ZERO = 47; // 0x0
	public const BattleEvent ON_COOPERATE_PLAYER_REVIVE = 48; // 0x0
	public const BattleEvent ON_BATTLE_CTRL_DISPOSE = 49; // 0x0
	public const BattleEvent ON_DECK_CREATED = 50; // 0x0
	public const BattleEvent ON_GAMECITY_SCORE_CHANGE = 51; // 0x0
	public const BattleEvent ON_BEFORE_LEVEL_ACTION_EXECUTE = 52; // 0x0


}
```