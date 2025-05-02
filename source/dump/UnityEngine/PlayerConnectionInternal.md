# PlayerConnectionInternal

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
internal class PlayerConnectionInternal : IPlayerEditorConnectionNative
{


	// RVA: 0x6880610 VA: 0x7598e98610
	private Void UnityEngine.IPlayerEditorConnectionNative.SendMessage(Guid messageId, Byte[] data, Int32 playerId) { }
	// RVA: 0x6880790 VA: 0x7598e98790
	private Boolean UnityEngine.IPlayerEditorConnectionNative.TrySendMessage(Guid messageId, Byte[] data, Int32 playerId) { }
	// RVA: 0x6880914 VA: 0x7598e98914
	private Void UnityEngine.IPlayerEditorConnectionNative.Poll() { }
	// RVA: 0x6880964 VA: 0x7598e98964
	private Void UnityEngine.IPlayerEditorConnectionNative.RegisterInternal(Guid messageId) { }
	// RVA: 0x6880a24 VA: 0x7598e98a24
	private Void UnityEngine.IPlayerEditorConnectionNative.UnregisterInternal(Guid messageId) { }
	// RVA: 0x6880ae4 VA: 0x7598e98ae4
	private Void UnityEngine.IPlayerEditorConnectionNative.Initialize() { }
	// RVA: 0x6880b34 VA: 0x7598e98b34
	private Boolean UnityEngine.IPlayerEditorConnectionNative.IsConnected() { }
	// RVA: 0x6880b84 VA: 0x7598e98b84
	private Void UnityEngine.IPlayerEditorConnectionNative.DisconnectAll() { }
	// RVA: 0x6880b5c VA: 0x7598e98b5c
	private static Boolean IsConnected() { }
	// RVA: 0x6880b0c VA: 0x7598e98b0c
	private static Void Initialize() { }
	// RVA: 0x68809e8 VA: 0x7598e989e8
	private static Void RegisterInternal(String messageId) { }
	// RVA: 0x6880aa8 VA: 0x7598e98aa8
	private static Void UnregisterInternal(String messageId) { }
	// RVA: 0x688073c VA: 0x7598e9873c
	private static Void SendMessage(String messageId, Byte[] data, Int32 playerId) { }
	// RVA: 0x68808c0 VA: 0x7598e988c0
	private static Boolean TrySendMessage(String messageId, Byte[] data, Int32 playerId) { }
	// RVA: 0x688093c VA: 0x7598e9893c
	private static Void PollInternal() { }
	// RVA: 0x6880bac VA: 0x7598e98bac
	private static Void DisconnectAll() { }
	// RVA: 0x6880bd4 VA: 0x7598e98bd4
	public Void .ctor() { }
}
```