# InternalTaskOptions

**Namespace:** `System.Threading.Tasks`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 65280 | InternalOptionsMask |

| 512 | ContinuationTask |

| 1024 | PromiseTask |

| 4096 | LazyCancellation |

| 8192 | QueuedByRuntime |

| 16384 | DoNotDispose |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
internal enum InternalTaskOptions
{
	public Int32 value__; // 0x10
	public const InternalTaskOptions None = 0; // 0x0
	public const InternalTaskOptions InternalOptionsMask = 65280; // 0x0
	public const InternalTaskOptions ContinuationTask = 512; // 0x0
	public const InternalTaskOptions PromiseTask = 1024; // 0x0
	public const InternalTaskOptions LazyCancellation = 4096; // 0x0
	public const InternalTaskOptions QueuedByRuntime = 8192; // 0x0
	public const InternalTaskOptions DoNotDispose = 16384; // 0x0


}
```