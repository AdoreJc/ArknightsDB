# ClimbTowerRecruitSubGodState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgBg`

- `ClimbTowerRecruitSubGodView _view`

- `RectTransform _backBtnRt`

- `Boolean m_hasInited`

- `ClimbTowerRecruitSubGodStateBean m_stateBean`

- `MenuAdapter m_menuAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _SelectItem(String)`

- `Void _OnConfirmCallBack()`

- `Void EventOnBtnConfirm()`

- `Void <EventOnBtnConfirm>b__12_0(ClimbTowerRecruitSubGodCardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRecruitSubGodState : PopupFadeState
{
	private Image _imgBg; // 0x70
	private ClimbTowerRecruitSubGodView _view; // 0x78
	private RectTransform _backBtnRt; // 0x80
	private Boolean m_hasInited; // 0x88
	private ClimbTowerRecruitSubGodStateBean m_stateBean; // 0x90
	private MenuAdapter m_menuAdapter; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SelectItem; // 0x18
	private static DelegateBridge __Hotfix0__OnConfirmCallBack; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBtnConfirm; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2cac94c VA: 0x75952c494c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2cac9b4 VA: 0x75952c49b4
	protected override Void OnEnter() { }
	// RVA: 0x2cacbd0 VA: 0x75952c4bd0
	private Void _InitIfNot() { }
	// RVA: 0x2cad1d0 VA: 0x75952c51d0
	private Void _SelectItem(String subCardId) { }
	// RVA: 0x2cad334 VA: 0x75952c5334
	private Void _OnConfirmCallBack() { }
	// RVA: 0x2cad564 VA: 0x75952c5564
	public Void EventOnBtnConfirm() { }
	// RVA: 0x2cad8ac VA: 0x75952c58ac
	public Void .ctor() { }
	// RVA: 0x2cadaac VA: 0x75952c5aac
	private Void <EventOnBtnConfirm>b__12_0(ClimbTowerRecruitSubGodCardResponse response) { }
	// RVA: 0x2cadab0 VA: 0x75952c5ab0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```