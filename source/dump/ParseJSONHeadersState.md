# ParseJSONHeadersState

**Namespace:** ` `


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Begin |

| 1 | FindKey |

| 2 | ReadKey |

| 3 | FindColon |

| 4 | FindValue |

| 5 | ReadValue |

| 6 | FindComma |

| 7 | Finished |

| 8 | Failed |

## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
private enum ParseJSONHeadersState
{
	public Int32 value__; // 0x10
	public const ParseJSONHeadersState Begin = 0; // 0x0
	public const ParseJSONHeadersState FindKey = 1; // 0x0
	public const ParseJSONHeadersState ReadKey = 2; // 0x0
	public const ParseJSONHeadersState FindColon = 3; // 0x0
	public const ParseJSONHeadersState FindValue = 4; // 0x0
	public const ParseJSONHeadersState ReadValue = 5; // 0x0
	public const ParseJSONHeadersState FindComma = 6; // 0x0
	public const ParseJSONHeadersState Finished = 7; // 0x0
	public const ParseJSONHeadersState Failed = 8; // 0x0


}
```