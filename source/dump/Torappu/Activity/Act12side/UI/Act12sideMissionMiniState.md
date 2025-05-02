# Act12sideMissionMiniState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideMissionMiniView _view`

- `RectTransform _backPressRt`

- `Boolean m_hasInited`

- `Act12sideStageController m_stageController`


## Properties

- `String activityId`

- `Act12sideStageController actController`


## Methods

- `String get_activityId()`

- `Act12sideStageController get_actController()`

- `Void _InitIfNot()`

- `Void _FetchStageController()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMissionMiniState : PopupFloatState
{
	private Act12sideMissionMiniView _view; // 0x70
	private RectTransform _backPressRt; // 0x78
	private Boolean m_hasInited; // 0x80
	private Act12sideStageController m_stageController; // 0x88
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_get_actController; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__FetchStageController; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected String activityId { get; }
	protected Act12sideStageController actController { get; }

	// RVA: 0x345f09c VA: 0x7595a7709c
	protected String get_activityId() { }
	// RVA: 0x345f16c VA: 0x7595a7716c
	protected Act12sideStageController get_actController() { }
	// RVA: 0x345f3b4 VA: 0x7595a773b4
	protected override Void OnEnter() { }
	// RVA: 0x345f684 VA: 0x7595a77684
	public override IStateBean GetCacheBean() { }
	// RVA: 0x345f57c VA: 0x7595a7757c
	private Void _InitIfNot() { }
	// RVA: 0x345f218 VA: 0x7595a77218
	private Void _FetchStageController() { }
	// RVA: 0x345f6e8 VA: 0x7595a776e8
	public Void .ctor() { }
	// RVA: 0x345f758 VA: 0x7595a77758
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```