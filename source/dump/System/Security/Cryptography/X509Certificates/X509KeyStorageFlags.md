# X509KeyStorageFlags

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | DefaultKeySet |

| 1 | UserKeySet |

| 2 | MachineKeySet |

| 4 | Exportable |

| 8 | UserProtected |

| 16 | PersistKeySet |

| 32 | EphemeralKeySet |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography.X509Certificates
public enum X509KeyStorageFlags
{
	public Int32 value__; // 0x10
	public const X509KeyStorageFlags DefaultKeySet = 0; // 0x0
	public const X509KeyStorageFlags UserKeySet = 1; // 0x0
	public const X509KeyStorageFlags MachineKeySet = 2; // 0x0
	public const X509KeyStorageFlags Exportable = 4; // 0x0
	public const X509KeyStorageFlags UserProtected = 8; // 0x0
	public const X509KeyStorageFlags PersistKeySet = 16; // 0x0
	public const X509KeyStorageFlags EphemeralKeySet = 32; // 0x0


}
```