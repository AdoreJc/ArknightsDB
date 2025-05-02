# TaskCreationOptions

**Namespace:** `System.Threading.Tasks`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | PreferFairness |

| 2 | LongRunning |

| 4 | AttachedToParent |

| 8 | DenyChildAttach |

| 16 | HideScheduler |

| 64 | RunContinuationsAsynchronously |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public enum TaskCreationOptions
{
	public Int32 value__; // 0x10
	public const TaskCreationOptions None = 0; // 0x0
	public const TaskCreationOptions PreferFairness = 1; // 0x0
	public const TaskCreationOptions LongRunning = 2; // 0x0
	public const TaskCreationOptions AttachedToParent = 4; // 0x0
	public const TaskCreationOptions DenyChildAttach = 8; // 0x0
	public const TaskCreationOptions HideScheduler = 16; // 0x0
	public const TaskCreationOptions RunContinuationsAsynchronously = 64; // 0x0


}
```