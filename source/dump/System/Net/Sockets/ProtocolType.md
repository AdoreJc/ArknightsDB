# ProtocolType

**Namespace:** `System.Net.Sockets`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | IP |

| 0 | IPv6HopByHopOptions |

| 1 | Icmp |

| 2 | Igmp |

| 3 | Ggp |

| 4 | IPv4 |

| 6 | Tcp |

| 12 | Pup |

| 17 | Udp |

| 22 | Idp |

| 41 | IPv6 |

| 43 | IPv6RoutingHeader |

| 44 | IPv6FragmentHeader |

| 50 | IPSecEncapsulatingSecurityPayload |

| 51 | IPSecAuthenticationHeader |

| 58 | IcmpV6 |

| 59 | IPv6NoNextHeader |

| 60 | IPv6DestinationOptions |

| 77 | ND |

| 255 | Raw |

| 0 | Unspecified |

| 1000 | Ipx |

| 1256 | Spx |

| 1257 | SpxII |

| 4294967295 | Unknown |

## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public enum ProtocolType
{
	public Int32 value__; // 0x10
	public const ProtocolType IP = 0; // 0x0
	public const ProtocolType IPv6HopByHopOptions = 0; // 0x0
	public const ProtocolType Icmp = 1; // 0x0
	public const ProtocolType Igmp = 2; // 0x0
	public const ProtocolType Ggp = 3; // 0x0
	public const ProtocolType IPv4 = 4; // 0x0
	public const ProtocolType Tcp = 6; // 0x0
	public const ProtocolType Pup = 12; // 0x0
	public const ProtocolType Udp = 17; // 0x0
	public const ProtocolType Idp = 22; // 0x0
	public const ProtocolType IPv6 = 41; // 0x0
	public const ProtocolType IPv6RoutingHeader = 43; // 0x0
	public const ProtocolType IPv6FragmentHeader = 44; // 0x0
	public const ProtocolType IPSecEncapsulatingSecurityPayload = 50; // 0x0
	public const ProtocolType IPSecAuthenticationHeader = 51; // 0x0
	public const ProtocolType IcmpV6 = 58; // 0x0
	public const ProtocolType IPv6NoNextHeader = 59; // 0x0
	public const ProtocolType IPv6DestinationOptions = 60; // 0x0
	public const ProtocolType ND = 77; // 0x0
	public const ProtocolType Raw = 255; // 0x0
	public const ProtocolType Unspecified = 0; // 0x0
	public const ProtocolType Ipx = 1000; // 0x0
	public const ProtocolType Spx = 1256; // 0x0
	public const ProtocolType SpxII = 1257; // 0x0
	public const ProtocolType Unknown = 4294967295; // 0x0


}
```