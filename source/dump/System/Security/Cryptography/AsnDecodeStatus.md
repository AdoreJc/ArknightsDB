# AsnDecodeStatus

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 4294967295 | NotDecoded |

| 0 | Ok |

| 1 | BadAsn |

| 2 | BadTag |

| 3 | BadLength |

| 4 | InformationNotAvailable |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography
internal enum AsnDecodeStatus
{
	public Int32 value__; // 0x10
	public const AsnDecodeStatus NotDecoded = 4294967295; // 0x0
	public const AsnDecodeStatus Ok = 0; // 0x0
	public const AsnDecodeStatus BadAsn = 1; // 0x0
	public const AsnDecodeStatus BadTag = 2; // 0x0
	public const AsnDecodeStatus BadLength = 3; // 0x0
	public const AsnDecodeStatus InformationNotAvailable = 4; // 0x0


}
```