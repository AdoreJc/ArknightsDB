# NtlmAuthLevel

**Namespace:** `Mono.Security.Protocol.Ntlm`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | LM_and_NTLM |

| 1 | LM_and_NTLM_and_try_NTLMv2_Session |

| 2 | NTLM_only |

| 3 | NTLMv2_only |

## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Protocol.Ntlm
public enum NtlmAuthLevel
{
	public Int32 value__; // 0x10
	public const NtlmAuthLevel LM_and_NTLM = 0; // 0x0
	public const NtlmAuthLevel LM_and_NTLM_and_try_NTLMv2_Session = 1; // 0x0
	public const NtlmAuthLevel NTLM_only = 2; // 0x0
	public const NtlmAuthLevel NTLMv2_only = 3; // 0x0


}
```