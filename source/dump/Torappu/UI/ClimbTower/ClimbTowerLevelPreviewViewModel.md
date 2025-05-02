# ClimbTowerLevelPreviewViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerViewModel towerModel`

- `EnemyHandBookEverViewModel bossInfoModel`

- `Int32 selectedParamsIndex`


## Properties

- `Int32 selectedIndex`

- `Boolean isShowingBoss`

- `ClimbTowerLevelModel selectedLevelModel`

- `Boolean isFirstItem`

- `Boolean isLastItem`


## Methods

- `Void InitDataIfNot(ClimbTowerViewModel)`

- `Int32 get_selectedIndex()`

- `Boolean get_isShowingBoss()`

- `ClimbTowerLevelModel get_selectedLevelModel()`

- `Boolean get_isFirstItem()`

- `Boolean get_isLastItem()`

- `Boolean SwitchSelectedIndex(Boolean)`

- `Boolean SelectLastIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLevelPreviewViewModel : IHotfixable
{
	public ClimbTowerViewModel towerModel; // 0x10
	public SelectedParam[] selectedParams; // 0x18
	public EnemyHandBookEverViewModel bossInfoModel; // 0x20
	public Int32 selectedParamsIndex; // 0x28
	private static DelegateBridge __Hotfix0_InitDataIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_isShowingBoss; // 0x10
	private static DelegateBridge __Hotfix0_get_selectedLevelModel; // 0x18
	private static DelegateBridge __Hotfix0_get_isFirstItem; // 0x20
	private static DelegateBridge __Hotfix0_get_isLastItem; // 0x28
	private static DelegateBridge __Hotfix0_SwitchSelectedIndex; // 0x30
	private static DelegateBridge __Hotfix0_SelectLastIndex; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 selectedIndex { get; }
	public Boolean isShowingBoss { get; }
	public ClimbTowerLevelModel selectedLevelModel { get; }
	public Boolean isFirstItem { get; }
	public Boolean isLastItem { get; }

	// RVA: 0x2cd9380 VA: 0x75952f1380
	public Void InitDataIfNot(ClimbTowerViewModel model) { }
	// RVA: 0x2cd9564 VA: 0x75952f1564
	public Int32 get_selectedIndex() { }
	// RVA: 0x2cd95f0 VA: 0x75952f15f0
	public Boolean get_isShowingBoss() { }
	// RVA: 0x2cd967c VA: 0x75952f167c
	public ClimbTowerLevelModel get_selectedLevelModel() { }
	// RVA: 0x2cd972c VA: 0x75952f172c
	public Boolean get_isFirstItem() { }
	// RVA: 0x2cd979c VA: 0x75952f179c
	public Boolean get_isLastItem() { }
	// RVA: 0x2cd9830 VA: 0x75952f1830
	public Boolean SwitchSelectedIndex(Boolean switchDown) { }
	// RVA: 0x2cd98e8 VA: 0x75952f18e8
	public Boolean SelectLastIndex() { }
	// RVA: 0x2cd9988 VA: 0x75952f1988
	public Void .ctor() { }
}
```