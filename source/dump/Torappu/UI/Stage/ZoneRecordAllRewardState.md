# ZoneRecordAllRewardState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `ZoneRecordAllRewardsView _view`

- `RectTransform _backPressRt`

- `ZoneRecordStateBean m_stateBean`

- `Boolean m_isInit`


## Methods

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__7_0(GameObject)`

- `Void <_InitIfNot>b__7_1()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordAllRewardState : PopupFloatState
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private ZoneRecordAllRewardsView _view; // 0x78
	private RectTransform _backPressRt; // 0x80
	private ZoneRecordStateBean m_stateBean; // 0x88
	private Boolean m_isInit; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fc3fc4 VA: 0x75955dbfc4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2fc402c VA: 0x75955dc02c
	protected override Void OnEnter() { }
	// RVA: 0x2fc40e4 VA: 0x75955dc0e4
	private Void _InitIfNot() { }
	// RVA: 0x2fc4240 VA: 0x75955dc240
	public Void .ctor() { }
	// RVA: 0x2fc42f0 VA: 0x75955dc2f0
	private Void <_InitIfNot>b__7_0(GameObject instObj) { }
	// RVA: 0x2fc43a8 VA: 0x75955dc3a8
	private Void <_InitIfNot>b__7_1() { }
	// RVA: 0x2fc43b8 VA: 0x75955dc3b8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```