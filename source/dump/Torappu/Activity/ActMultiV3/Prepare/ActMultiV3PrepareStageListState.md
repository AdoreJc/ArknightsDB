# ActMultiV3PrepareStageListState

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `RectTransform _viewHolder`

- `RectTransform _backPressRt`

- `ActMultiV3StageListView _viewPrefab`

- `Boolean m_inited`

- `ActMultiV3StageListView m_view`

- `StateBean m_stateBean`

- `UICompDialogMgr m_dialogMgr`

- `Int32 m_infoDialogInst`


## Methods

- `Void _InitIfNot()`

- `Boolean _CheckUIStable()`

- `Void _OnTabClicked(Int64)`

- `Void _OnStageClicked(String)`

- `Void _OnBtnInfoClicked()`

- `Void OnBackClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareStageListState : ActMultiV3StageListViewState
{
	private RectTransform _viewHolder; // 0x70
	private RectTransform _backPressRt; // 0x78
	private ActMultiV3StageListView _viewPrefab; // 0x80
	private Boolean m_inited; // 0x88
	private ActMultiV3StageListView m_view; // 0x90
	private StateBean m_stateBean; // 0x98
	private UICompDialogMgr m_dialogMgr; // 0xa0
	private Int32 m_infoDialogInst; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x20
	private static DelegateBridge __Hotfix0__CheckUIStable; // 0x28
	private static DelegateBridge __Hotfix0__OnTabClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnStageClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnBtnInfoClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x317a868 VA: 0x7595792868
	private Void _InitIfNot() { }
	// RVA: 0x317aa5c VA: 0x7595792a5c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x317aac4 VA: 0x7595792ac4
	protected override Void OnEnter() { }
	// RVA: 0x317ab68 VA: 0x7595792b68
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x317b27c VA: 0x759579327c
	public override Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x317b300 VA: 0x7595793300
	private Boolean _CheckUIStable() { }
	// RVA: 0x317aca0 VA: 0x7595792ca0
	private Void _OnTabClicked(Int64 msg) { }
	// RVA: 0x317ad9c VA: 0x7595792d9c
	private Void _OnStageClicked(String stageId) { }
	// RVA: 0x317b0b8 VA: 0x75957930b8
	private Void _OnBtnInfoClicked() { }
	// RVA: 0x317afb4 VA: 0x7595792fb4
	public Void OnBackClicked() { }
	// RVA: 0x317b3dc VA: 0x75957933dc
	public Void .ctor() { }
	// RVA: 0x317b538 VA: 0x7595793538
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```