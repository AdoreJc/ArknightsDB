# ParameterAttributes

**Namespace:** `System.Reflection`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | In |

| 2 | Out |

| 4 | Lcid |

| 8 | Retval |

| 16 | Optional |

| 4096 | HasDefault |

| 8192 | HasFieldMarshal |

| 16384 | Reserved3 |

| 32768 | Reserved4 |

| 61440 | ReservedMask |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public enum ParameterAttributes
{
	public Int32 value__; // 0x10
	public const ParameterAttributes None = 0; // 0x0
	public const ParameterAttributes In = 1; // 0x0
	public const ParameterAttributes Out = 2; // 0x0
	public const ParameterAttributes Lcid = 4; // 0x0
	public const ParameterAttributes Retval = 8; // 0x0
	public const ParameterAttributes Optional = 16; // 0x0
	public const ParameterAttributes HasDefault = 4096; // 0x0
	public const ParameterAttributes HasFieldMarshal = 8192; // 0x0
	public const ParameterAttributes Reserved3 = 16384; // 0x0
	public const ParameterAttributes Reserved4 = 32768; // 0x0
	public const ParameterAttributes ReservedMask = 61440; // 0x0


}
```