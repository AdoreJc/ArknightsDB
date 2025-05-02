# UriSyntaxFlags

**Namespace:** `System`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | MustHaveAuthority |

| 2 | OptionalAuthority |

| 4 | MayHaveUserInfo |

| 8 | MayHavePort |

| 16 | MayHavePath |

| 32 | MayHaveQuery |

| 64 | MayHaveFragment |

| 128 | AllowEmptyHost |

| 256 | AllowUncHost |

| 512 | AllowDnsHost |

| 1024 | AllowIPv4Host |

| 2048 | AllowIPv6Host |

| 3584 | AllowAnInternetHost |

| 4096 | AllowAnyOtherHost |

| 8192 | FileLikeUri |

| 16384 | MailToLikeUri |

| 65536 | V1_UnknownUri |

| 131072 | SimpleUserSyntax |

| 262144 | BuiltInSyntax |

| 524288 | ParserSchemeOnly |

| 1048576 | AllowDOSPath |

| 2097152 | PathIsRooted |

| 4194304 | ConvertPathSlashes |

| 8388608 | CompressPath |

| 16777216 | CanonicalizeAsFilePath |

| 33554432 | UnEscapeDotsAndSlashes |

| 67108864 | AllowIdn |

| 268435456 | AllowIriParsing |

## Dump
```C#
// Dll : System.dll
// Namespace : System
internal enum UriSyntaxFlags
{
	public Int32 value__; // 0x10
	public const UriSyntaxFlags None = 0; // 0x0
	public const UriSyntaxFlags MustHaveAuthority = 1; // 0x0
	public const UriSyntaxFlags OptionalAuthority = 2; // 0x0
	public const UriSyntaxFlags MayHaveUserInfo = 4; // 0x0
	public const UriSyntaxFlags MayHavePort = 8; // 0x0
	public const UriSyntaxFlags MayHavePath = 16; // 0x0
	public const UriSyntaxFlags MayHaveQuery = 32; // 0x0
	public const UriSyntaxFlags MayHaveFragment = 64; // 0x0
	public const UriSyntaxFlags AllowEmptyHost = 128; // 0x0
	public const UriSyntaxFlags AllowUncHost = 256; // 0x0
	public const UriSyntaxFlags AllowDnsHost = 512; // 0x0
	public const UriSyntaxFlags AllowIPv4Host = 1024; // 0x0
	public const UriSyntaxFlags AllowIPv6Host = 2048; // 0x0
	public const UriSyntaxFlags AllowAnInternetHost = 3584; // 0x0
	public const UriSyntaxFlags AllowAnyOtherHost = 4096; // 0x0
	public const UriSyntaxFlags FileLikeUri = 8192; // 0x0
	public const UriSyntaxFlags MailToLikeUri = 16384; // 0x0
	public const UriSyntaxFlags V1_UnknownUri = 65536; // 0x0
	public const UriSyntaxFlags SimpleUserSyntax = 131072; // 0x0
	public const UriSyntaxFlags BuiltInSyntax = 262144; // 0x0
	public const UriSyntaxFlags ParserSchemeOnly = 524288; // 0x0
	public const UriSyntaxFlags AllowDOSPath = 1048576; // 0x0
	public const UriSyntaxFlags PathIsRooted = 2097152; // 0x0
	public const UriSyntaxFlags ConvertPathSlashes = 4194304; // 0x0
	public const UriSyntaxFlags CompressPath = 8388608; // 0x0
	public const UriSyntaxFlags CanonicalizeAsFilePath = 16777216; // 0x0
	public const UriSyntaxFlags UnEscapeDotsAndSlashes = 33554432; // 0x0
	public const UriSyntaxFlags AllowIdn = 67108864; // 0x0
	public const UriSyntaxFlags AllowIriParsing = 268435456; // 0x0


}
```