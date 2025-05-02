# UpdateSubMsgCenter

**Namespace:** `Torappu.MsgSubscription`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.MsgSubscription
public class UpdateSubMsgCenter : SubscriptionMsgCenter`1
{
	private static DelegateBridge __Hotfix0_OnStop; // 0x0
	private static DelegateBridge __Hotfix0_get_msgType; // 0x8
	private static DelegateBridge __Hotfix0_CheckMsgValid; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override String msgType { get; }

	// RVA: 0x35abda4 VA: 0x7595bc3da4
	protected override Void OnStop() { }
	// RVA: 0x35abe08 VA: 0x7595bc3e08
	protected override String get_msgType() { }
	// RVA: 0x35abe84 VA: 0x7595bc3e84
	protected override Boolean CheckMsgValid(UpdateSubMsg msg) { }
	// RVA: 0x35abf18 VA: 0x7595bc3f18
	public Void .ctor() { }
}
```