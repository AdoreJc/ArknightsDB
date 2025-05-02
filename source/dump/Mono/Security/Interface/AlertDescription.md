# AlertDescription

**Namespace:** `Mono.Security.Interface`


## Fields

- `Byte value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | CloseNotify |

| 10 | UnexpectedMessage |

| 20 | BadRecordMAC |

| 21 | DecryptionFailed_RESERVED |

| 22 | RecordOverflow |

| 30 | DecompressionFailure |

| 40 | HandshakeFailure |

| 41 | NoCertificate_RESERVED |

| 42 | BadCertificate |

| 43 | UnsupportedCertificate |

| 44 | CertificateRevoked |

| 45 | CertificateExpired |

| 46 | CertificateUnknown |

| 47 | IlegalParameter |

| 48 | UnknownCA |

| 49 | AccessDenied |

| 50 | DecodeError |

| 51 | DecryptError |

| 60 | ExportRestriction |

| 70 | ProtocolVersion |

| 71 | InsuficientSecurity |

| 80 | InternalError |

| 90 | UserCancelled |

| 100 | NoRenegotiation |

| 110 | UnsupportedExtension |

## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Interface
public enum AlertDescription
{
	public Byte value__; // 0x10
	public const AlertDescription CloseNotify = 0; // 0x0
	public const AlertDescription UnexpectedMessage = 10; // 0x0
	public const AlertDescription BadRecordMAC = 20; // 0x0
	public const AlertDescription DecryptionFailed_RESERVED = 21; // 0x0
	public const AlertDescription RecordOverflow = 22; // 0x0
	public const AlertDescription DecompressionFailure = 30; // 0x0
	public const AlertDescription HandshakeFailure = 40; // 0x0
	public const AlertDescription NoCertificate_RESERVED = 41; // 0x0
	public const AlertDescription BadCertificate = 42; // 0x0
	public const AlertDescription UnsupportedCertificate = 43; // 0x0
	public const AlertDescription CertificateRevoked = 44; // 0x0
	public const AlertDescription CertificateExpired = 45; // 0x0
	public const AlertDescription CertificateUnknown = 46; // 0x0
	public const AlertDescription IlegalParameter = 47; // 0x0
	public const AlertDescription UnknownCA = 48; // 0x0
	public const AlertDescription AccessDenied = 49; // 0x0
	public const AlertDescription DecodeError = 50; // 0x0
	public const AlertDescription DecryptError = 51; // 0x0
	public const AlertDescription ExportRestriction = 60; // 0x0
	public const AlertDescription ProtocolVersion = 70; // 0x0
	public const AlertDescription InsuficientSecurity = 71; // 0x0
	public const AlertDescription InternalError = 80; // 0x0
	public const AlertDescription UserCancelled = 90; // 0x0
	public const AlertDescription NoRenegotiation = 100; // 0x0
	public const AlertDescription UnsupportedExtension = 110; // 0x0


}
```