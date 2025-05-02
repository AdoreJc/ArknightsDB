# ParseFlags

**Namespace:** `System`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | HaveYear |

| 2 | HaveMonth |

| 4 | HaveDay |

| 8 | HaveHour |

| 16 | HaveMinute |

| 32 | HaveSecond |

| 64 | HaveTime |

| 128 | HaveDate |

| 256 | TimeZoneUsed |

| 512 | TimeZoneUtc |

| 1024 | ParsedMonthName |

| 2048 | CaptureOffset |

| 4096 | YearDefault |

| 8192 | Rfc1123Pattern |

| 16384 | UtcSortPattern |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal enum ParseFlags
{
	public Int32 value__; // 0x10
	public const ParseFlags HaveYear = 1; // 0x0
	public const ParseFlags HaveMonth = 2; // 0x0
	public const ParseFlags HaveDay = 4; // 0x0
	public const ParseFlags HaveHour = 8; // 0x0
	public const ParseFlags HaveMinute = 16; // 0x0
	public const ParseFlags HaveSecond = 32; // 0x0
	public const ParseFlags HaveTime = 64; // 0x0
	public const ParseFlags HaveDate = 128; // 0x0
	public const ParseFlags TimeZoneUsed = 256; // 0x0
	public const ParseFlags TimeZoneUtc = 512; // 0x0
	public const ParseFlags ParsedMonthName = 1024; // 0x0
	public const ParseFlags CaptureOffset = 2048; // 0x0
	public const ParseFlags YearDefault = 4096; // 0x0
	public const ParseFlags Rfc1123Pattern = 8192; // 0x0
	public const ParseFlags UtcSortPattern = 16384; // 0x0


}
```