# HTTPConnectionStates

**Namespace:** `BestHTTP`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Initial |

| 1 | Processing |

| 2 | Redirected |

| 3 | Upgraded |

| 4 | WaitForProtocolShutdown |

| 5 | WaitForRecycle |

| 6 | Free |

| 7 | AbortRequested |

| 8 | TimedOut |

| 9 | Closed |

## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP
internal enum HTTPConnectionStates
{
	public Int32 value__; // 0x10
	public const HTTPConnectionStates Initial = 0; // 0x0
	public const HTTPConnectionStates Processing = 1; // 0x0
	public const HTTPConnectionStates Redirected = 2; // 0x0
	public const HTTPConnectionStates Upgraded = 3; // 0x0
	public const HTTPConnectionStates WaitForProtocolShutdown = 4; // 0x0
	public const HTTPConnectionStates WaitForRecycle = 5; // 0x0
	public const HTTPConnectionStates Free = 6; // 0x0
	public const HTTPConnectionStates AbortRequested = 7; // 0x0
	public const HTTPConnectionStates TimedOut = 8; // 0x0
	public const HTTPConnectionStates Closed = 9; // 0x0


}
```