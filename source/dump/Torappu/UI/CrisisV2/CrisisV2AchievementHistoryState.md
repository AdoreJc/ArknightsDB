# CrisisV2AchievementHistoryState

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2SettleView _settleViewPrefab`

- `RectTransform _viewContainer`

- `CrisisV2AchievementHistoryStateBean m_stateBean`

- `Boolean m_hasInited`

- `CrisisV2SettleView m_settleView`

- `CrisisV2CacheServerData m_crisisV2ServerData`


## Methods

- `Void _InitIfNot()`

- `Void _OnCloseBtnClicked()`

- `Void _LoadDataAndRender()`

- `Boolean _LoadSnapshotDiffData(Param, CrisisV2SnapShotBase)`

- `Boolean _LoadDataFromDetailSnapshot(Param, CrisisV2DetailSnapshot)`

- `Boolean _LoadDataFromSimpleSnapshot(Param, CrisisV2SimpleSnapshot)`

- `Boolean _LoadRuneList(Param, CrisisV2SnapShotBase, Boolean)`

- `Boolean _LoadCommentList(Param, CrisisV2SnapShotBase, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementHistoryState : PopupFadeState, IHotfixable
{
	private CrisisV2SettleView _settleViewPrefab; // 0x70
	private RectTransform _viewContainer; // 0x78
	private CrisisV2AchievementHistoryStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private CrisisV2SettleView m_settleView; // 0x90
	private CrisisV2CacheServerData m_crisisV2ServerData; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnCloseBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__LoadDataAndRender; // 0x28
	private static DelegateBridge __Hotfix0__LoadSnapshotDiffData; // 0x30
	private static DelegateBridge __Hotfix0__LoadDataFromDetailSnapshot; // 0x38
	private static DelegateBridge __Hotfix0__LoadDataFromSimpleSnapshot; // 0x40
	private static DelegateBridge __Hotfix0__LoadRuneList; // 0x48
	private static DelegateBridge __Hotfix0__LoadCommentList; // 0x50
	private static DelegateBridge __Hotfix0__PickRandomSkinInfo; // 0x58
	private static DelegateBridge __Hotfix0__CreateSquadItemFromSharedChar; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2bd5ae4 VA: 0x75951edae4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2bd5b4c VA: 0x75951edb4c
	protected override Void OnEnter() { }
	// RVA: 0x2bd6174 VA: 0x75951ee174
	protected override Void OnPause() { }
	// RVA: 0x2bd5c20 VA: 0x75951edc20
	private Void _InitIfNot() { }
	// RVA: 0x2bd6238 VA: 0x75951ee238
	private Void _OnCloseBtnClicked() { }
	// RVA: 0x2bd5e00 VA: 0x75951ede00
	private Void _LoadDataAndRender() { }
	// RVA: 0x2bd6394 VA: 0x75951ee394
	private Boolean _LoadSnapshotDiffData(Param input, CrisisV2SnapShotBase snapshot) { }
	// RVA: 0x2bd7734 VA: 0x75951ef734
	private Boolean _LoadDataFromDetailSnapshot(Param input, CrisisV2DetailSnapshot snapshot) { }
	// RVA: 0x2bd720c VA: 0x75951ef20c
	private Boolean _LoadDataFromSimpleSnapshot(Param input, CrisisV2SimpleSnapshot snapshot) { }
	// RVA: 0x2bd64e4 VA: 0x75951ee4e4
	private Boolean _LoadRuneList(Param input, CrisisV2SnapShotBase snapshot, Boolean isCurrentSeason) { }
	// RVA: 0x2bd6b3c VA: 0x75951eeb3c
	private Boolean _LoadCommentList(Param input, CrisisV2SnapShotBase snapshot, Boolean isCurrentSeason) { }
	// RVA: 0x2bd7b90 VA: 0x75951efb90
	private static SquadSkinInfo _PickRandomSkinInfo(List`1 skinInfoList) { }
	// RVA: 0x2bd7a50 VA: 0x75951efa50
	private static SquadItemStruct _CreateSquadItemFromSharedChar(SharedCharData charData, Boolean withPotential) { }
	// RVA: 0x2bd7d58 VA: 0x75951efd58
	public Void .ctor() { }
	// RVA: 0x2bd7e74 VA: 0x75951efe74
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2bd7e7c VA: 0x75951efe7c
	private Void <>xLuaBaseProxy_OnPause() { }
}
```