# GenericParameterAttributes

**Namespace:** `System.Reflection`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 3 | VarianceMask |

| 1 | Covariant |

| 2 | Contravariant |

| 28 | SpecialConstraintMask |

| 4 | ReferenceTypeConstraint |

| 8 | NotNullableValueTypeConstraint |

| 16 | DefaultConstructorConstraint |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public enum GenericParameterAttributes
{
	public Int32 value__; // 0x10
	public const GenericParameterAttributes None = 0; // 0x0
	public const GenericParameterAttributes VarianceMask = 3; // 0x0
	public const GenericParameterAttributes Covariant = 1; // 0x0
	public const GenericParameterAttributes Contravariant = 2; // 0x0
	public const GenericParameterAttributes SpecialConstraintMask = 28; // 0x0
	public const GenericParameterAttributes ReferenceTypeConstraint = 4; // 0x0
	public const GenericParameterAttributes NotNullableValueTypeConstraint = 8; // 0x0
	public const GenericParameterAttributes DefaultConstructorConstraint = 16; // 0x0


}
```