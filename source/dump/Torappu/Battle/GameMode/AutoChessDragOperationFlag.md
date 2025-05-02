# AutoChessDragOperationFlag

**Namespace:** `Torappu.Battle.GameMode`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NONE |

| 2 | IS_START_BATTLE |

| 4 | IS_END_BATTLE |

| 8 | IS_START_VALID_HAND |

| 16 | IS_END_VALID_HAND |

| 32 | IS_START_HAND |

| 64 | IS_END_HAND |

| 128 | END_CONTAINS_TARGET |

| 256 | START_CONTAINS_TOKEN_POS |

| 512 | END_CONTAINS_TOKEN_POS |

| 1022 | ALL |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.GameMode
public enum AutoChessDragOperationFlag
{
	public Int32 value__; // 0x10
	public const AutoChessDragOperationFlag NONE = 0; // 0x0
	public const AutoChessDragOperationFlag IS_START_BATTLE = 2; // 0x0
	public const AutoChessDragOperationFlag IS_END_BATTLE = 4; // 0x0
	public const AutoChessDragOperationFlag IS_START_VALID_HAND = 8; // 0x0
	public const AutoChessDragOperationFlag IS_END_VALID_HAND = 16; // 0x0
	public const AutoChessDragOperationFlag IS_START_HAND = 32; // 0x0
	public const AutoChessDragOperationFlag IS_END_HAND = 64; // 0x0
	public const AutoChessDragOperationFlag END_CONTAINS_TARGET = 128; // 0x0
	public const AutoChessDragOperationFlag START_CONTAINS_TOKEN_POS = 256; // 0x0
	public const AutoChessDragOperationFlag END_CONTAINS_TOKEN_POS = 512; // 0x0
	public const AutoChessDragOperationFlag ALL = 1022; // 0x0


}
```