# BossRushRelicState

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushRelicView _relicView`

- `Boolean m_hasInited`

- `BossRushRelicStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _SendRelicSelectRequest(Action)`

- `Void _RaiseTutorialSignal()`

- `Void _OnBackClick()`

- `Void _OnTopMenuRoutedToOtherPage(UIRouteTarget, Object, Action`2)`

- `Void _OnJumpToUpgrade(IStateBean)`

- `Void _OnSelectRelic(BossRushRelicNodeModel)`

- `Void _OnUpgradeClicked(BossRushRelicNodeModel)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicState : PopupFadeState
{
	private BossRushRelicView _relicView; // 0x70
	private Boolean m_hasInited; // 0x78
	private BossRushRelicStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__SendRelicSelectRequest; // 0x28
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x30
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x38
	private static DelegateBridge __Hotfix0__OnTopMenuRoutedToOtherPage; // 0x40
	private static DelegateBridge __Hotfix0__OnJumpToUpgrade; // 0x48
	private static DelegateBridge __Hotfix0__OnSelectRelic; // 0x50
	private static DelegateBridge __Hotfix0__OnUpgradeClicked; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2e5bedc VA: 0x7595473edc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e5bf44 VA: 0x7595473f44
	protected override Void OnEnter() { }
	// RVA: 0x2e5c490 VA: 0x7595474490
	protected override Void OnResume() { }
	// RVA: 0x2e5c708 VA: 0x7595474708
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2e5c180 VA: 0x7595474180
	private Void _InitIfNot() { }
	// RVA: 0x2e5c880 VA: 0x7595474880
	private Void _SendRelicSelectRequest(Action callback) { }
	// RVA: 0x2e5c6a4 VA: 0x75954746a4
	private Void _RaiseTutorialSignal() { }
	// RVA: 0x2e5cc6c VA: 0x7595474c6c
	private Void _OnBackClick() { }
	// RVA: 0x2e5cd7c VA: 0x7595474d7c
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x2e5cebc VA: 0x7595474ebc
	private Void _OnJumpToUpgrade(IStateBean stateBean) { }
	// RVA: 0x2e5d1bc VA: 0x75954751bc
	private Void _OnSelectRelic(BossRushRelicNodeModel relicNodeModel) { }
	// RVA: 0x2e5d3d8 VA: 0x75954753d8
	private Void _OnUpgradeClicked(BossRushRelicNodeModel relicNodeModel) { }
	// RVA: 0x2e5d588 VA: 0x7595475588
	public Void .ctor() { }
	// RVA: 0x2e5d6e4 VA: 0x75954756e4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e5d6ec VA: 0x75954756ec
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2e5d6f4 VA: 0x75954756f4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```