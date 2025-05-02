# RL03SubTransPredictController

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03SubTransPredictView _view`

- `Boolean m_waitForConfirm`


## Methods

- `Boolean _EnsurePendingEvent()`

- `Void OnConfirmBtnClicked()`

- `Boolean <TransCoroutine>b__9_0()`

- `Void <OnConfirmBtnClicked>b__11_0(RL03ConfirmPredictResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03SubTransPredictController : SubTransitionBase`1
{
	private RL03SubTransPredictView _view; // 0x18
	private Boolean m_waitForConfirm; // 0x20
	private static DelegateBridge __Hotfix0__EnsurePendingEvent; // 0x0
	private static DelegateBridge __Hotfix0_GetParam; // 0x8
	private static DelegateBridge __Hotfix0_SetParam; // 0x10
	private static DelegateBridge __Hotfix0_GetTransType; // 0x18
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0_OnConfirmBtnClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2bb44ac VA: 0x75951cc4ac
	private Boolean _EnsurePendingEvent() { }
	// RVA: 0x2bb45ac VA: 0x75951cc5ac
	protected override PredictModel GetParam(TransOptions transOptions) { }
	// RVA: 0x2bb48e4 VA: 0x75951cc8e4
	protected override Void SetParam(PredictModel predictModel) { }
	// RVA: 0x2bb4a94 VA: 0x75951cca94
	public override SubTransType GetTransType() { }
	// RVA: 0x2bb4afc VA: 0x75951ccafc
	public override IEnumerator TransCoroutine() { }
	// RVA: 0x2bb4bd0 VA: 0x75951ccbd0
	public override Void Reset() { }
	// RVA: 0x2bb4cf0 VA: 0x75951cccf0
	public Void OnConfirmBtnClicked() { }
	// RVA: 0x2bb4ed8 VA: 0x75951cced8
	public Void .ctor() { }
	// RVA: 0x2bb4f68 VA: 0x75951ccf68
	private Boolean <TransCoroutine>b__9_0() { }
	// RVA: 0x2bb4f70 VA: 0x75951ccf70
	private Void <OnConfirmBtnClicked>b__11_0(RL03ConfirmPredictResponse response) { }
}
```