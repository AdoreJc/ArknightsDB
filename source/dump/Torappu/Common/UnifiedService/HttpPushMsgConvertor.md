# HttpPushMsgConvertor

**Namespace:** `Torappu.Common.UnifiedService`


## Fields

- `MsgType m_msgType`


## Methods

- `Void _HandlePushMsg(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Common.UnifiedService
public class HttpPushMsgConvertor`2
{
	private MsgType m_msgType; // 0x0
	private Action`2 m_dispatcher; // 0x0


	// RVA: 0x VA: 0x0
	private Void .ctor() { }
	// RVA: 0x VA: 0x0
	public static HttpPushMsgConvertor`2 Gen(String pushMsgPath, MsgType toMsg, UnifiedServiceNetCoreHttp httpNet, Action`2 msgDispatcher) { }
	// RVA: 0x VA: 0x0
	private Void _HandlePushMsg(List`1 msgList) { }
}
```