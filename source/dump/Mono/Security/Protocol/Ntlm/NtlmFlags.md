# NtlmFlags

**Namespace:** `Mono.Security.Protocol.Ntlm`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1 | NegotiateUnicode |

| 2 | NegotiateOem |

| 4 | RequestTarget |

| 512 | NegotiateNtlm |

| 4096 | NegotiateDomainSupplied |

| 8192 | NegotiateWorkstationSupplied |

| 32768 | NegotiateAlwaysSign |

| 524288 | NegotiateNtlm2Key |

| 536870912 | Negotiate128 |

| 2147483648 | Negotiate56 |

## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Protocol.Ntlm
public enum NtlmFlags
{
	public Int32 value__; // 0x10
	public const NtlmFlags NegotiateUnicode = 1; // 0x0
	public const NtlmFlags NegotiateOem = 2; // 0x0
	public const NtlmFlags RequestTarget = 4; // 0x0
	public const NtlmFlags NegotiateNtlm = 512; // 0x0
	public const NtlmFlags NegotiateDomainSupplied = 4096; // 0x0
	public const NtlmFlags NegotiateWorkstationSupplied = 8192; // 0x0
	public const NtlmFlags NegotiateAlwaysSign = 32768; // 0x0
	public const NtlmFlags NegotiateNtlm2Key = 524288; // 0x0
	public const NtlmFlags Negotiate128 = 536870912; // 0x0
	public const NtlmFlags Negotiate56 = 2147483648; // 0x0


}
```