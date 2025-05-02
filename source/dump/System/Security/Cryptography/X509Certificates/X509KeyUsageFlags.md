# X509KeyUsageFlags

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | None |

| 1 | EncipherOnly |

| 2 | CrlSign |

| 4 | KeyCertSign |

| 8 | KeyAgreement |

| 16 | DataEncipherment |

| 32 | KeyEncipherment |

| 64 | NonRepudiation |

| 128 | DigitalSignature |

| 32768 | DecipherOnly |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public enum X509KeyUsageFlags
{
	public Int32 value__; // 0x10
	public const X509KeyUsageFlags None = 0; // 0x0
	public const X509KeyUsageFlags EncipherOnly = 1; // 0x0
	public const X509KeyUsageFlags CrlSign = 2; // 0x0
	public const X509KeyUsageFlags KeyCertSign = 4; // 0x0
	public const X509KeyUsageFlags KeyAgreement = 8; // 0x0
	public const X509KeyUsageFlags DataEncipherment = 16; // 0x0
	public const X509KeyUsageFlags KeyEncipherment = 32; // 0x0
	public const X509KeyUsageFlags NonRepudiation = 64; // 0x0
	public const X509KeyUsageFlags DigitalSignature = 128; // 0x0
	public const X509KeyUsageFlags DecipherOnly = 32768; // 0x0


}
```