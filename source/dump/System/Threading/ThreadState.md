# ThreadState

**Namespace:** `System.Threading`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Running |

| 1 | StopRequested |

| 2 | SuspendRequested |

| 4 | Background |

| 8 | Unstarted |

| 16 | Stopped |

| 32 | WaitSleepJoin |

| 64 | Suspended |

| 128 | AbortRequested |

| 256 | Aborted |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
public enum ThreadState
{
	public Int32 value__; // 0x10
	public const ThreadState Running = 0; // 0x0
	public const ThreadState StopRequested = 1; // 0x0
	public const ThreadState SuspendRequested = 2; // 0x0
	public const ThreadState Background = 4; // 0x0
	public const ThreadState Unstarted = 8; // 0x0
	public const ThreadState Stopped = 16; // 0x0
	public const ThreadState WaitSleepJoin = 32; // 0x0
	public const ThreadState Suspended = 64; // 0x0
	public const ThreadState AbortRequested = 128; // 0x0
	public const ThreadState Aborted = 256; // 0x0


}
```