# BsonReaderState

**Namespace:** ` `


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Normal |

| 1 | ReferenceStart |

| 2 | ReferenceRef |

| 3 | ReferenceId |

| 4 | CodeWScopeStart |

| 5 | CodeWScopeCode |

| 6 | CodeWScopeScope |

| 7 | CodeWScopeScopeObject |

| 8 | CodeWScopeScopeEnd |

## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : 
private enum BsonReaderState
{
	public Int32 value__; // 0x10
	public const BsonReaderState Normal = 0; // 0x0
	public const BsonReaderState ReferenceStart = 1; // 0x0
	public const BsonReaderState ReferenceRef = 2; // 0x0
	public const BsonReaderState ReferenceId = 3; // 0x0
	public const BsonReaderState CodeWScopeStart = 4; // 0x0
	public const BsonReaderState CodeWScopeCode = 5; // 0x0
	public const BsonReaderState CodeWScopeScope = 6; // 0x0
	public const BsonReaderState CodeWScopeScopeObject = 7; // 0x0
	public const BsonReaderState CodeWScopeScopeEnd = 8; // 0x0


}
```