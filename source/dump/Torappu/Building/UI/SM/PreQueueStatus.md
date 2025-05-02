# PreQueueStatus

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Avail |

| 1 | EmptyQueue |

| 2 | HasTired |

| 4 | HasWorkInOtherRoom |

| 8 | IsTraining |

| 16 | SameAsCurRoom |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public enum PreQueueStatus
{
	public Int32 value__; // 0x10
	public const PreQueueStatus Avail = 0; // 0x0
	public const PreQueueStatus EmptyQueue = 1; // 0x0
	public const PreQueueStatus HasTired = 2; // 0x0
	public const PreQueueStatus HasWorkInOtherRoom = 4; // 0x0
	public const PreQueueStatus IsTraining = 8; // 0x0
	public const PreQueueStatus SameAsCurRoom = 16; // 0x0


}
```