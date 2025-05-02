# ClimbTowerTrapState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _trapGroupList`

- `RectTransform _backBtnRt`

- `ClimbTowerTrapStateBean m_stateBean`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `MenuAdapter m_menuAdapter`

- `String m_selectedTrapId`

- `ClimbTowerTrapType m_selectCardType`


## Methods

- `Void _InitIfNot()`

- `Boolean _NeedHideBuffBtnWithHolder()`

- `Boolean _NeedShowSquadBtn()`

- `Boolean _NeedShowProfessionBtns()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrapState : PopupFadeState
{
	private SimpleLayoutContent _trapGroupList; // 0x70
	private RectTransform _backBtnRt; // 0x78
	private ClimbTowerTrapStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private Adapter m_adapter; // 0x90
	private MenuAdapter m_menuAdapter; // 0x98
	private String m_selectedTrapId; // 0xa0
	private ClimbTowerTrapType m_selectCardType; // 0xa8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__NeedHideBuffBtnWithHolder; // 0x18
	private static DelegateBridge __Hotfix0__NeedShowSquadBtn; // 0x20
	private static DelegateBridge __Hotfix0__NeedShowProfessionBtns; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2c8f210 VA: 0x75952a7210
	protected override Void OnEnter() { }
	// RVA: 0x2c8f92c VA: 0x75952a792c
	protected override Void OnResume() { }
	// RVA: 0x2c8f74c VA: 0x75952a774c
	private Void _InitIfNot() { }
	// RVA: 0x2c8fa44 VA: 0x75952a7a44
	private Boolean _NeedHideBuffBtnWithHolder() { }
	// RVA: 0x2c8fb28 VA: 0x75952a7b28
	private Boolean _NeedShowSquadBtn() { }
	// RVA: 0x2c8fc00 VA: 0x75952a7c00
	private Boolean _NeedShowProfessionBtns() { }
	// RVA: 0x2c8fcd8 VA: 0x75952a7cd8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c8fd40 VA: 0x75952a7d40
	public Void .ctor() { }
	// RVA: 0x2c8feb0 VA: 0x75952a7eb0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c8feb8 VA: 0x75952a7eb8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```