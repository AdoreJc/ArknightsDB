# MRoomViewModel

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Boolean m_isEditing`

- `BasicRoomInfoModel basicInfo`

- `ManufactInfoViewModel info`

- `MRoomEditStruct initEditInfo`

- `MRoomEditStruct editInfo`


## Properties

- `Boolean isEditing`


## Methods

- `BasicRoomInfoModel GetRoomInfo()`

- `Boolean get_isEditing()`

- `Void set_isEditing(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class MRoomViewModel : IBasicRoomModel, IHotfixable
{
	private Boolean m_isEditing; // 0x10
	public BasicRoomInfoModel basicInfo; // 0x18
	public ManufactInfoViewModel info; // 0x48
	public MRoomEditStruct initEditInfo; // 0x50
	public MRoomEditStruct editInfo; // 0x68
	private static DelegateBridge __Hotfix0_GetRoomInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_isEditing; // 0x8
	private static DelegateBridge __Hotfix0_set_isEditing; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isEditing { get; set; }

	// RVA: 0x3e04830 VA: 0x759641c830
	public BasicRoomInfoModel GetRoomInfo() { }
	// RVA: 0x3e044fc VA: 0x759641c4fc
	public Boolean get_isEditing() { }
	// RVA: 0x3e0269c VA: 0x759641a69c
	public Void set_isEditing(Boolean value) { }
	// RVA: 0x3e0312c VA: 0x759641b12c
	public Void .ctor() { }
}
```