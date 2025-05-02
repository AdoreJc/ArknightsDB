# BuildingWorkshopWholeViewModel

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `BuildingWorkshopModel workshopModel`

- `Int32 <workCount>k__BackingField`


## Properties

- `Int32 workCount`


## Methods

- `Int32 get_workCount()`

- `Void set_workCount(Int32)`

- `MaxCountLimitReason TryToSetWorkCount(Int32)`

- `Boolean CheckIfNeedProtectPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopWholeViewModel : IHotfixable
{
	public BuildingWorkshopModel workshopModel; // 0x10
	private Int32 <workCount>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_workCount; // 0x0
	private static DelegateBridge __Hotfix0_set_workCount; // 0x8
	private static DelegateBridge __Hotfix0_TryToSetWorkCount; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfNeedProtectPanel; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Int32 workCount { get; set; }

	// RVA: 0x3d675c0 VA: 0x759637f5c0
	public Int32 get_workCount() { }
	// RVA: 0x3d67910 VA: 0x759637f910
	private Void set_workCount(Int32 value) { }
	// RVA: 0x3d67220 VA: 0x759637f220
	public MaxCountLimitReason TryToSetWorkCount(Int32 targetCount) { }
	// RVA: 0x3d67428 VA: 0x759637f428
	public Boolean CheckIfNeedProtectPanel() { }
	// RVA: 0x3d671b0 VA: 0x759637f1b0
	public Void .ctor() { }
}
```