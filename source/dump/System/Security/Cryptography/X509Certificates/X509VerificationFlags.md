# X509VerificationFlags

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NoFlag |

| 1 | IgnoreNotTimeValid |

| 2 | IgnoreCtlNotTimeValid |

| 4 | IgnoreNotTimeNested |

| 8 | IgnoreInvalidBasicConstraints |

| 16 | AllowUnknownCertificateAuthority |

| 32 | IgnoreWrongUsage |

| 64 | IgnoreInvalidName |

| 128 | IgnoreInvalidPolicy |

| 256 | IgnoreEndRevocationUnknown |

| 512 | IgnoreCtlSignerRevocationUnknown |

| 1024 | IgnoreCertificateAuthorityRevocationUnknown |

| 2048 | IgnoreRootRevocationUnknown |

| 4095 | AllFlags |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public enum X509VerificationFlags
{
	public Int32 value__; // 0x10
	public const X509VerificationFlags NoFlag = 0; // 0x0
	public const X509VerificationFlags IgnoreNotTimeValid = 1; // 0x0
	public const X509VerificationFlags IgnoreCtlNotTimeValid = 2; // 0x0
	public const X509VerificationFlags IgnoreNotTimeNested = 4; // 0x0
	public const X509VerificationFlags IgnoreInvalidBasicConstraints = 8; // 0x0
	public const X509VerificationFlags AllowUnknownCertificateAuthority = 16; // 0x0
	public const X509VerificationFlags IgnoreWrongUsage = 32; // 0x0
	public const X509VerificationFlags IgnoreInvalidName = 64; // 0x0
	public const X509VerificationFlags IgnoreInvalidPolicy = 128; // 0x0
	public const X509VerificationFlags IgnoreEndRevocationUnknown = 256; // 0x0
	public const X509VerificationFlags IgnoreCtlSignerRevocationUnknown = 512; // 0x0
	public const X509VerificationFlags IgnoreCertificateAuthorityRevocationUnknown = 1024; // 0x0
	public const X509VerificationFlags IgnoreRootRevocationUnknown = 2048; // 0x0
	public const X509VerificationFlags AllFlags = 4095; // 0x0


}
```