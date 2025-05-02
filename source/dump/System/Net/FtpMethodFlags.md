# FtpMethodFlags

**Namespace:** `System.Net`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | IsDownload |

| 2 | IsUpload |

| 4 | TakesParameter |

| 8 | MayTakeParameter |

| 16 | DoesNotTakeParameter |

| 32 | ParameterIsDirectory |

| 64 | ShouldParseForResponseUri |

| 128 | HasHttpCommand |

| 256 | MustChangeWorkingDirectoryToPath |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal enum FtpMethodFlags
{
	public Int32 value__; // 0x10
	public const FtpMethodFlags None = 0; // 0x0
	public const FtpMethodFlags IsDownload = 1; // 0x0
	public const FtpMethodFlags IsUpload = 2; // 0x0
	public const FtpMethodFlags TakesParameter = 4; // 0x0
	public const FtpMethodFlags MayTakeParameter = 8; // 0x0
	public const FtpMethodFlags DoesNotTakeParameter = 16; // 0x0
	public const FtpMethodFlags ParameterIsDirectory = 32; // 0x0
	public const FtpMethodFlags ShouldParseForResponseUri = 64; // 0x0
	public const FtpMethodFlags HasHttpCommand = 128; // 0x0
	public const FtpMethodFlags MustChangeWorkingDirectoryToPath = 256; // 0x0


}
```