# CspProviderFlags

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NoFlags |

| 1 | UseMachineKeyStore |

| 2 | UseDefaultKeyContainer |

| 4 | UseNonExportableKey |

| 8 | UseExistingKey |

| 16 | UseArchivableKey |

| 32 | UseUserProtectedKey |

| 64 | NoPrompt |

| 128 | CreateEphemeralKey |

## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public enum CspProviderFlags
{
	public Int32 value__; // 0x10
	public const CspProviderFlags NoFlags = 0; // 0x0
	public const CspProviderFlags UseMachineKeyStore = 1; // 0x0
	public const CspProviderFlags UseDefaultKeyContainer = 2; // 0x0
	public const CspProviderFlags UseNonExportableKey = 4; // 0x0
	public const CspProviderFlags UseExistingKey = 8; // 0x0
	public const CspProviderFlags UseArchivableKey = 16; // 0x0
	public const CspProviderFlags UseUserProtectedKey = 32; // 0x0
	public const CspProviderFlags NoPrompt = 64; // 0x0
	public const CspProviderFlags CreateEphemeralKey = 128; // 0x0


}
```