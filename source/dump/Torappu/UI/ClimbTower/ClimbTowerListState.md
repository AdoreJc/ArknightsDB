# ClimbTowerListState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEntryMapView _mapView`

- `ClimbTowerEntryFloatView _floatPanel`

- `ClimbTowerItemRewardView _prefabReward`

- `RectTransform _containerReward`

- `RectTransform _topContainer`

- `ClimbTowerEntryMapProperty m_mapProperty`

- `ClimbTowerItemRewardProperty m_itemProperty`

- `ClimbTowerEntryFloatPanelProperty m_floatPanelProperty`

- `Boolean m_hasInited`

- `ClimbTowerItemRewardView m_itemView`

- `String m_cachedSelectCardId`


## Methods

- `Void OnDestroy()`

- `Void _TriggerClimbTowerBGM()`

- `Void _TriggerClimbTowerAVG()`

- `Void _InitIfNot()`

- `Void _OnItemClicked()`

- `Void _OnTowerClicked(ClimbTowerTowerType, String)`

- `Void _OnGodCardClicked()`

- `Void _OnGodCardItemClicked(String)`

- `Void _OnJumpToClimbTowerGodCardDetailState(IStateBean)`

- `Void _OnMissionClicked()`

- `Void <_InitIfNot>b__18_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerListState : PopupFadeState
{
	private ClimbTowerEntryMapView _mapView; // 0x70
	private ClimbTowerEntryFloatView _floatPanel; // 0x78
	private ClimbTowerItemRewardView _prefabReward; // 0x80
	private RectTransform _containerReward; // 0x88
	private RectTransform _topContainer; // 0x90
	private ClimbTowerEntryMapProperty m_mapProperty; // 0x98
	private ClimbTowerItemRewardProperty m_itemProperty; // 0xa0
	private ClimbTowerEntryFloatPanelProperty m_floatPanelProperty; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private ClimbTowerItemRewardView m_itemView; // 0xb8
	private String m_cachedSelectCardId; // 0xc0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__TriggerClimbTowerBGM; // 0x28
	private static DelegateBridge __Hotfix0__TriggerClimbTowerAVG; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnTowerClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnGodCardClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnGodCardItemClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpToClimbTowerGodCardDetailState; // 0x60
	private static DelegateBridge __Hotfix0__OnMissionClicked; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2ca2ee8 VA: 0x75952baee8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ca2f4c VA: 0x75952baf4c
	protected override Void OnEnter() { }
	// RVA: 0x2ca36a8 VA: 0x75952bb6a8
	protected override Void OnResume() { }
	// RVA: 0x2ca382c VA: 0x75952bb82c
	private Void OnDestroy() { }
	// RVA: 0x2ca38d8 VA: 0x75952bb8d8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ca3594 VA: 0x75952bb594
	private Void _TriggerClimbTowerBGM() { }
	// RVA: 0x2ca3418 VA: 0x75952bb418
	private Void _TriggerClimbTowerAVG() { }
	// RVA: 0x2ca2fd0 VA: 0x75952bafd0
	private Void _InitIfNot() { }
	// RVA: 0x2ca3a50 VA: 0x75952bba50
	private Void _OnItemClicked() { }
	// RVA: 0x2ca3bd0 VA: 0x75952bbbd0
	private Void _OnTowerClicked(ClimbTowerTowerType type, String towerId) { }
	// RVA: 0x2ca3e74 VA: 0x75952bbe74
	private Void _OnGodCardClicked() { }
	// RVA: 0x2ca3f2c VA: 0x75952bbf2c
	private Void _OnGodCardItemClicked(String cardId) { }
	// RVA: 0x2ca41d0 VA: 0x75952bc1d0
	private Void _OnJumpToClimbTowerGodCardDetailState(IStateBean stateBean) { }
	// RVA: 0x2ca42b0 VA: 0x75952bc2b0
	private Void _OnMissionClicked() { }
	// RVA: 0x2ca4460 VA: 0x75952bc460
	public Void .ctor() { }
	// RVA: 0x2ca4588 VA: 0x75952bc588
	private Void <_InitIfNot>b__18_0() { }
	// RVA: 0x2ca4700 VA: 0x75952bc700
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ca4708 VA: 0x75952bc708
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2ca4710 VA: 0x75952bc710
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```