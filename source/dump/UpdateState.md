# UpdateState

**Namespace:** ` `


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NONE |

| 1 | VERSION |

| 2 | DOWNLOAD_INFO |

| 3 | DOWNLOAD_UPZIP_RES |

| 4 | UNZIPPING_RES |

| 5 | COMPLETE |

| 6 | ERROR |

| 7 | TRIVIAL_ERROR |

| 9 | CONSISTENCY_CHECK |

| 10 | RECOVER_PERSIST_INFO |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public enum UpdateState
{
	public Int32 value__; // 0x10
	public const UpdateState NONE = 0; // 0x0
	public const UpdateState VERSION = 1; // 0x0
	public const UpdateState DOWNLOAD_INFO = 2; // 0x0
	public const UpdateState DOWNLOAD_UPZIP_RES = 3; // 0x0
	public const UpdateState UNZIPPING_RES = 4; // 0x0
	public const UpdateState COMPLETE = 5; // 0x0
	public const UpdateState ERROR = 6; // 0x0
	public const UpdateState TRIVIAL_ERROR = 7; // 0x0
	public const UpdateState CONSISTENCY_CHECK = 9; // 0x0
	public const UpdateState RECOVER_PERSIST_INFO = 10; // 0x0


}
```