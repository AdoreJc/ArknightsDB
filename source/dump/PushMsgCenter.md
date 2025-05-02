# PushMsgCenter

**Namespace:** ` `


## Methods

- `Void SubscriptPushMsg(ISubMsgCenter, Boolean)`

- `Void OnPushMessage(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class PushMsgCenter
{
	private Dictionary`2 m_centers; // 0x10
	private ListDict`2 m_pendings; // 0x18


	// RVA: 0x35ac358 VA: 0x7595bc4358
	public Void SubscriptPushMsg(ISubMsgCenter center, Boolean enable) { }
	// RVA: 0x35ac18c VA: 0x7595bc418c
	public Void OnPushMessage(String msgType, String data) { }
	// RVA: 0x35ac784 VA: 0x7595bc4784
	public Void .ctor() { }
}
```