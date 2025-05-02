# CheckpointType

**Namespace:** `Torappu`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | MOVE |

| 1 | WAIT_FOR_SECONDS |

| 2 | WAIT_FOR_PLAY_TIME |

| 3 | WAIT_CURRENT_FRAGMENT_TIME |

| 4 | WAIT_CURRENT_WAVE_TIME |

| 5 | DISAPPEAR |

| 6 | APPEAR_AT_POS |

| 7 | ALERT |

| 8 | PATROL_MOVE |

| 9 | WAIT_BOSSRUSH_WAVE |

| 10 | INVALID |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public enum CheckpointType
{
	public Int32 value__; // 0x10
	public const CheckpointType MOVE = 0; // 0x0
	public const CheckpointType WAIT_FOR_SECONDS = 1; // 0x0
	public const CheckpointType WAIT_FOR_PLAY_TIME = 2; // 0x0
	public const CheckpointType WAIT_CURRENT_FRAGMENT_TIME = 3; // 0x0
	public const CheckpointType WAIT_CURRENT_WAVE_TIME = 4; // 0x0
	public const CheckpointType DISAPPEAR = 5; // 0x0
	public const CheckpointType APPEAR_AT_POS = 6; // 0x0
	public const CheckpointType ALERT = 7; // 0x0
	public const CheckpointType PATROL_MOVE = 8; // 0x0
	public const CheckpointType WAIT_BOSSRUSH_WAVE = 9; // 0x0
	public const CheckpointType INVALID = 10; // 0x0


}
```