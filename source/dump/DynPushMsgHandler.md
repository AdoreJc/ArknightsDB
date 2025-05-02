# DynPushMsgHandler

**Namespace:** ` `


## Methods

- `Void SetPushMsgHandler(String, MsgHandlerCallback`1)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DynPushMsgHandler
{
	private static Dictionary`2 s_msgMap; // 0x0
	private List`1 m_handlers; // 0x10


	// RVA: 0x VA: 0x0
	public Void SetPushMsgHandler(String path, MsgHandlerCallback`1 pHandler) { }
	// RVA: 0x21e4a14 VA: 0x75947fca14
	public Void Clear() { }
	// RVA: 0x21e4c08 VA: 0x75947fcc08
	public static Boolean sHandlePushMessage(String path, List`1 msgList) { }
	// RVA: 0x21e4d50 VA: 0x75947fcd50
	public Void .ctor() { }
}
```