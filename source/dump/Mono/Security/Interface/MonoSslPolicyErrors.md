# MonoSslPolicyErrors

**Namespace:** `Mono.Security.Interface`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | RemoteCertificateNotAvailable |

| 2 | RemoteCertificateNameMismatch |

| 4 | RemoteCertificateChainErrors |

## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Interface
public enum MonoSslPolicyErrors
{
	public Int32 value__; // 0x10
	public const MonoSslPolicyErrors None = 0; // 0x0
	public const MonoSslPolicyErrors RemoteCertificateNotAvailable = 1; // 0x0
	public const MonoSslPolicyErrors RemoteCertificateNameMismatch = 2; // 0x0
	public const MonoSslPolicyErrors RemoteCertificateChainErrors = 4; // 0x0


}
```