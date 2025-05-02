# MethodImplAttributes

**Namespace:** `System.Reflection`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 3 | CodeTypeMask |

| 0 | IL |

| 1 | Native |

| 2 | OPTIL |

| 3 | Runtime |

| 4 | ManagedMask |

| 4 | Unmanaged |

| 0 | Managed |

| 16 | ForwardRef |

| 128 | PreserveSig |

| 4096 | InternalCall |

| 32 | Synchronized |

| 8 | NoInlining |

| 256 | AggressiveInlining |

| 64 | NoOptimization |

| 65535 | MaxMethodImplVal |

| 1024 | SecurityMitigations |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public enum MethodImplAttributes
{
	public Int32 value__; // 0x10
	public const MethodImplAttributes CodeTypeMask = 3; // 0x0
	public const MethodImplAttributes IL = 0; // 0x0
	public const MethodImplAttributes Native = 1; // 0x0
	public const MethodImplAttributes OPTIL = 2; // 0x0
	public const MethodImplAttributes Runtime = 3; // 0x0
	public const MethodImplAttributes ManagedMask = 4; // 0x0
	public const MethodImplAttributes Unmanaged = 4; // 0x0
	public const MethodImplAttributes Managed = 0; // 0x0
	public const MethodImplAttributes ForwardRef = 16; // 0x0
	public const MethodImplAttributes PreserveSig = 128; // 0x0
	public const MethodImplAttributes InternalCall = 4096; // 0x0
	public const MethodImplAttributes Synchronized = 32; // 0x0
	public const MethodImplAttributes NoInlining = 8; // 0x0
	public const MethodImplAttributes AggressiveInlining = 256; // 0x0
	public const MethodImplAttributes NoOptimization = 64; // 0x0
	public const MethodImplAttributes MaxMethodImplVal = 65535; // 0x0
	public const MethodImplAttributes SecurityMitigations = 1024; // 0x0


}
```