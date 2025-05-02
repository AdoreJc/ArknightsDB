# StreamingContextStates

**Namespace:** `System.Runtime.Serialization`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | CrossProcess |

| 2 | CrossMachine |

| 4 | File |

| 8 | Persistence |

| 16 | Remoting |

| 32 | Other |

| 64 | Clone |

| 128 | CrossAppDomain |

| 255 | All |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization
public enum StreamingContextStates
{
	public Int32 value__; // 0x10
	public const StreamingContextStates CrossProcess = 1; // 0x0
	public const StreamingContextStates CrossMachine = 2; // 0x0
	public const StreamingContextStates File = 4; // 0x0
	public const StreamingContextStates Persistence = 8; // 0x0
	public const StreamingContextStates Remoting = 16; // 0x0
	public const StreamingContextStates Other = 32; // 0x0
	public const StreamingContextStates Clone = 64; // 0x0
	public const StreamingContextStates CrossAppDomain = 128; // 0x0
	public const StreamingContextStates All = 255; // 0x0


}
```