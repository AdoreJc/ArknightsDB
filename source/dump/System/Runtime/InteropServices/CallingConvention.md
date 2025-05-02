# CallingConvention

**Namespace:** `System.Runtime.InteropServices`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | Winapi |

| 2 | Cdecl |

| 3 | StdCall |

| 4 | ThisCall |

| 5 | FastCall |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.InteropServices
public enum CallingConvention
{
	public Int32 value__; // 0x10
	public const CallingConvention Winapi = 1; // 0x0
	public const CallingConvention Cdecl = 2; // 0x0
	public const CallingConvention StdCall = 3; // 0x0
	public const CallingConvention ThisCall = 4; // 0x0
	public const CallingConvention FastCall = 5; // 0x0


}
```