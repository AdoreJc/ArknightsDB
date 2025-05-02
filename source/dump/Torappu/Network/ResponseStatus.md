# ResponseStatus

**Namespace:** `Torappu.Network`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | OK |

| 1 | ERROR_IGNORE |

| 2 | ERROR_RETRY |

| 3 | ERROR_SYNC_DATA |

| 4 | ERROR_RELOGIN |

| 5 | ERROR_TIMEOUT |

| 6 | ERROR_CLIENT |

| 7 | CANCEL |

| 8 | ERROR_SECURE_SYS |

| 9 | ERROR_UNKNOW |

## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public enum ResponseStatus
{
	public Int32 value__; // 0x10
	public const ResponseStatus OK = 0; // 0x0
	public const ResponseStatus ERROR_IGNORE = 1; // 0x0
	public const ResponseStatus ERROR_RETRY = 2; // 0x0
	public const ResponseStatus ERROR_SYNC_DATA = 3; // 0x0
	public const ResponseStatus ERROR_RELOGIN = 4; // 0x0
	public const ResponseStatus ERROR_TIMEOUT = 5; // 0x0
	public const ResponseStatus ERROR_CLIENT = 6; // 0x0
	public const ResponseStatus CANCEL = 7; // 0x0
	public const ResponseStatus ERROR_SECURE_SYS = 8; // 0x0
	public const ResponseStatus ERROR_UNKNOW = 9; // 0x0


}
```