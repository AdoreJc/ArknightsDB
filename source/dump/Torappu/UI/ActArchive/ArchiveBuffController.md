# ArchiveBuffController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveBuffListDataBinder _buffDataBinder`


## Methods

- `Void set_onItemClicked(Action`2)`

- `Void <>xLuaBaseProxy_OnItemClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveBuffController : ActArchiveController
{
	private ArchiveBuffListDataBinder _buffDataBinder; // 0x38
	private Action`2 <onItemClicked>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`2 onItemClicked { get; set; }

	// RVA: 0x3037948 VA: 0x759564f948
	private Action`2 get_onItemClicked() { }
	// RVA: 0x30379b0 VA: 0x759564f9b0
	public Void set_onItemClicked(Action`2 value) { }
	// RVA: 0x3037a34 VA: 0x759564fa34
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x3037af0 VA: 0x759564faf0
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3037ca8 VA: 0x759564fca8
	public Void .ctor() { }
	// RVA: 0x3037d18 VA: 0x759564fd18
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
}
```