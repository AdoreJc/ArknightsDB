# BindingFlags

**Namespace:** `System.Reflection`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Default |

| 1 | IgnoreCase |

| 2 | DeclaredOnly |

| 4 | Instance |

| 8 | Static |

| 16 | Public |

| 32 | NonPublic |

| 64 | FlattenHierarchy |

| 256 | InvokeMethod |

| 512 | CreateInstance |

| 1024 | GetField |

| 2048 | SetField |

| 4096 | GetProperty |

| 8192 | SetProperty |

| 16384 | PutDispProperty |

| 32768 | PutRefDispProperty |

| 65536 | ExactBinding |

| 131072 | SuppressChangeType |

| 262144 | OptionalParamBinding |

| 16777216 | IgnoreReturn |

| 33554432 | DoNotWrapExceptions |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public enum BindingFlags
{
	public Int32 value__; // 0x10
	public const BindingFlags Default = 0; // 0x0
	public const BindingFlags IgnoreCase = 1; // 0x0
	public const BindingFlags DeclaredOnly = 2; // 0x0
	public const BindingFlags Instance = 4; // 0x0
	public const BindingFlags Static = 8; // 0x0
	public const BindingFlags Public = 16; // 0x0
	public const BindingFlags NonPublic = 32; // 0x0
	public const BindingFlags FlattenHierarchy = 64; // 0x0
	public const BindingFlags InvokeMethod = 256; // 0x0
	public const BindingFlags CreateInstance = 512; // 0x0
	public const BindingFlags GetField = 1024; // 0x0
	public const BindingFlags SetField = 2048; // 0x0
	public const BindingFlags GetProperty = 4096; // 0x0
	public const BindingFlags SetProperty = 8192; // 0x0
	public const BindingFlags PutDispProperty = 16384; // 0x0
	public const BindingFlags PutRefDispProperty = 32768; // 0x0
	public const BindingFlags ExactBinding = 65536; // 0x0
	public const BindingFlags SuppressChangeType = 131072; // 0x0
	public const BindingFlags OptionalParamBinding = 262144; // 0x0
	public const BindingFlags IgnoreReturn = 16777216; // 0x0
	public const BindingFlags DoNotWrapExceptions = 33554432; // 0x0


}
```