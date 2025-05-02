# FileOptions

**Namespace:** `System.IO`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 2147483648 | WriteThrough |

| 1073741824 | Asynchronous |

| 268435456 | RandomAccess |

| 67108864 | DeleteOnClose |

| 134217728 | SequentialScan |

| 16384 | Encrypted |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public enum FileOptions
{
	public Int32 value__; // 0x10
	public const FileOptions None = 0; // 0x0
	public const FileOptions WriteThrough = 2147483648; // 0x0
	public const FileOptions Asynchronous = 1073741824; // 0x0
	public const FileOptions RandomAccess = 268435456; // 0x0
	public const FileOptions DeleteOnClose = 67108864; // 0x0
	public const FileOptions SequentialScan = 134217728; // 0x0
	public const FileOptions Encrypted = 16384; // 0x0


}
```