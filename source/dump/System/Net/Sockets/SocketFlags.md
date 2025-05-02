# SocketFlags

**Namespace:** `System.Net.Sockets`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | OutOfBand |

| 2 | Peek |

| 4 | DontRoute |

| 16 | MaxIOVectorLength |

| 256 | Truncated |

| 512 | ControlDataTruncated |

| 1024 | Broadcast |

| 2048 | Multicast |

| 32768 | Partial |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public enum SocketFlags
{
	public Int32 value__; // 0x10
	public const SocketFlags None = 0; // 0x0
	public const SocketFlags OutOfBand = 1; // 0x0
	public const SocketFlags Peek = 2; // 0x0
	public const SocketFlags DontRoute = 4; // 0x0
	public const SocketFlags MaxIOVectorLength = 16; // 0x0
	public const SocketFlags Truncated = 256; // 0x0
	public const SocketFlags ControlDataTruncated = 512; // 0x0
	public const SocketFlags Broadcast = 1024; // 0x0
	public const SocketFlags Multicast = 2048; // 0x0
	public const SocketFlags Partial = 32768; // 0x0


}
```