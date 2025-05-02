# StageZoneGroupPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Tween m_defaultEnterTween`

- `Tween m_defaultExitTween`

- `CanvasGroup m_canvasGroup`

- `GroupState m_groupState`

- `InitOptions initOptions`

- `ZoneGroupViewModel <viewModel>k__BackingField`

- `ZoneGroupViewProperty <viewProp>k__BackingField`


## Properties

- `StagePage stagePage`

- `GroupState groupState`

- `CanvasGroup alphaHandler`

- `Boolean isActive`

- `Boolean isTransiting`

- `ZoneGroupViewModel viewModel`

- `ZoneGroupViewProperty viewProp`


## Methods

- `StagePage get_stagePage()`

- `GroupState get_groupState()`

- `CanvasGroup get_alphaHandler()`

- `Boolean get_isActive()`

- `Boolean get_isTransiting()`

- `ZoneGroupViewModel get_viewModel()`

- `Void set_viewModel(ZoneGroupViewModel)`

- `ZoneGroupViewProperty get_viewProp()`

- `Void set_viewProp(ZoneGroupViewProperty)`

- `IEnumerator _EnterProcess()`

- `IEnumerator _ExitProcess()`

- `Void Init(InitOptions)`

- `Void _CoroutineWithPage(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneGroupPanel : DataBinder`1, IHotfixable
{
	protected const Single DEFAULT_ANIM_DUR; // 0x0
	protected const Single DEFAULT_FADEOUT_DUR; // 0x0
	private Tween m_defaultEnterTween; // 0x20
	private Tween m_defaultExitTween; // 0x28
	private CanvasGroup m_canvasGroup; // 0x30
	private GroupState m_groupState; // 0x38
	protected InitOptions initOptions; // 0x40
	private ZoneGroupViewModel <viewModel>k__BackingField; // 0x50
	private ZoneGroupViewProperty <viewProp>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_stagePage; // 0x0
	private static DelegateBridge __Hotfix0_get_onZoneSelected; // 0x8
	private static DelegateBridge __Hotfix0_get_groupState; // 0x10
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x18
	private static DelegateBridge __Hotfix0_get_isActive; // 0x20
	private static DelegateBridge __Hotfix0_get_isTransiting; // 0x28
	private static DelegateBridge __Hotfix0_get_viewModel; // 0x30
	private static DelegateBridge __Hotfix0_set_viewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_viewProp; // 0x40
	private static DelegateBridge __Hotfix0_set_viewProp; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x50
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x58
	private static DelegateBridge __Hotfix0__EnterProcess; // 0x60
	private static DelegateBridge __Hotfix0__ExitProcess; // 0x68
	private static DelegateBridge __Hotfix0_EnterYieldInstruction; // 0x70
	private static DelegateBridge __Hotfix0_ExitYieldInstruction; // 0x78
	private static DelegateBridge __Hotfix0_CancelEnter; // 0x80
	private static DelegateBridge __Hotfix0_CancelExit; // 0x88
	private static DelegateBridge __Hotfix0_Init; // 0x90
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x98
	private static DelegateBridge __Hotfix0__CoroutineWithPage; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	protected StagePage stagePage { get; }
	protected Action`2 onZoneSelected { get; }
	protected GroupState groupState { get; }
	protected CanvasGroup alphaHandler { get; }
	protected Boolean isActive { get; }
	protected Boolean isTransiting { get; }
	protected ZoneGroupViewModel viewModel { get; set; }
	protected ZoneGroupViewProperty viewProp { get; set; }

	// RVA: 0x2fb27a0 VA: 0x75955ca7a0
	protected StagePage get_stagePage() { }
	// RVA: 0x2fb3bac VA: 0x75955cbbac
	protected Action`2 get_onZoneSelected() { }
	// RVA: 0x2fb3c14 VA: 0x75955cbc14
	protected GroupState get_groupState() { }
	// RVA: 0x2fb3cdc VA: 0x75955cbcdc
	protected CanvasGroup get_alphaHandler() { }
	// RVA: 0x2fb3db4 VA: 0x75955cbdb4
	protected Boolean get_isActive() { }
	// RVA: 0x2fb3e28 VA: 0x75955cbe28
	protected Boolean get_isTransiting() { }
	// RVA: 0x2fb3e9c VA: 0x75955cbe9c
	protected ZoneGroupViewModel get_viewModel() { }
	// RVA: 0x2fb3f04 VA: 0x75955cbf04
	private Void set_viewModel(ZoneGroupViewModel value) { }
	// RVA: 0x2fb3f88 VA: 0x75955cbf88
	protected ZoneGroupViewProperty get_viewProp() { }
	// RVA: 0x2fb3ff0 VA: 0x75955cbff0
	private Void set_viewProp(ZoneGroupViewProperty value) { }
	// RVA: 0x2fb1bc4 VA: 0x75955c9bc4
	protected virtual Void OnEnter() { }
	// RVA: 0x2fb2068 VA: 0x75955ca068
	protected virtual Void OnDataUpdated(ZoneGroupViewProperty prop) { }
	// RVA: 0x2fb4074 VA: 0x75955cc074
	private IEnumerator _EnterProcess() { }
	// RVA: 0x2fb4148 VA: 0x75955cc148
	private IEnumerator _ExitProcess() { }
	// RVA: 0x2fb421c VA: 0x75955cc21c
	protected virtual IEnumerator EnterYieldInstruction() { }
	// RVA: 0x2fb42f0 VA: 0x75955cc2f0
	protected virtual IEnumerator ExitYieldInstruction() { }
	// RVA: 0x2fb43b4 VA: 0x75955cc3b4
	protected virtual Void CancelEnter() { }
	// RVA: 0x2fb4454 VA: 0x75955cc454
	protected virtual Void CancelExit() { }
	// RVA: 0x2fb44f4 VA: 0x75955cc4f4
	public Void Init(InitOptions initOptions) { }
	// RVA: 0x2fb364c VA: 0x75955cb64c
	public override Void OnValueChanged(ZoneGroupViewProperty property) { }
	// RVA: 0x2fb4584 VA: 0x75955cc584
	private Void _CoroutineWithPage(IEnumerator coroutine) { }
	// RVA: 0x2fb28b4 VA: 0x75955ca8b4
	public Void .ctor() { }
}
```