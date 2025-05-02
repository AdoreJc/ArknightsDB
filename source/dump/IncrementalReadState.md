# IncrementalReadState

**Namespace:** ` `


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Text |

| 1 | StartTag |

| 2 | PI |

| 3 | CDATA |

| 4 | Comment |

| 5 | Attributes |

| 6 | AttributeValue |

| 7 | ReadData |

| 8 | EndElement |

| 9 | End |

| 10 | ReadValueChunk_OnCachedValue |

| 11 | ReadValueChunk_OnPartialValue |

| 12 | ReadContentAsBinary_OnCachedValue |

| 13 | ReadContentAsBinary_OnPartialValue |

| 14 | ReadContentAsBinary_End |

## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
private enum IncrementalReadState
{
	public Int32 value__; // 0x10
	public const IncrementalReadState Text = 0; // 0x0
	public const IncrementalReadState StartTag = 1; // 0x0
	public const IncrementalReadState PI = 2; // 0x0
	public const IncrementalReadState CDATA = 3; // 0x0
	public const IncrementalReadState Comment = 4; // 0x0
	public const IncrementalReadState Attributes = 5; // 0x0
	public const IncrementalReadState AttributeValue = 6; // 0x0
	public const IncrementalReadState ReadData = 7; // 0x0
	public const IncrementalReadState EndElement = 8; // 0x0
	public const IncrementalReadState End = 9; // 0x0
	public const IncrementalReadState ReadValueChunk_OnCachedValue = 10; // 0x0
	public const IncrementalReadState ReadValueChunk_OnPartialValue = 11; // 0x0
	public const IncrementalReadState ReadContentAsBinary_OnCachedValue = 12; // 0x0
	public const IncrementalReadState ReadContentAsBinary_OnPartialValue = 13; // 0x0
	public const IncrementalReadState ReadContentAsBinary_End = 14; // 0x0


}
```