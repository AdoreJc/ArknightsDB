# SslPolicyErrors

**Namespace:** `System.Net.Security`


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
// Dll : System.dll
// Namespace : System.Net.Security
public enum SslPolicyErrors
{
	public Int32 value__; // 0x10
	public const SslPolicyErrors None = 0; // 0x0
	public const SslPolicyErrors RemoteCertificateNotAvailable = 1; // 0x0
	public const SslPolicyErrors RemoteCertificateNameMismatch = 2; // 0x0
	public const SslPolicyErrors RemoteCertificateChainErrors = 4; // 0x0


}
```