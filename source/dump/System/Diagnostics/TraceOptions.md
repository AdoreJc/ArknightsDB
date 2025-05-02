# TraceOptions

**Namespace:** `System.Diagnostics`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | LogicalOperationStack |

| 2 | DateTime |

| 4 | Timestamp |

| 8 | ProcessId |

| 16 | ThreadId |

| 32 | Callstack |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
public enum TraceOptions
{
	public Int32 value__; // 0x10
	public const TraceOptions None = 0; // 0x0
	public const TraceOptions LogicalOperationStack = 1; // 0x0
	public const TraceOptions DateTime = 2; // 0x0
	public const TraceOptions Timestamp = 4; // 0x0
	public const TraceOptions ProcessId = 8; // 0x0
	public const TraceOptions ThreadId = 16; // 0x0
	public const TraceOptions Callstack = 32; // 0x0


}
```