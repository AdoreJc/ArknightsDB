# TaskStatus

**Namespace:** `System.Threading.Tasks`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Created |

| 1 | WaitingForActivation |

| 2 | WaitingToRun |

| 3 | Running |

| 4 | WaitingForChildrenToComplete |

| 5 | RanToCompletion |

| 6 | Canceled |

| 7 | Faulted |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public enum TaskStatus
{
	public Int32 value__; // 0x10
	public const TaskStatus Created = 0; // 0x0
	public const TaskStatus WaitingForActivation = 1; // 0x0
	public const TaskStatus WaitingToRun = 2; // 0x0
	public const TaskStatus Running = 3; // 0x0
	public const TaskStatus WaitingForChildrenToComplete = 4; // 0x0
	public const TaskStatus RanToCompletion = 5; // 0x0
	public const TaskStatus Canceled = 6; // 0x0
	public const TaskStatus Faulted = 7; // 0x0


}
```