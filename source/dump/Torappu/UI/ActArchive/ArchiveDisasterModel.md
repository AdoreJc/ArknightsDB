# ArchiveDisasterModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedTypeId`

- `Boolean showSwitchAnim`


## Methods

- `String _GetDefaultSelectId()`

- `Boolean HasNewMark()`

- `Void SetSelectedType(String)`

- `DisasterTypeModel GetSelectedTypeModel()`

- `Void LoadData(String, RoguelikeArchiveComponentData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDisasterModel : IHotfixable
{
	public ListDict`2 disasterTypeModels; // 0x10
	public String selectedTypeId; // 0x18
	public Boolean showSwitchAnim; // 0x20
	private static DelegateBridge __Hotfix0__GetDefaultSelectId; // 0x0
	private static DelegateBridge __Hotfix0_HasNewMark; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedType; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedTypeModel; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x304a1a8 VA: 0x75956621a8
	private String _GetDefaultSelectId() { }
	// RVA: 0x304a290 VA: 0x7595662290
	public Boolean HasNewMark() { }
	// RVA: 0x304a620 VA: 0x7595662620
	public Void SetSelectedType(String typeId) { }
	// RVA: 0x3048ddc VA: 0x7595660ddc
	public DisasterTypeModel GetSelectedTypeModel() { }
	// RVA: 0x304a724 VA: 0x7595662724
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData) { }
	// RVA: 0x304b3f0 VA: 0x75956633f0
	public Void .ctor() { }
}
```