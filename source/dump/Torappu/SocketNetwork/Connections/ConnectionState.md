# ConnectionState

**Namespace:** `Torappu.SocketNetwork.Connections`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 4294967295 | NOT_EXIST_STATE |

| 0 | NULL |

| 1 | CONNECTING |

| 2 | CONNECTED |

| 3 | CONNECTED_FAILED |

| 4 | FAILED |

| 5 | ERROR |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork.Connections
public enum ConnectionState
{
	public Int32 value__; // 0x10
	public const ConnectionState NOT_EXIST_STATE = 4294967295; // 0x0
	public const ConnectionState NULL = 0; // 0x0
	public const ConnectionState CONNECTING = 1; // 0x0
	public const ConnectionState CONNECTED = 2; // 0x0
	public const ConnectionState CONNECTED_FAILED = 3; // 0x0
	public const ConnectionState FAILED = 4; // 0x0
	public const ConnectionState ERROR = 5; // 0x0


}
```