# VerifyPrefabTypeFlags

**Namespace:** `FullInspector`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | None |

| 2 | Prefab |

| 4 | ModelPrefab |

| 8 | PrefabInstance |

| 16 | ModelPrefabInstance |

| 32 | MissingPrefabInstance |

| 64 | DisconnectedPrefabInstance |

| 128 | DisconnectedModelPrefabInstance |

## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public enum VerifyPrefabTypeFlags
{
	public Int32 value__; // 0x10
	public const VerifyPrefabTypeFlags None = 1; // 0x0
	public const VerifyPrefabTypeFlags Prefab = 2; // 0x0
	public const VerifyPrefabTypeFlags ModelPrefab = 4; // 0x0
	public const VerifyPrefabTypeFlags PrefabInstance = 8; // 0x0
	public const VerifyPrefabTypeFlags ModelPrefabInstance = 16; // 0x0
	public const VerifyPrefabTypeFlags MissingPrefabInstance = 32; // 0x0
	public const VerifyPrefabTypeFlags DisconnectedPrefabInstance = 64; // 0x0
	public const VerifyPrefabTypeFlags DisconnectedModelPrefabInstance = 128; // 0x0


}
```