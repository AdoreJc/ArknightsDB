# RL03SubTransExpeditionReturnController

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03SubTransExpeditionReturnView _view`

- `Boolean m_waitForConfirm`


## Methods

- `Boolean _EnsureExpeditionReturn()`

- `Void _SendExpeditionDialogRequest()`

- `Boolean <TransCoroutine>b__8_0()`

- `Void <_SendExpeditionDialogRequest>b__10_0(RoguelikeExpedReturnResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03SubTransExpeditionReturnController : SubTransitionBase`1
{
	private RL03SubTransExpeditionReturnView _view; // 0x18
	private Boolean m_waitForConfirm; // 0x20
	private static DelegateBridge __Hotfix0__EnsureExpeditionReturn; // 0x0
	private static DelegateBridge __Hotfix0_GetParam; // 0x8
	private static DelegateBridge __Hotfix0_SetParam; // 0x10
	private static DelegateBridge __Hotfix0_GetTransType; // 0x18
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0__SendExpeditionDialogRequest; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2bb2904 VA: 0x75951ca904
	private Boolean _EnsureExpeditionReturn() { }
	// RVA: 0x2bb29e8 VA: 0x75951ca9e8
	protected override ExpeditionReturnModel GetParam(TransOptions transOptions) { }
	// RVA: 0x2bb2ee8 VA: 0x75951caee8
	protected override Void SetParam(ExpeditionReturnModel expeditionReturnModel) { }
	// RVA: 0x2bb30f0 VA: 0x75951cb0f0
	public override SubTransType GetTransType() { }
	// RVA: 0x2bb3158 VA: 0x75951cb158
	public override IEnumerator TransCoroutine() { }
	// RVA: 0x2bb322c VA: 0x75951cb22c
	public override Void Reset() { }
	// RVA: 0x2bb3364 VA: 0x75951cb364
	private Void _SendExpeditionDialogRequest() { }
	// RVA: 0x2bb354c VA: 0x75951cb54c
	public Void .ctor() { }
	// RVA: 0x2bb35dc VA: 0x75951cb5dc
	private Boolean <TransCoroutine>b__8_0() { }
	// RVA: 0x2bb35e4 VA: 0x75951cb5e4
	private Void <_SendExpeditionDialogRequest>b__10_0(RoguelikeExpedReturnResponse response) { }
}
```