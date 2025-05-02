# PayConfirmStatus

**Namespace:** `U8.SDK`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | FAILED |

| 1 | THIRD_PARTY_PENDING |

| 2 | GAME_SERVER_PENDING |

| 3 | SUCCEED |

| 4 | ORDER_NOT_EXIST |

## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public enum PayConfirmStatus
{
	public Int32 value__; // 0x10
	public const PayConfirmStatus FAILED = 0; // 0x0
	public const PayConfirmStatus THIRD_PARTY_PENDING = 1; // 0x0
	public const PayConfirmStatus GAME_SERVER_PENDING = 2; // 0x0
	public const PayConfirmStatus SUCCEED = 3; // 0x0
	public const PayConfirmStatus ORDER_NOT_EXIST = 4; // 0x0


}
```