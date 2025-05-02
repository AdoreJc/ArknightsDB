# UpdateSubMsg

**Namespace:** `Torappu.MsgSubscription`


## Fields

- `String content`

- `Int32 loop`

- `String majorVersion`


## Methods

- `Void FlushData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.MsgSubscription
public class UpdateSubMsg : ISubscriptionMsg, IHotfixable
{
	public const String MSG_TYPE_NAME; // 0x0
	public String content; // 0x10
	public Int32 loop; // 0x18
	public String majorVersion; // 0x20
	private static DelegateBridge __Hotfix0_FlushData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x35abb0c VA: 0x7595bc3b0c
	public Void FlushData(String data) { }
	// RVA: 0x35abd34 VA: 0x7595bc3d34
	public Void .ctor() { }
}
```