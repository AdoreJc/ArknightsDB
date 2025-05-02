# ArchiveDisasterController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveDisasterListDataBinder _disasterDataBinder`


## Properties

- `ArchiveDisasterListDataBinder dataBinder`


## Methods

- `Void set_onItemClicked(Action`2)`

- `ArchiveDisasterListDataBinder get_dataBinder()`

- `Sprite LoadDisasterIcon(String, String)`

- `Void <>xLuaBaseProxy_OnItemClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDisasterController : ActArchiveController, IHotfixable
{
	private ArchiveDisasterListDataBinder _disasterDataBinder; // 0x38
	private Action`2 <onItemClicked>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_dataBinder; // 0x10
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x18
	private static DelegateBridge __Hotfix0_LoadDisasterIcon; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`2 onItemClicked { get; set; }
	public ArchiveDisasterListDataBinder dataBinder { get; }

	// RVA: 0x30481a0 VA: 0x75956601a0
	private Action`2 get_onItemClicked() { }
	// RVA: 0x3048208 VA: 0x7595660208
	public Void set_onItemClicked(Action`2 value) { }
	// RVA: 0x304828c VA: 0x759566028c
	public ArchiveDisasterListDataBinder get_dataBinder() { }
	// RVA: 0x30482f4 VA: 0x75956602f4
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x30483b0 VA: 0x75956603b0
	public Sprite LoadDisasterIcon(String archiveId, String iconId) { }
	// RVA: 0x3048448 VA: 0x7595660448
	public Void .ctor() { }
	// RVA: 0x30484b8 VA: 0x75956604b8
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
}
```