# ClimbTowerInitCurseDisplayState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerInitCurseDisplayView _view`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `RectTransform _backBtnRt`

- `Boolean m_hasInited`

- `ClimbTowerInitCurseDisplayStateBean m_stateBean`

- `MenuAdapter m_menuAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _SendSettleGameRequest()`

- `Void _NavToLayerState()`

- `Void _EventOnBtnNext()`

- `Void EventOnBtnQuit()`

- `Void <_SendSettleGameRequest>b__10_0(ClimbTowerSettleGameResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitCurseDisplayState : PopupFadeState
{
	private ClimbTowerInitCurseDisplayView _view; // 0x70
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x78
	private RectTransform _backBtnRt; // 0x80
	private Boolean m_hasInited; // 0x88
	private ClimbTowerInitCurseDisplayStateBean m_stateBean; // 0x90
	private MenuAdapter m_menuAdapter; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SendSettleGameRequest; // 0x18
	private static DelegateBridge __Hotfix0__NavToLayerState; // 0x20
	private static DelegateBridge __Hotfix0__EventOnBtnNext; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnQuit; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2ca6d10 VA: 0x75952bed10
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ca6d78 VA: 0x75952bed78
	protected override Void OnEnter() { }
	// RVA: 0x2ca6fd0 VA: 0x75952befd0
	private Void _InitIfNot() { }
	// RVA: 0x2ca7464 VA: 0x75952bf464
	private Void _SendSettleGameRequest() { }
	// RVA: 0x2ca7634 VA: 0x75952bf634
	private Void _NavToLayerState() { }
	// RVA: 0x2ca77b0 VA: 0x75952bf7b0
	private Void _EventOnBtnNext() { }
	// RVA: 0x2ca792c VA: 0x75952bf92c
	public Void EventOnBtnQuit() { }
	// RVA: 0x2ca7bb0 VA: 0x75952bfbb0
	public Void .ctor() { }
	// RVA: 0x2ca7d08 VA: 0x75952bfd08
	private Void <_SendSettleGameRequest>b__10_0(ClimbTowerSettleGameResponse response) { }
	// RVA: 0x2ca7d0c VA: 0x75952bfd0c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```