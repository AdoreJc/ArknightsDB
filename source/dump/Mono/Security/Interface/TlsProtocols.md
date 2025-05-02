# TlsProtocols

**Namespace:** `Mono.Security.Interface`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Zero |

| 128 | Tls10Client |

| 64 | Tls10Server |

| 192 | Tls10 |

| 512 | Tls11Client |

| 256 | Tls11Server |

| 768 | Tls11 |

| 2048 | Tls12Client |

| 1024 | Tls12Server |

| 3072 | Tls12 |

| 2688 | ClientMask |

| 1344 | ServerMask |

## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Interface
public enum TlsProtocols
{
	public Int32 value__; // 0x10
	public const TlsProtocols Zero = 0; // 0x0
	public const TlsProtocols Tls10Client = 128; // 0x0
	public const TlsProtocols Tls10Server = 64; // 0x0
	public const TlsProtocols Tls10 = 192; // 0x0
	public const TlsProtocols Tls11Client = 512; // 0x0
	public const TlsProtocols Tls11Server = 256; // 0x0
	public const TlsProtocols Tls11 = 768; // 0x0
	public const TlsProtocols Tls12Client = 2048; // 0x0
	public const TlsProtocols Tls12Server = 1024; // 0x0
	public const TlsProtocols Tls12 = 3072; // 0x0
	public const TlsProtocols ClientMask = 2688; // 0x0
	public const TlsProtocols ServerMask = 1344; // 0x0


}
```