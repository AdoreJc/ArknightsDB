# ServerWideSubMsg

**Namespace:** `Torappu.MsgSubscription`


## Fields

- `String content`

- `Int32 loop`


## Methods

- `Void FlushData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.MsgSubscription
public class ServerWideSubMsg : ISubscriptionMsg, IHotfixable
{
	public const String MSG_TYPE_NAME; // 0x0
	public String content; // 0x10
	public Int32 loop; // 0x18
	private static DelegateBridge __Hotfix0_FlushData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x35ab788 VA: 0x7595bc3788
	public Void FlushData(String data) { }
	// RVA: 0x35ab990 VA: 0x7595bc3990
	public Void .ctor() { }
}
```