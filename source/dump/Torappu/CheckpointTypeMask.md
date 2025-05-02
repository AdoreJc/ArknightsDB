# CheckpointTypeMask

**Namespace:** `Torappu`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | MOVE |

| 2 | WAIT_FOR_SECONDS |

| 4 | WAIT_FOR_PLAY_TIME |

| 8 | WAIT_CURRENT_FRAGMENT_TIME |

| 16 | WAIT_CURRENT_WAVE_TIME |

| 32 | DISAPPEAR |

| 64 | APPEAR_AT_POS |

| 128 | ALERT |

| 256 | PATROL_MOVE |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public enum CheckpointTypeMask
{
	public Int32 value__; // 0x10
	public const CheckpointTypeMask MOVE = 1; // 0x0
	public const CheckpointTypeMask WAIT_FOR_SECONDS = 2; // 0x0
	public const CheckpointTypeMask WAIT_FOR_PLAY_TIME = 4; // 0x0
	public const CheckpointTypeMask WAIT_CURRENT_FRAGMENT_TIME = 8; // 0x0
	public const CheckpointTypeMask WAIT_CURRENT_WAVE_TIME = 16; // 0x0
	public const CheckpointTypeMask DISAPPEAR = 32; // 0x0
	public const CheckpointTypeMask APPEAR_AT_POS = 64; // 0x0
	public const CheckpointTypeMask ALERT = 128; // 0x0
	public const CheckpointTypeMask PATROL_MOVE = 256; // 0x0


}
```