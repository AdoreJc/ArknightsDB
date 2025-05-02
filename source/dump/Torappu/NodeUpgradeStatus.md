# NodeUpgradeStatus

**Namespace:** `Torappu`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NONE |

| 1 | PERM_UPGRADE |

| 2 | CAN_PERM_UPGRADE |

| 3 | TEMP_UPGRADE |

| 4 | CAN_TEMP_UPGRADE |

| 5 | TEMP_UPGRADED |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public enum NodeUpgradeStatus
{
	public Int32 value__; // 0x10
	public const NodeUpgradeStatus NONE = 0; // 0x0
	public const NodeUpgradeStatus PERM_UPGRADE = 1; // 0x0
	public const NodeUpgradeStatus CAN_PERM_UPGRADE = 2; // 0x0
	public const NodeUpgradeStatus TEMP_UPGRADE = 3; // 0x0
	public const NodeUpgradeStatus CAN_TEMP_UPGRADE = 4; // 0x0
	public const NodeUpgradeStatus TEMP_UPGRADED = 5; // 0x0


}
```