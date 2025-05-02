# BuildingWorkshopStateBean

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `BuildingWorkshopProperty property`


## Properties

- `Int32 workCount`


## Methods

- `Void LoadData(BuildingWorkshopModel)`

- `Void RefreshViewModel(Boolean)`

- `Int32 get_workCount()`

- `MaxCountLimitReason TryToSetWorkCount(Int32)`

- `Void SwitchItemProtect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public BuildingWorkshopProperty property; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_workCount; // 0x10
	private static DelegateBridge __Hotfix0_TryToSetWorkCount; // 0x18
	private static DelegateBridge __Hotfix0_SwitchItemProtect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Int32 workCount { get; }

	// RVA: 0x3d670bc VA: 0x759637f0bc
	public Void LoadData(BuildingWorkshopModel workshopModel) { }
	// RVA: 0x3d67310 VA: 0x759637f310
	public Void RefreshViewModel(Boolean reCalcCount) { }
	// RVA: 0x3d67530 VA: 0x759637f530
	public Int32 get_workCount() { }
	// RVA: 0x3d67628 VA: 0x759637f628
	public MaxCountLimitReason TryToSetWorkCount(Int32 count) { }
	// RVA: 0x3d67704 VA: 0x759637f704
	public Void SwitchItemProtect() { }
	// RVA: 0x3d677f8 VA: 0x759637f7f8
	public Void .ctor() { }
}
```