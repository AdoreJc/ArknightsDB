# ClimbTowerLayerViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerViewModel towerModel`

- `Int32 selectedIndex`

- `Int32 currLayerNum`

- `Int32 currLayerTryCount`

- `Int32 addLowerItemCount`

- `Int32 addHigherItemCount`

- `Boolean isHardMode`

- `Boolean isSubCardSelected`

- `OverrideData overrideData`


## Properties

- `ClimbTowerLevelModel selectedLevelModel`

- `Boolean isFirstItem`

- `Boolean isLastItem`


## Methods

- `Void InitDataIfNot(ClimbTowerViewModel)`

- `Void LoadData()`

- `Void _SetSelectIndex(Int32)`

- `ClimbTowerLevelModel get_selectedLevelModel()`

- `Boolean get_isFirstItem()`

- `Boolean get_isLastItem()`

- `Boolean IsLevelPassed(Int32)`

- `Boolean SwitchSelectedIndex(Boolean)`

- `Boolean SelectCurrIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLayerViewModel : IHotfixable
{
	public ClimbTowerViewModel towerModel; // 0x10
	public Int32 selectedIndex; // 0x18
	public Int32 currLayerNum; // 0x1c
	public Int32 currLayerTryCount; // 0x20
	public Int32 addLowerItemCount; // 0x24
	public Int32 addHigherItemCount; // 0x28
	public Boolean isHardMode; // 0x2c
	public Boolean isSubCardSelected; // 0x2d
	public OverrideData overrideData; // 0x30
	private static DelegateBridge __Hotfix0_InitDataIfNot; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__SetSelectIndex; // 0x10
	private static DelegateBridge __Hotfix0_get_currentlevels; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedLevelModel; // 0x20
	private static DelegateBridge __Hotfix0_get_isFirstItem; // 0x28
	private static DelegateBridge __Hotfix0_get_isLastItem; // 0x30
	private static DelegateBridge __Hotfix0_IsLevelPassed; // 0x38
	private static DelegateBridge __Hotfix0_SwitchSelectedIndex; // 0x40
	private static DelegateBridge __Hotfix0_SelectCurrIndex; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 currentlevels { get; }
	public ClimbTowerLevelModel selectedLevelModel { get; }
	public Boolean isFirstItem { get; }
	public Boolean isLastItem { get; }

	// RVA: 0x2cd8b94 VA: 0x75952f0b94
	public Void InitDataIfNot(ClimbTowerViewModel model) { }
	// RVA: 0x2cd8c38 VA: 0x75952f0c38
	public Void LoadData() { }
	// RVA: 0x2cd8d80 VA: 0x75952f0d80
	private Void _SetSelectIndex(Int32 index) { }
	// RVA: 0x2cd8ea0 VA: 0x75952f0ea0
	public List`1 get_currentlevels() { }
	// RVA: 0x2cd8f20 VA: 0x75952f0f20
	public ClimbTowerLevelModel get_selectedLevelModel() { }
	// RVA: 0x2cd8fc4 VA: 0x75952f0fc4
	public Boolean get_isFirstItem() { }
	// RVA: 0x2cd9038 VA: 0x75952f1038
	public Boolean get_isLastItem() { }
	// RVA: 0x2cd90d0 VA: 0x75952f10d0
	public Boolean IsLevelPassed(Int32 layerNum) { }
	// RVA: 0x2cd9154 VA: 0x75952f1154
	public Boolean SwitchSelectedIndex(Boolean switchDown) { }
	// RVA: 0x2cd9214 VA: 0x75952f1214
	public Boolean SelectCurrIndex() { }
	// RVA: 0x2cd929c VA: 0x75952f129c
	public Void .ctor() { }
}
```