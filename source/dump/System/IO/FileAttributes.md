# FileAttributes

**Namespace:** `System.IO`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | ReadOnly |

| 2 | Hidden |

| 4 | System |

| 16 | Directory |

| 32 | Archive |

| 64 | Device |

| 128 | Normal |

| 256 | Temporary |

| 512 | SparseFile |

| 1024 | ReparsePoint |

| 2048 | Compressed |

| 4096 | Offline |

| 8192 | NotContentIndexed |

| 16384 | Encrypted |

| 32768 | IntegrityStream |

| 131072 | NoScrubData |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public enum FileAttributes
{
	public Int32 value__; // 0x10
	public const FileAttributes ReadOnly = 1; // 0x0
	public const FileAttributes Hidden = 2; // 0x0
	public const FileAttributes System = 4; // 0x0
	public const FileAttributes Directory = 16; // 0x0
	public const FileAttributes Archive = 32; // 0x0
	public const FileAttributes Device = 64; // 0x0
	public const FileAttributes Normal = 128; // 0x0
	public const FileAttributes Temporary = 256; // 0x0
	public const FileAttributes SparseFile = 512; // 0x0
	public const FileAttributes ReparsePoint = 1024; // 0x0
	public const FileAttributes Compressed = 2048; // 0x0
	public const FileAttributes Offline = 4096; // 0x0
	public const FileAttributes NotContentIndexed = 8192; // 0x0
	public const FileAttributes Encrypted = 16384; // 0x0
	public const FileAttributes IntegrityStream = 32768; // 0x0
	public const FileAttributes NoScrubData = 131072; // 0x0


}
```