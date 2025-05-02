# MethodAttributes

**Namespace:** `System.Reflection`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 7 | MemberAccessMask |

| 0 | PrivateScope |

| 1 | Private |

| 2 | FamANDAssem |

| 3 | Assembly |

| 4 | Family |

| 5 | FamORAssem |

| 6 | Public |

| 16 | Static |

| 32 | Final |

| 64 | Virtual |

| 128 | HideBySig |

| 512 | CheckAccessOnOverride |

| 256 | VtableLayoutMask |

| 0 | ReuseSlot |

| 256 | NewSlot |

| 1024 | Abstract |

| 2048 | SpecialName |

| 8192 | PinvokeImpl |

| 8 | UnmanagedExport |

| 4096 | RTSpecialName |

| 16384 | HasSecurity |

| 32768 | RequireSecObject |

| 53248 | ReservedMask |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public enum MethodAttributes
{
	public Int32 value__; // 0x10
	public const MethodAttributes MemberAccessMask = 7; // 0x0
	public const MethodAttributes PrivateScope = 0; // 0x0
	public const MethodAttributes Private = 1; // 0x0
	public const MethodAttributes FamANDAssem = 2; // 0x0
	public const MethodAttributes Assembly = 3; // 0x0
	public const MethodAttributes Family = 4; // 0x0
	public const MethodAttributes FamORAssem = 5; // 0x0
	public const MethodAttributes Public = 6; // 0x0
	public const MethodAttributes Static = 16; // 0x0
	public const MethodAttributes Final = 32; // 0x0
	public const MethodAttributes Virtual = 64; // 0x0
	public const MethodAttributes HideBySig = 128; // 0x0
	public const MethodAttributes CheckAccessOnOverride = 512; // 0x0
	public const MethodAttributes VtableLayoutMask = 256; // 0x0
	public const MethodAttributes ReuseSlot = 0; // 0x0
	public const MethodAttributes NewSlot = 256; // 0x0
	public const MethodAttributes Abstract = 1024; // 0x0
	public const MethodAttributes SpecialName = 2048; // 0x0
	public const MethodAttributes PinvokeImpl = 8192; // 0x0
	public const MethodAttributes UnmanagedExport = 8; // 0x0
	public const MethodAttributes RTSpecialName = 4096; // 0x0
	public const MethodAttributes HasSecurity = 16384; // 0x0
	public const MethodAttributes RequireSecObject = 32768; // 0x0
	public const MethodAttributes ReservedMask = 53248; // 0x0


}
```