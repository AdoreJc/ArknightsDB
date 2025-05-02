# BuildingFuncFurnitureModel

**Namespace:** `Torappu.Building`


## Fields

- `FurnOutlineInfo m_currFurnOutlineInfo`


## Properties

- `FurnOutlineInfo outlineInfo`


## Methods

- `FurnOutlineInfo get_outlineInfo()`

- `Void set_outlineInfo(FurnOutlineInfo)`

- `Void OnInit()`

- `Void UpdateData()`

- `Void UpdateData(FurnitureSubType)`

- `BuildingFuncFurniBtnModel GetFuncFurnSubTypeModel(FurnitureSubType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingFuncFurnitureModel : IHotfixable
{
	private Dictionary`2 m_models; // 0x10
	private FurnOutlineInfo m_currFurnOutlineInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_outlineInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_outlineInfo; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge __Hotfix1_UpdateData; // 0x20
	private static DelegateBridge __Hotfix0_GetFuncFurnSubTypeModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public FurnOutlineInfo outlineInfo { get; set; }

	// RVA: 0x3788580 VA: 0x7595da0580
	public FurnOutlineInfo get_outlineInfo() { }
	// RVA: 0x37885e4 VA: 0x7595da05e4
	public Void set_outlineInfo(FurnOutlineInfo value) { }
	// RVA: 0x3788674 VA: 0x7595da0674
	public Void OnInit() { }
	// RVA: 0x3788898 VA: 0x7595da0898
	public Void UpdateData() { }
	// RVA: 0x3788ae4 VA: 0x7595da0ae4
	public Void UpdateData(FurnitureSubType subType) { }
	// RVA: 0x3788c34 VA: 0x7595da0c34
	public BuildingFuncFurniBtnModel GetFuncFurnSubTypeModel(FurnitureSubType subType) { }
	// RVA: 0x3788cd4 VA: 0x7595da0cd4
	public Void .ctor() { }
}
```