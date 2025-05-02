# PayProcessPaymentState

**Namespace:** `HGSDK.UI`


## Methods

- `Void _OnPaymentFinished()`

- `Void <OnEnter>b__6_0(PayResult)`

- `Boolean <>xLuaBaseProxy_get_isCloseable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class PayProcessPaymentState : UIState
{
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_get_showBackPanel; // 0x8
	private static DelegateBridge __Hotfix0_get_isCloseable; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0__OnPaymentFinished; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override PayState myState { get; }
	public override Boolean showBackPanel { get; }
	public override Boolean isCloseable { get; }

	// RVA: 0x355d854 VA: 0x7595b75854
	public override PayState get_myState() { }
	// RVA: 0x355d8bc VA: 0x7595b758bc
	public override Boolean get_showBackPanel() { }
	// RVA: 0x355d920 VA: 0x7595b75920
	public override Boolean get_isCloseable() { }
	// RVA: 0x355d984 VA: 0x7595b75984
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x355daa0 VA: 0x7595b75aa0
	private Void _OnPaymentFinished() { }
	// RVA: 0x355db0c VA: 0x7595b75b0c
	public Void .ctor() { }
	// RVA: 0x355db78 VA: 0x7595b75b78
	private Void <OnEnter>b__6_0(PayResult payResult) { }
	// RVA: 0x355dbb4 VA: 0x7595b75bb4
	private Boolean <>xLuaBaseProxy_get_isCloseable() { }
}
```