# MessageEnum

**Namespace:** `System.Runtime.Serialization.Formatters.Binary`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | NoArgs |

| 2 | ArgsInline |

| 4 | ArgsIsArray |

| 8 | ArgsInArray |

| 16 | NoContext |

| 32 | ContextInline |

| 64 | ContextInArray |

| 128 | MethodSignatureInArray |

| 256 | PropertyInArray |

| 512 | NoReturnValue |

| 1024 | ReturnValueVoid |

| 2048 | ReturnValueInline |

| 4096 | ReturnValueInArray |

| 8192 | ExceptionInArray |

| 32768 | GenericMethod |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization.Formatters.Binary
internal enum MessageEnum
{
	public Int32 value__; // 0x10
	public const MessageEnum NoArgs = 1; // 0x0
	public const MessageEnum ArgsInline = 2; // 0x0
	public const MessageEnum ArgsIsArray = 4; // 0x0
	public const MessageEnum ArgsInArray = 8; // 0x0
	public const MessageEnum NoContext = 16; // 0x0
	public const MessageEnum ContextInline = 32; // 0x0
	public const MessageEnum ContextInArray = 64; // 0x0
	public const MessageEnum MethodSignatureInArray = 128; // 0x0
	public const MessageEnum PropertyInArray = 256; // 0x0
	public const MessageEnum NoReturnValue = 512; // 0x0
	public const MessageEnum ReturnValueVoid = 1024; // 0x0
	public const MessageEnum ReturnValueInline = 2048; // 0x0
	public const MessageEnum ReturnValueInArray = 4096; // 0x0
	public const MessageEnum ExceptionInArray = 8192; // 0x0
	public const MessageEnum GenericMethod = 32768; // 0x0


}
```