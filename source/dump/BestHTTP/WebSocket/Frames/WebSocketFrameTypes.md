# WebSocketFrameTypes

**Namespace:** `BestHTTP.WebSocket.Frames`


## Fields

- `Byte value__`


## Enum Values
| Value | Name |
|-------|------|

| 0 | Continuation |

| 1 | Text |

| 2 | Binary |

| 8 | ConnectionClose |

| 9 | Ping |

| 10 | Pong |

## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.WebSocket.Frames
public enum WebSocketFrameTypes
{
	public Byte value__; // 0x10
	public const WebSocketFrameTypes Continuation = 0; // 0x0
	public const WebSocketFrameTypes Text = 1; // 0x0
	public const WebSocketFrameTypes Binary = 2; // 0x0
	public const WebSocketFrameTypes ConnectionClose = 8; // 0x0
	public const WebSocketFrameTypes Ping = 9; // 0x0
	public const WebSocketFrameTypes Pong = 10; // 0x0


}
```