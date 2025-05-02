# WebSocketStausCodes

**Namespace:** `BestHTTP.WebSocket`


## Fields

- `UInt32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 1000 | NormalClosure |

| 1001 | GoingAway |

| 1002 | ProtocolError |

| 1003 | WrongDataType |

| 1004 | Reserved |

| 1005 | NoStatusCode |

| 1006 | ClosedAbnormally |

| 1007 | DataError |

| 1008 | PolicyError |

| 1009 | TooBigMessage |

| 1010 | ExtensionExpected |

| 1011 | WrongRequest |

| 1015 | TLSHandshakeError |

## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.WebSocket
public enum WebSocketStausCodes
{
	public UInt32 value__; // 0x10
	public const WebSocketStausCodes NormalClosure = 1000; // 0x0
	public const WebSocketStausCodes GoingAway = 1001; // 0x0
	public const WebSocketStausCodes ProtocolError = 1002; // 0x0
	public const WebSocketStausCodes WrongDataType = 1003; // 0x0
	public const WebSocketStausCodes Reserved = 1004; // 0x0
	public const WebSocketStausCodes NoStatusCode = 1005; // 0x0
	public const WebSocketStausCodes ClosedAbnormally = 1006; // 0x0
	public const WebSocketStausCodes DataError = 1007; // 0x0
	public const WebSocketStausCodes PolicyError = 1008; // 0x0
	public const WebSocketStausCodes TooBigMessage = 1009; // 0x0
	public const WebSocketStausCodes ExtensionExpected = 1010; // 0x0
	public const WebSocketStausCodes WrongRequest = 1011; // 0x0
	public const WebSocketStausCodes TLSHandshakeError = 1015; // 0x0


}
```