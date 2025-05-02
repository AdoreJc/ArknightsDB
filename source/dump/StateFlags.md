# StateFlags

**Namespace:** ` `


## Fields

- `Byte value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | CaptureIdentity |

| 2 | CaptureContext |

| 4 | ThreadSafeContextCopy |

| 8 | PostBlockStarted |

| 16 | PostBlockFinished |

## Dump
```C#
// Dll : System.dll
// Namespace : 
private enum StateFlags
{
	public Byte value__; // 0x10
	public const StateFlags None = 0; // 0x0
	public const StateFlags CaptureIdentity = 1; // 0x0
	public const StateFlags CaptureContext = 2; // 0x0
	public const StateFlags ThreadSafeContextCopy = 4; // 0x0
	public const StateFlags PostBlockStarted = 8; // 0x0
	public const StateFlags PostBlockFinished = 16; // 0x0


}
```