# TraceEventType

**Namespace:** `System.Diagnostics`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | Critical |

| 2 | Error |

| 4 | Warning |

| 8 | Information |

| 16 | Verbose |

| 256 | Start |

| 512 | Stop |

| 1024 | Suspend |

| 2048 | Resume |

| 4096 | Transfer |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
public enum TraceEventType
{
	public Int32 value__; // 0x10
	public const TraceEventType Critical = 1; // 0x0
	public const TraceEventType Error = 2; // 0x0
	public const TraceEventType Warning = 4; // 0x0
	public const TraceEventType Information = 8; // 0x0
	public const TraceEventType Verbose = 16; // 0x0
	public const TraceEventType Start = 256; // 0x0
	public const TraceEventType Stop = 512; // 0x0
	public const TraceEventType Suspend = 1024; // 0x0
	public const TraceEventType Resume = 2048; // 0x0
	public const TraceEventType Transfer = 4096; // 0x0


}
```