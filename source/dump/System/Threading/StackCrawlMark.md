# StackCrawlMark

**Namespace:** `System.Threading`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | LookForMe |

| 1 | LookForMyCaller |

| 2 | LookForMyCallersCaller |

| 3 | LookForThread |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
internal enum StackCrawlMark
{
	public Int32 value__; // 0x10
	public const StackCrawlMark LookForMe = 0; // 0x0
	public const StackCrawlMark LookForMyCaller = 1; // 0x0
	public const StackCrawlMark LookForMyCallersCaller = 2; // 0x0
	public const StackCrawlMark LookForThread = 3; // 0x0


}
```