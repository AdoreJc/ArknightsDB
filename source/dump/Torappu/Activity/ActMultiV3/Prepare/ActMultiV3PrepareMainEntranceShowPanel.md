# ActMultiV3PrepareMainEntranceShowPanel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3PrepareMainEntranceShowView _view`

- `ActMultiV3PrepareMainEntranceShowProperty m_prop`

- `GameObject m_entranceShowRoot`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnConfirmBtnClicked()`

- `Void <>xLuaBaseProxy_OnVisible(Boolean)`

- `Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase)`

- `IEnumerator <>xLuaBaseProxy_PlayExitAnimation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainEntranceShowPanel : ActMultiV3PrepareMainStepPanelBase
{
	private ActMultiV3PrepareMainEntranceShowView _view; // 0x38
	private ActMultiV3PrepareMainEntranceShowProperty m_prop; // 0x40
	private GameObject m_entranceShowRoot; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_get_step; // 0x0
	private static DelegateBridge __Hotfix0_GetMainViewConfig; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnVisible; // 0x18
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x20
	private static DelegateBridge __Hotfix0_PlayExitAnimation; // 0x28
	private static DelegateBridge __Hotfix0_EventOnConfirmBtnClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override ActMultiV3PrepareStepType step { get; }

	// RVA: 0x316be50 VA: 0x7595783e50
	public override ActMultiV3PrepareStepType get_step() { }
	// RVA: 0x316beb8 VA: 0x7595783eb8
	public override ActMultiV3PrepareMainViewConfig GetMainViewConfig() { }
	// RVA: 0x316bf20 VA: 0x7595783f20
	private Void _InitIfNot() { }
	// RVA: 0x316c478 VA: 0x7595784478
	protected override Void OnVisible(Boolean v) { }
	// RVA: 0x316c594 VA: 0x7595784594
	protected override Void OnUpdate(ActMultiV3StepUpdateCase updateCase) { }
	// RVA: 0x316c668 VA: 0x7595784668
	protected override IEnumerator PlayExitAnimation() { }
	// RVA: 0x316c73c VA: 0x759578473c
	public Void EventOnConfirmBtnClicked() { }
	// RVA: 0x316c804 VA: 0x7595784804
	public Void .ctor() { }
	// RVA: 0x316c874 VA: 0x7595784874
	private Void <>xLuaBaseProxy_OnVisible(Boolean P0) { }
	// RVA: 0x316c880 VA: 0x7595784880
	private Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase P0) { }
	// RVA: 0x316c888 VA: 0x7595784888
	private IEnumerator <>xLuaBaseProxy_PlayExitAnimation() { }
}
```