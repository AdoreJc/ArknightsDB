# SocketOptionLevel

**Namespace:** `System.Net.Sockets`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 65535 | Socket |

| 0 | IP |

| 41 | IPv6 |

| 6 | Tcp |

| 17 | Udp |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public enum SocketOptionLevel
{
	public Int32 value__; // 0x10
	public const SocketOptionLevel Socket = 65535; // 0x0
	public const SocketOptionLevel IP = 0; // 0x0
	public const SocketOptionLevel IPv6 = 41; // 0x0
	public const SocketOptionLevel Tcp = 6; // 0x0
	public const SocketOptionLevel Udp = 17; // 0x0


}
```