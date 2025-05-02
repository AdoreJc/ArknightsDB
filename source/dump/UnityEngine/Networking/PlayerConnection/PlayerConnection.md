# PlayerConnection

**Namespace:** `UnityEngine.Networking.PlayerConnection`


## Fields

- `PlayerEditorConnectionEvents m_PlayerEditorConnectionEvents`

- `Boolean m_IsInitilized`


## Properties

- `Boolean isConnected`


## Methods

- `Boolean get_isConnected()`

- `Void OnEnable()`

- `IPlayerEditorConnectionNative GetConnectionNativeApi()`

- `Void Register(Guid, UnityAction`1)`

- `Void Unregister(Guid, UnityAction`1)`

- `Void RegisterConnection(UnityAction`1)`

- `Void RegisterDisconnection(UnityAction`1)`

- `Void UnregisterConnection(UnityAction`1)`

- `Void UnregisterDisconnection(UnityAction`1)`

- `Void Send(Guid, Byte[])`

- `Boolean TrySend(Guid, Byte[])`

- `Boolean BlockUntilRecvMsg(Guid, Int32)`

- `Void DisconnectAll()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Networking.PlayerConnection
public class PlayerConnection : ScriptableObject
{
	internal static IPlayerEditorConnectionNative connectionNative; // 0x0
	private PlayerEditorConnectionEvents m_PlayerEditorConnectionEvents; // 0x18
	private List`1 m_connectedPlayers; // 0x20
	private Boolean m_IsInitilized; // 0x28
	private static PlayerConnection s_Instance; // 0x8

	public static PlayerConnection instance { get; }
	public Boolean isConnected { get; }

	// RVA: 0x689a8b0 VA: 0x7598eb28b0
	public static PlayerConnection get_instance() { }
	// RVA: 0x689aa00 VA: 0x7598eb2a00
	public Boolean get_isConnected() { }
	// RVA: 0x689a944 VA: 0x7598eb2944
	private static PlayerConnection CreateInstance() { }
	// RVA: 0x689ab1c VA: 0x7598eb2b1c
	public Void OnEnable() { }
	// RVA: 0x689aa9c VA: 0x7598eb2a9c
	private IPlayerEditorConnectionNative GetConnectionNativeApi() { }
	// RVA: 0x689abdc VA: 0x7598eb2bdc
	public Void Register(Guid messageId, UnityAction`1 callback) { }
	// RVA: 0x689b02c VA: 0x7598eb302c
	public Void Unregister(Guid messageId, UnityAction`1 callback) { }
	// RVA: 0x689b348 VA: 0x7598eb3348
	public Void RegisterConnection(UnityAction`1 callback) { }
	// RVA: 0x689b4e8 VA: 0x7598eb34e8
	public Void RegisterDisconnection(UnityAction`1 callback) { }
	// RVA: 0x689b548 VA: 0x7598eb3548
	public Void UnregisterConnection(UnityAction`1 callback) { }
	// RVA: 0x689b5a8 VA: 0x7598eb35a8
	public Void UnregisterDisconnection(UnityAction`1 callback) { }
	// RVA: 0x689b608 VA: 0x7598eb3608
	public Void Send(Guid messageId, Byte[] data) { }
	// RVA: 0x689b764 VA: 0x7598eb3764
	public Boolean TrySend(Guid messageId, Byte[] data) { }
	// RVA: 0x689b8c0 VA: 0x7598eb38c0
	public Boolean BlockUntilRecvMsg(Guid messageId, Int32 timeout) { }
	// RVA: 0x689bb00 VA: 0x7598eb3b00
	public Void DisconnectAll() { }
	// RVA: 0x689bb9c VA: 0x7598eb3b9c
	private static Void MessageCallbackInternal(IntPtr data, UInt64 size, UInt64 guid, String messageId) { }
	// RVA: 0x689c164 VA: 0x7598eb4164
	private static Void ConnectedCallbackInternal(Int32 playerId) { }
	// RVA: 0x689c240 VA: 0x7598eb4240
	private static Void DisconnectedCallback(Int32 playerId) { }
	// RVA: 0x689c2d4 VA: 0x7598eb42d4
	public Void .ctor() { }
}
```