# WebSocketSample

**Namespace:** ` `


## Fields

- `String address`

- `String msgToSend`

- `String Text`

- `WebSocket webSocket`

- `Vector2 scrollPos`


## Methods

- `Void OnDestroy()`

- `Void OnGUI()`

- `Void OnOpen(WebSocket)`

- `Void OnMessageReceived(WebSocket, String)`

- `Void OnClosed(WebSocket, UInt16, String)`

- `Void OnError(WebSocket, Exception)`

- `Void <OnGUI>b__6_0()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class WebSocketSample : MonoBehaviour
{
	private String address; // 0x18
	private String msgToSend; // 0x20
	private String Text; // 0x28
	private WebSocket webSocket; // 0x30
	private Vector2 scrollPos; // 0x38


	// RVA: 0x6456784 VA: 0x7598a6e784
	private Void OnDestroy() { }
	// RVA: 0x6456798 VA: 0x7598a6e798
	private Void OnGUI() { }
	// RVA: 0x6456868 VA: 0x7598a6e868
	private Void OnOpen(WebSocket ws) { }
	// RVA: 0x6456928 VA: 0x7598a6e928
	private Void OnMessageReceived(WebSocket ws, String message) { }
	// RVA: 0x64569a4 VA: 0x7598a6e9a4
	private Void OnClosed(WebSocket ws, UInt16 code, String message) { }
	// RVA: 0x6456a78 VA: 0x7598a6ea78
	private Void OnError(WebSocket ws, Exception ex) { }
	// RVA: 0x6456bf4 VA: 0x7598a6ebf4
	public Void .ctor() { }
	// RVA: 0x6456ca4 VA: 0x7598a6eca4
	private Void <OnGUI>b__6_0() { }
}
```