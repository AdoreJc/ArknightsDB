# DisconnectReason

**Namespace:** `FlyingWormConsole3.LiteNetLib`


## Fields

- `Int32 value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | ConnectionFailed |

| 1 | Timeout |

| 2 | HostUnreachable |

| 3 | NetworkUnreachable |

| 4 | RemoteConnectionClose |

| 5 | DisconnectPeerCalled |

| 6 | ConnectionRejected |

| 7 | InvalidProtocol |

| 8 | UnknownHost |

| 9 | Reconnect |

| 10 | PeerToPeerConnection |

## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib
public enum DisconnectReason
{
	public Int32 value__; // 0x10
	public const DisconnectReason ConnectionFailed = 0; // 0x0
	public const DisconnectReason Timeout = 1; // 0x0
	public const DisconnectReason HostUnreachable = 2; // 0x0
	public const DisconnectReason NetworkUnreachable = 3; // 0x0
	public const DisconnectReason RemoteConnectionClose = 4; // 0x0
	public const DisconnectReason DisconnectPeerCalled = 5; // 0x0
	public const DisconnectReason ConnectionRejected = 6; // 0x0
	public const DisconnectReason InvalidProtocol = 7; // 0x0
	public const DisconnectReason UnknownHost = 8; // 0x0
	public const DisconnectReason Reconnect = 9; // 0x0
	public const DisconnectReason PeerToPeerConnection = 10; // 0x0


}
```