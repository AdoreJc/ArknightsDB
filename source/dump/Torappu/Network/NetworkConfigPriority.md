# NetworkConfigPriority

**Namespace:** `Torappu.Network`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | LOWEST |

| 1 | SDK_INJECTED |

| 2 | NETWORK_ROUTER |

| 3 | FORTRESS_CONFIG |

| 4 | TEST_CONFIG |

| 5 | HIGHEST |

## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public enum NetworkConfigPriority
{
	public Int32 value__; // 0x10
	public const NetworkConfigPriority LOWEST = 0; // 0x0
	public const NetworkConfigPriority SDK_INJECTED = 1; // 0x0
	public const NetworkConfigPriority NETWORK_ROUTER = 2; // 0x0
	public const NetworkConfigPriority FORTRESS_CONFIG = 3; // 0x0
	public const NetworkConfigPriority TEST_CONFIG = 4; // 0x0
	public const NetworkConfigPriority HIGHEST = 5; // 0x0


}
```