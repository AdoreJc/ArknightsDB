# GenericUriParserOptions

**Namespace:** `System`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Default |

| 1 | GenericAuthority |

| 2 | AllowEmptyAuthority |

| 4 | NoUserInfo |

| 8 | NoPort |

| 16 | NoQuery |

| 32 | NoFragment |

| 64 | DontConvertPathBackslashes |

| 128 | DontCompressPath |

| 256 | DontUnescapePathDotsAndSlashes |

| 512 | Idn |

| 1024 | IriParsing |

## Dump
```C#
// Dll : System.dll
// Namespace : System
public enum GenericUriParserOptions
{
	public Int32 value__; // 0x10
	public const GenericUriParserOptions Default = 0; // 0x0
	public const GenericUriParserOptions GenericAuthority = 1; // 0x0
	public const GenericUriParserOptions AllowEmptyAuthority = 2; // 0x0
	public const GenericUriParserOptions NoUserInfo = 4; // 0x0
	public const GenericUriParserOptions NoPort = 8; // 0x0
	public const GenericUriParserOptions NoQuery = 16; // 0x0
	public const GenericUriParserOptions NoFragment = 32; // 0x0
	public const GenericUriParserOptions DontConvertPathBackslashes = 64; // 0x0
	public const GenericUriParserOptions DontCompressPath = 128; // 0x0
	public const GenericUriParserOptions DontUnescapePathDotsAndSlashes = 256; // 0x0
	public const GenericUriParserOptions Idn = 512; // 0x0
	public const GenericUriParserOptions IriParsing = 1024; // 0x0


}
```