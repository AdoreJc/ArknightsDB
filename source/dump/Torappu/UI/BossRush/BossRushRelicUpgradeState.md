# BossRushRelicUpgradeState

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushRelicUpgradeView _relicUpgradeView`

- `RectTransform _backBtn`

- `Boolean m_hasInited`

- `BossRushRelicUpgradeStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void OnBackClicked()`

- `Void OnUpgradeClicked(String)`

- `Void _SendRelicUpgradeRequest(String, String, Action)`

- `Void <OnUpgradeClicked>b__8_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicUpgradeState : PopupFloatState
{
	private BossRushRelicUpgradeView _relicUpgradeView; // 0x70
	private RectTransform _backBtn; // 0x78
	private Boolean m_hasInited; // 0x80
	private BossRushRelicUpgradeStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnUpgradeClicked; // 0x20
	private static DelegateBridge __Hotfix0__SendRelicUpgradeRequest; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2e5e7c8 VA: 0x75954767c8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e5e830 VA: 0x7595476830
	protected override Void OnEnter() { }
	// RVA: 0x2e5e9a8 VA: 0x75954769a8
	private Void _InitIfNot() { }
	// RVA: 0x2e5eca0 VA: 0x7595476ca0
	public Void OnBackClicked() { }
	// RVA: 0x2e5ed14 VA: 0x7595476d14
	public Void OnUpgradeClicked(String rID) { }
	// RVA: 0x2e5ee1c VA: 0x7595476e1c
	private Void _SendRelicUpgradeRequest(String aId, String rId, Action onComplete) { }
	// RVA: 0x2e5f10c VA: 0x759547710c
	public Void .ctor() { }
	// RVA: 0x2e5f264 VA: 0x7595477264
	private Void <OnUpgradeClicked>b__8_0() { }
	// RVA: 0x2e5f2dc VA: 0x75954772dc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```