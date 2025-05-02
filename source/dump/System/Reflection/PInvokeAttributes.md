# PInvokeAttributes

**Namespace:** `System.Reflection`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | NoMangle |

| 6 | CharSetMask |

| 0 | CharSetNotSpec |

| 2 | CharSetAnsi |

| 4 | CharSetUnicode |

| 6 | CharSetAuto |

| 0 | BestFitUseAssem |

| 16 | BestFitEnabled |

| 32 | BestFitDisabled |

| 48 | BestFitMask |

| 0 | ThrowOnUnmappableCharUseAssem |

| 4096 | ThrowOnUnmappableCharEnabled |

| 8192 | ThrowOnUnmappableCharDisabled |

| 12288 | ThrowOnUnmappableCharMask |

| 64 | SupportsLastError |

| 1792 | CallConvMask |

| 256 | CallConvWinapi |

| 512 | CallConvCdecl |

| 768 | CallConvStdcall |

| 1024 | CallConvThiscall |

| 1280 | CallConvFastcall |

| 65535 | MaxValue |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal enum PInvokeAttributes
{
	public Int32 value__; // 0x10
	public const PInvokeAttributes NoMangle = 1; // 0x0
	public const PInvokeAttributes CharSetMask = 6; // 0x0
	public const PInvokeAttributes CharSetNotSpec = 0; // 0x0
	public const PInvokeAttributes CharSetAnsi = 2; // 0x0
	public const PInvokeAttributes CharSetUnicode = 4; // 0x0
	public const PInvokeAttributes CharSetAuto = 6; // 0x0
	public const PInvokeAttributes BestFitUseAssem = 0; // 0x0
	public const PInvokeAttributes BestFitEnabled = 16; // 0x0
	public const PInvokeAttributes BestFitDisabled = 32; // 0x0
	public const PInvokeAttributes BestFitMask = 48; // 0x0
	public const PInvokeAttributes ThrowOnUnmappableCharUseAssem = 0; // 0x0
	public const PInvokeAttributes ThrowOnUnmappableCharEnabled = 4096; // 0x0
	public const PInvokeAttributes ThrowOnUnmappableCharDisabled = 8192; // 0x0
	public const PInvokeAttributes ThrowOnUnmappableCharMask = 12288; // 0x0
	public const PInvokeAttributes SupportsLastError = 64; // 0x0
	public const PInvokeAttributes CallConvMask = 1792; // 0x0
	public const PInvokeAttributes CallConvWinapi = 256; // 0x0
	public const PInvokeAttributes CallConvCdecl = 512; // 0x0
	public const PInvokeAttributes CallConvStdcall = 768; // 0x0
	public const PInvokeAttributes CallConvThiscall = 1024; // 0x0
	public const PInvokeAttributes CallConvFastcall = 1280; // 0x0
	public const PInvokeAttributes MaxValue = 65535; // 0x0


}
```