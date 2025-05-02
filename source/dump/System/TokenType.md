# TokenType

**Namespace:** `System`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | NumberToken |

| 2 | YearNumberToken |

| 3 | Am |

| 4 | Pm |

| 5 | MonthToken |

| 6 | EndOfString |

| 7 | DayOfWeekToken |

| 8 | TimeZoneToken |

| 9 | EraToken |

| 10 | DateWordToken |

| 11 | UnknownToken |

| 12 | HebrewNumber |

| 13 | JapaneseEraToken |

| 14 | TEraToken |

| 15 | IgnorableSymbol |

| 256 | SEP_Unk |

| 512 | SEP_End |

| 768 | SEP_Space |

| 1024 | SEP_Am |

| 1280 | SEP_Pm |

| 1536 | SEP_Date |

| 1792 | SEP_Time |

| 2048 | SEP_YearSuff |

| 2304 | SEP_MonthSuff |

| 2560 | SEP_DaySuff |

| 2816 | SEP_HourSuff |

| 3072 | SEP_MinuteSuff |

| 3328 | SEP_SecondSuff |

| 3584 | SEP_LocalTimeMark |

| 3840 | SEP_DateOrOffset |

| 255 | RegularTokenMask |

| 65280 | SeparatorTokenMask |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal enum TokenType
{
	public Int32 value__; // 0x10
	public const TokenType NumberToken = 1; // 0x0
	public const TokenType YearNumberToken = 2; // 0x0
	public const TokenType Am = 3; // 0x0
	public const TokenType Pm = 4; // 0x0
	public const TokenType MonthToken = 5; // 0x0
	public const TokenType EndOfString = 6; // 0x0
	public const TokenType DayOfWeekToken = 7; // 0x0
	public const TokenType TimeZoneToken = 8; // 0x0
	public const TokenType EraToken = 9; // 0x0
	public const TokenType DateWordToken = 10; // 0x0
	public const TokenType UnknownToken = 11; // 0x0
	public const TokenType HebrewNumber = 12; // 0x0
	public const TokenType JapaneseEraToken = 13; // 0x0
	public const TokenType TEraToken = 14; // 0x0
	public const TokenType IgnorableSymbol = 15; // 0x0
	public const TokenType SEP_Unk = 256; // 0x0
	public const TokenType SEP_End = 512; // 0x0
	public const TokenType SEP_Space = 768; // 0x0
	public const TokenType SEP_Am = 1024; // 0x0
	public const TokenType SEP_Pm = 1280; // 0x0
	public const TokenType SEP_Date = 1536; // 0x0
	public const TokenType SEP_Time = 1792; // 0x0
	public const TokenType SEP_YearSuff = 2048; // 0x0
	public const TokenType SEP_MonthSuff = 2304; // 0x0
	public const TokenType SEP_DaySuff = 2560; // 0x0
	public const TokenType SEP_HourSuff = 2816; // 0x0
	public const TokenType SEP_MinuteSuff = 3072; // 0x0
	public const TokenType SEP_SecondSuff = 3328; // 0x0
	public const TokenType SEP_LocalTimeMark = 3584; // 0x0
	public const TokenType SEP_DateOrOffset = 3840; // 0x0
	public const TokenType RegularTokenMask = 255; // 0x0
	public const TokenType SeparatorTokenMask = 65280; // 0x0


}
```