# HTTPRequestStates

**Namespace:** `BestHTTP`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Initial |

| 1 | Queued |

| 2 | Processing |

| 3 | Finished |

| 4 | Error |

| 5 | Aborted |

| 6 | ConnectionTimedOut |

| 7 | TimedOut |

## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP
public enum HTTPRequestStates
{
	public Int32 value__; // 0x10
	public const HTTPRequestStates Initial = 0; // 0x0
	public const HTTPRequestStates Queued = 1; // 0x0
	public const HTTPRequestStates Processing = 2; // 0x0
	public const HTTPRequestStates Finished = 3; // 0x0
	public const HTTPRequestStates Error = 4; // 0x0
	public const HTTPRequestStates Aborted = 5; // 0x0
	public const HTTPRequestStates ConnectionTimedOut = 6; // 0x0
	public const HTTPRequestStates TimedOut = 7; // 0x0


}
```