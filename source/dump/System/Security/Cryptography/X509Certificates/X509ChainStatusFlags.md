# X509ChainStatusFlags

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | NoError |

| 1 | NotTimeValid |

| 2 | NotTimeNested |

| 4 | Revoked |

| 8 | NotSignatureValid |

| 16 | NotValidForUsage |

| 32 | UntrustedRoot |

| 64 | RevocationStatusUnknown |

| 128 | Cyclic |

| 256 | InvalidExtension |

| 512 | InvalidPolicyConstraints |

| 1024 | InvalidBasicConstraints |

| 2048 | InvalidNameConstraints |

| 4096 | HasNotSupportedNameConstraint |

| 8192 | HasNotDefinedNameConstraint |

| 16384 | HasNotPermittedNameConstraint |

| 32768 | HasExcludedNameConstraint |

| 65536 | PartialChain |

| 131072 | CtlNotTimeValid |

| 262144 | CtlNotSignatureValid |

| 524288 | CtlNotValidForUsage |

| 16777216 | OfflineRevocation |

| 33554432 | NoIssuanceChainPolicy |

| 67108864 | ExplicitDistrust |

| 134217728 | HasNotSupportedCriticalExtension |

| 1048576 | HasWeakSignature |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public enum X509ChainStatusFlags
{
	public Int32 value__; // 0x10
	public const X509ChainStatusFlags NoError = 0; // 0x0
	public const X509ChainStatusFlags NotTimeValid = 1; // 0x0
	public const X509ChainStatusFlags NotTimeNested = 2; // 0x0
	public const X509ChainStatusFlags Revoked = 4; // 0x0
	public const X509ChainStatusFlags NotSignatureValid = 8; // 0x0
	public const X509ChainStatusFlags NotValidForUsage = 16; // 0x0
	public const X509ChainStatusFlags UntrustedRoot = 32; // 0x0
	public const X509ChainStatusFlags RevocationStatusUnknown = 64; // 0x0
	public const X509ChainStatusFlags Cyclic = 128; // 0x0
	public const X509ChainStatusFlags InvalidExtension = 256; // 0x0
	public const X509ChainStatusFlags InvalidPolicyConstraints = 512; // 0x0
	public const X509ChainStatusFlags InvalidBasicConstraints = 1024; // 0x0
	public const X509ChainStatusFlags InvalidNameConstraints = 2048; // 0x0
	public const X509ChainStatusFlags HasNotSupportedNameConstraint = 4096; // 0x0
	public const X509ChainStatusFlags HasNotDefinedNameConstraint = 8192; // 0x0
	public const X509ChainStatusFlags HasNotPermittedNameConstraint = 16384; // 0x0
	public const X509ChainStatusFlags HasExcludedNameConstraint = 32768; // 0x0
	public const X509ChainStatusFlags PartialChain = 65536; // 0x0
	public const X509ChainStatusFlags CtlNotTimeValid = 131072; // 0x0
	public const X509ChainStatusFlags CtlNotSignatureValid = 262144; // 0x0
	public const X509ChainStatusFlags CtlNotValidForUsage = 524288; // 0x0
	public const X509ChainStatusFlags OfflineRevocation = 16777216; // 0x0
	public const X509ChainStatusFlags NoIssuanceChainPolicy = 33554432; // 0x0
	public const X509ChainStatusFlags ExplicitDistrust = 67108864; // 0x0
	public const X509ChainStatusFlags HasNotSupportedCriticalExtension = 134217728; // 0x0
	public const X509ChainStatusFlags HasWeakSignature = 1048576; // 0x0


}
```