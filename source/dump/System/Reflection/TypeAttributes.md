# TypeAttributes

**Namespace:** `System.Reflection`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 7 | VisibilityMask |

| 0 | NotPublic |

| 1 | Public |

| 2 | NestedPublic |

| 3 | NestedPrivate |

| 4 | NestedFamily |

| 5 | NestedAssembly |

| 6 | NestedFamANDAssem |

| 7 | NestedFamORAssem |

| 24 | LayoutMask |

| 0 | AutoLayout |

| 8 | SequentialLayout |

| 16 | ExplicitLayout |

| 32 | ClassSemanticsMask |

| 0 | Class |

| 32 | Interface |

| 128 | Abstract |

| 256 | Sealed |

| 1024 | SpecialName |

| 4096 | Import |

| 8192 | Serializable |

| 16384 | WindowsRuntime |

| 196608 | StringFormatMask |

| 0 | AnsiClass |

| 65536 | UnicodeClass |

| 131072 | AutoClass |

| 196608 | CustomFormatClass |

| 12582912 | CustomFormatMask |

| 1048576 | BeforeFieldInit |

| 2048 | RTSpecialName |

| 262144 | HasSecurity |

| 264192 | ReservedMask |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public enum TypeAttributes
{
	public Int32 value__; // 0x10
	public const TypeAttributes VisibilityMask = 7; // 0x0
	public const TypeAttributes NotPublic = 0; // 0x0
	public const TypeAttributes Public = 1; // 0x0
	public const TypeAttributes NestedPublic = 2; // 0x0
	public const TypeAttributes NestedPrivate = 3; // 0x0
	public const TypeAttributes NestedFamily = 4; // 0x0
	public const TypeAttributes NestedAssembly = 5; // 0x0
	public const TypeAttributes NestedFamANDAssem = 6; // 0x0
	public const TypeAttributes NestedFamORAssem = 7; // 0x0
	public const TypeAttributes LayoutMask = 24; // 0x0
	public const TypeAttributes AutoLayout = 0; // 0x0
	public const TypeAttributes SequentialLayout = 8; // 0x0
	public const TypeAttributes ExplicitLayout = 16; // 0x0
	public const TypeAttributes ClassSemanticsMask = 32; // 0x0
	public const TypeAttributes Class = 0; // 0x0
	public const TypeAttributes Interface = 32; // 0x0
	public const TypeAttributes Abstract = 128; // 0x0
	public const TypeAttributes Sealed = 256; // 0x0
	public const TypeAttributes SpecialName = 1024; // 0x0
	public const TypeAttributes Import = 4096; // 0x0
	public const TypeAttributes Serializable = 8192; // 0x0
	public const TypeAttributes WindowsRuntime = 16384; // 0x0
	public const TypeAttributes StringFormatMask = 196608; // 0x0
	public const TypeAttributes AnsiClass = 0; // 0x0
	public const TypeAttributes UnicodeClass = 65536; // 0x0
	public const TypeAttributes AutoClass = 131072; // 0x0
	public const TypeAttributes CustomFormatClass = 196608; // 0x0
	public const TypeAttributes CustomFormatMask = 12582912; // 0x0
	public const TypeAttributes BeforeFieldInit = 1048576; // 0x0
	public const TypeAttributes RTSpecialName = 2048; // 0x0
	public const TypeAttributes HasSecurity = 262144; // 0x0
	public const TypeAttributes ReservedMask = 264192; // 0x0


}
```