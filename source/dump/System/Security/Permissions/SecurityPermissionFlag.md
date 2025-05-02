# SecurityPermissionFlag

**Namespace:** `System.Security.Permissions`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NoFlags |

| 1 | Assertion |

| 2 | UnmanagedCode |

| 4 | SkipVerification |

| 8 | Execution |

| 16 | ControlThread |

| 32 | ControlEvidence |

| 64 | ControlPolicy |

| 128 | SerializationFormatter |

| 256 | ControlDomainPolicy |

| 512 | ControlPrincipal |

| 1024 | ControlAppDomain |

| 2048 | RemotingConfiguration |

| 4096 | Infrastructure |

| 8192 | BindingRedirects |

| 16383 | AllFlags |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Permissions
public enum SecurityPermissionFlag
{
	public Int32 value__; // 0x10
	public const SecurityPermissionFlag NoFlags = 0; // 0x0
	public const SecurityPermissionFlag Assertion = 1; // 0x0
	public const SecurityPermissionFlag UnmanagedCode = 2; // 0x0
	public const SecurityPermissionFlag SkipVerification = 4; // 0x0
	public const SecurityPermissionFlag Execution = 8; // 0x0
	public const SecurityPermissionFlag ControlThread = 16; // 0x0
	public const SecurityPermissionFlag ControlEvidence = 32; // 0x0
	public const SecurityPermissionFlag ControlPolicy = 64; // 0x0
	public const SecurityPermissionFlag SerializationFormatter = 128; // 0x0
	public const SecurityPermissionFlag ControlDomainPolicy = 256; // 0x0
	public const SecurityPermissionFlag ControlPrincipal = 512; // 0x0
	public const SecurityPermissionFlag ControlAppDomain = 1024; // 0x0
	public const SecurityPermissionFlag RemotingConfiguration = 2048; // 0x0
	public const SecurityPermissionFlag Infrastructure = 4096; // 0x0
	public const SecurityPermissionFlag BindingRedirects = 8192; // 0x0
	public const SecurityPermissionFlag AllFlags = 16383; // 0x0


}
```