# Consistency

**Namespace:** `System.Runtime.ConstrainedExecution`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | MayCorruptProcess |

| 1 | MayCorruptAppDomain |

| 2 | MayCorruptInstance |

| 3 | WillNotCorruptState |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.ConstrainedExecution
public enum Consistency
{
	public Int32 value__; // 0x10
	public const Consistency MayCorruptProcess = 0; // 0x0
	public const Consistency MayCorruptAppDomain = 1; // 0x0
	public const Consistency MayCorruptInstance = 2; // 0x0
	public const Consistency WillNotCorruptState = 3; // 0x0


}
```