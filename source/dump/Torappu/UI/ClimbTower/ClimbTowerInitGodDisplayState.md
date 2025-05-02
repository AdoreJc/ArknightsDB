# ClimbTowerInitGodDisplayState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerInitGodDisplayView _view`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `RectTransform _backBtnRt`

- `ClimbTowerInitGodDisplayStateBean m_stateBean`

- `MenuAdapter m_menuAdapter`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnCardClick(Int32)`

- `Void _SendSettleGameRequest()`

- `Void _NavToLayerState()`

- `Void _NavToBuffSelectState()`

- `Boolean _NeedShowTrapButton()`

- `Void _EventOnBtnNext()`

- `Void EventOnBtnQuit()`

- `Void <_SendSettleGameRequest>b__11_0(ClimbTowerSettleGameResponse)`

- `Void <_EventOnBtnNext>b__15_0(ClimbTowerInitGodCardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitGodDisplayState : PopupFadeState
{
	private ClimbTowerInitGodDisplayView _view; // 0x70
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x78
	private RectTransform _backBtnRt; // 0x80
	private ClimbTowerInitGodDisplayStateBean m_stateBean; // 0x88
	private MenuAdapter m_menuAdapter; // 0x90
	private Boolean m_hasInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnCardClick; // 0x18
	private static DelegateBridge __Hotfix0__SendSettleGameRequest; // 0x20
	private static DelegateBridge __Hotfix0__NavToLayerState; // 0x28
	private static DelegateBridge __Hotfix0__NavToBuffSelectState; // 0x30
	private static DelegateBridge __Hotfix0__NeedShowTrapButton; // 0x38
	private static DelegateBridge __Hotfix0__EventOnBtnNext; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnQuit; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2ca8f84 VA: 0x75952c0f84
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ca8fec VA: 0x75952c0fec
	protected override Void OnEnter() { }
	// RVA: 0x2ca9248 VA: 0x75952c1248
	private Void _InitIfNot() { }
	// RVA: 0x2ca98e8 VA: 0x75952c18e8
	private Void _OnCardClick(Int32 index) { }
	// RVA: 0x2ca9a9c VA: 0x75952c1a9c
	private Void _SendSettleGameRequest() { }
	// RVA: 0x2ca9c6c VA: 0x75952c1c6c
	private Void _NavToLayerState() { }
	// RVA: 0x2ca9de8 VA: 0x75952c1de8
	private Void _NavToBuffSelectState() { }
	// RVA: 0x2ca9f64 VA: 0x75952c1f64
	private Boolean _NeedShowTrapButton() { }
	// RVA: 0x2caa064 VA: 0x75952c2064
	private Void _EventOnBtnNext() { }
	// RVA: 0x2caa4a0 VA: 0x75952c24a0
	public Void EventOnBtnQuit() { }
	// RVA: 0x2caa724 VA: 0x75952c2724
	public Void .ctor() { }
	// RVA: 0x2caa87c VA: 0x75952c287c
	private Void <_SendSettleGameRequest>b__11_0(ClimbTowerSettleGameResponse response) { }
	// RVA: 0x2caa880 VA: 0x75952c2880
	private Void <_EventOnBtnNext>b__15_0(ClimbTowerInitGodCardResponse response) { }
	// RVA: 0x2caa884 VA: 0x75952c2884
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```