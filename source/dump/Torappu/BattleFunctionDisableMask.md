# BattleFunctionDisableMask

**Namespace:** `Torappu`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NONE |

| 1 | CARD_LIST |

| 2 | CHARACTER_MENU |

| 4 | CHARACTER_INFO |

| 8 | SYSTEM_MENU |

| 16 | PAUSE_BUTTON |

| 32 | SPEED_SWITCHER_BUTTON |

| 64 | BATTLE_STATUS |

| 128 | COST_PANEL |

| 256 | SLOW_MOTION |

| 512 | PAUSE_BUTTON_INTERACT |

| 1024 | SYSTEM_MENU_INTERACT |

| 2048 | SPEED_SWITCHER_BUTTON_INTERACT |

| 4096 | UNIT_HUD_SKILL_CAST_MASK |

| 8192 | WITHDRAWABLE_PANEL |

| 16384 | COST_PANEL_KEEP_CHARACTERLIMIT |

| 32768 | CHARACTER_LIMIT |

| 65536 | AUTOCHESS_SELL_OR_DESTORY |

| 131072 | CHARACTER_MENU_PANEL |

| 262143 | ALL |

## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public enum BattleFunctionDisableMask
{
	public Int32 value__; // 0x10
	public const BattleFunctionDisableMask NONE = 0; // 0x0
	public const BattleFunctionDisableMask CARD_LIST = 1; // 0x0
	public const BattleFunctionDisableMask CHARACTER_MENU = 2; // 0x0
	public const BattleFunctionDisableMask CHARACTER_INFO = 4; // 0x0
	public const BattleFunctionDisableMask SYSTEM_MENU = 8; // 0x0
	public const BattleFunctionDisableMask PAUSE_BUTTON = 16; // 0x0
	public const BattleFunctionDisableMask SPEED_SWITCHER_BUTTON = 32; // 0x0
	public const BattleFunctionDisableMask BATTLE_STATUS = 64; // 0x0
	public const BattleFunctionDisableMask COST_PANEL = 128; // 0x0
	public const BattleFunctionDisableMask SLOW_MOTION = 256; // 0x0
	public const BattleFunctionDisableMask PAUSE_BUTTON_INTERACT = 512; // 0x0
	public const BattleFunctionDisableMask SYSTEM_MENU_INTERACT = 1024; // 0x0
	public const BattleFunctionDisableMask SPEED_SWITCHER_BUTTON_INTERACT = 2048; // 0x0
	public const BattleFunctionDisableMask UNIT_HUD_SKILL_CAST_MASK = 4096; // 0x0
	public const BattleFunctionDisableMask WITHDRAWABLE_PANEL = 8192; // 0x0
	public const BattleFunctionDisableMask COST_PANEL_KEEP_CHARACTERLIMIT = 16384; // 0x0
	public const BattleFunctionDisableMask CHARACTER_LIMIT = 32768; // 0x0
	public const BattleFunctionDisableMask AUTOCHESS_SELL_OR_DESTORY = 65536; // 0x0
	public const BattleFunctionDisableMask CHARACTER_MENU_PANEL = 131072; // 0x0
	public const BattleFunctionDisableMask ALL = 262143; // 0x0


}
```