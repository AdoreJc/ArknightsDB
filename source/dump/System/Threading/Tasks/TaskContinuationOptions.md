# TaskContinuationOptions

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

| 32 | LazyCancellation |

| 64 | RunContinuationsAsynchronously |

| 65536 | NotOnRanToCompletion |

| 131072 | NotOnFaulted |

| 262144 | NotOnCanceled |

| 393216 | OnlyOnRanToCompletion |

| 327680 | OnlyOnFaulted |

| 196608 | OnlyOnCanceled |

| 524288 | ExecuteSynchronously |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public enum TaskContinuationOptions
{
	public Int32 value__; // 0x10
	public const TaskContinuationOptions None = 0; // 0x0
	public const TaskContinuationOptions PreferFairness = 1; // 0x0
	public const TaskContinuationOptions LongRunning = 2; // 0x0
	public const TaskContinuationOptions AttachedToParent = 4; // 0x0
	public const TaskContinuationOptions DenyChildAttach = 8; // 0x0
	public const TaskContinuationOptions HideScheduler = 16; // 0x0
	public const TaskContinuationOptions LazyCancellation = 32; // 0x0
	public const TaskContinuationOptions RunContinuationsAsynchronously = 64; // 0x0
	public const TaskContinuationOptions NotOnRanToCompletion = 65536; // 0x0
	public const TaskContinuationOptions NotOnFaulted = 131072; // 0x0
	public const TaskContinuationOptions NotOnCanceled = 262144; // 0x0
	public const TaskContinuationOptions OnlyOnRanToCompletion = 393216; // 0x0
	public const TaskContinuationOptions OnlyOnFaulted = 327680; // 0x0
	public const TaskContinuationOptions OnlyOnCanceled = 196608; // 0x0
	public const TaskContinuationOptions ExecuteSynchronously = 524288; // 0x0


}
```