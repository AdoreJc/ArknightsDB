# DllImportSearchPath

**Namespace:** `System.Runtime.InteropServices`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 256 | UseDllDirectoryForDependencies |

| 512 | ApplicationDirectory |

| 1024 | UserDirectories |

| 2048 | System32 |

| 4096 | SafeDirectories |

| 2 | AssemblyDirectory |

| 0 | LegacyBehavior |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.InteropServices
public enum DllImportSearchPath
{
	public Int32 value__; // 0x10
	public const DllImportSearchPath UseDllDirectoryForDependencies = 256; // 0x0
	public const DllImportSearchPath ApplicationDirectory = 512; // 0x0
	public const DllImportSearchPath UserDirectories = 1024; // 0x0
	public const DllImportSearchPath System32 = 2048; // 0x0
	public const DllImportSearchPath SafeDirectories = 4096; // 0x0
	public const DllImportSearchPath AssemblyDirectory = 2; // 0x0
	public const DllImportSearchPath LegacyBehavior = 0; // 0x0


}
```