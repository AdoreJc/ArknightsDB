# XmlSchemaValidationFlags

**Namespace:** `System.Xml.Schema`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | ProcessInlineSchema |

| 2 | ProcessSchemaLocation |

| 4 | ReportValidationWarnings |

| 8 | ProcessIdentityConstraints |

| 16 | AllowXmlAttributes |

## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public enum XmlSchemaValidationFlags
{
	public Int32 value__; // 0x10
	public const XmlSchemaValidationFlags None = 0; // 0x0
	public const XmlSchemaValidationFlags ProcessInlineSchema = 1; // 0x0
	public const XmlSchemaValidationFlags ProcessSchemaLocation = 2; // 0x0
	public const XmlSchemaValidationFlags ReportValidationWarnings = 4; // 0x0
	public const XmlSchemaValidationFlags ProcessIdentityConstraints = 8; // 0x0
	public const XmlSchemaValidationFlags AllowXmlAttributes = 16; // 0x0


}
```