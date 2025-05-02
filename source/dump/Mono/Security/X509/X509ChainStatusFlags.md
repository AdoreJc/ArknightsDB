# X509ChainStatusFlags

**Namespace:** `Mono.Security.X509`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1024 | InvalidBasicConstraints |

| 0 | NoError |

| 8 | NotSignatureValid |

| 2 | NotTimeNested |

| 1 | NotTimeValid |

| 65536 | PartialChain |

| 32 | UntrustedRoot |

## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public enum X509ChainStatusFlags
{
	public Int32 value__; // 0x10
	public const X509ChainStatusFlags InvalidBasicConstraints = 1024; // 0x0
	public const X509ChainStatusFlags NoError = 0; // 0x0
	public const X509ChainStatusFlags NotSignatureValid = 8; // 0x0
	public const X509ChainStatusFlags NotTimeNested = 2; // 0x0
	public const X509ChainStatusFlags NotTimeValid = 1; // 0x0
	public const X509ChainStatusFlags PartialChain = 65536; // 0x0
	public const X509ChainStatusFlags UntrustedRoot = 32; // 0x0


}
```