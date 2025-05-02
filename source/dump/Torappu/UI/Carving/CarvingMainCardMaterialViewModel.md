# CarvingMainCardMaterialViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String <materialId>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `String <materialIconId>k__BackingField`

- `Int32 <materialRating>k__BackingField`

- `Int32 <count>k__BackingField`


## Properties

- `String materialId`

- `Int32 sortId`

- `String materialIconId`

- `Int32 materialRating`

- `Int32 count`


## Methods

- `String get_materialId()`

- `Void set_materialId(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `String get_materialIconId()`

- `Void set_materialIconId(String)`

- `Int32 get_materialRating()`

- `Void set_materialRating(Int32)`

- `Int32 get_count()`

- `Void set_count(Int32)`

- `Void SetData(Act35SideMaterialData, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainCardMaterialViewModel : IHotfixable
{
	private String <materialId>k__BackingField; // 0x10
	private Int32 <sortId>k__BackingField; // 0x18
	private String <materialIconId>k__BackingField; // 0x20
	private Int32 <materialRating>k__BackingField; // 0x28
	private Int32 <count>k__BackingField; // 0x2c
	private static DelegateBridge __Hotfix0_get_materialId; // 0x0
	private static DelegateBridge __Hotfix0_set_materialId; // 0x8
	private static DelegateBridge __Hotfix0_get_sortId; // 0x10
	private static DelegateBridge __Hotfix0_set_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_materialIconId; // 0x20
	private static DelegateBridge __Hotfix0_set_materialIconId; // 0x28
	private static DelegateBridge __Hotfix0_get_materialRating; // 0x30
	private static DelegateBridge __Hotfix0_set_materialRating; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x40
	private static DelegateBridge __Hotfix0_set_count; // 0x48
	private static DelegateBridge __Hotfix0_SetData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String materialId { get; set; }
	public Int32 sortId { get; set; }
	public String materialIconId { get; set; }
	public Int32 materialRating { get; set; }
	public Int32 count { get; set; }

	// RVA: 0x2daa698 VA: 0x75953c2698
	public String get_materialId() { }
	// RVA: 0x2daa700 VA: 0x75953c2700
	private Void set_materialId(String value) { }
	// RVA: 0x2daa784 VA: 0x75953c2784
	public Int32 get_sortId() { }
	// RVA: 0x2daa7ec VA: 0x75953c27ec
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2da679c VA: 0x75953be79c
	public String get_materialIconId() { }
	// RVA: 0x2daa868 VA: 0x75953c2868
	private Void set_materialIconId(String value) { }
	// RVA: 0x2da6734 VA: 0x75953be734
	public Int32 get_materialRating() { }
	// RVA: 0x2daa8ec VA: 0x75953c28ec
	private Void set_materialRating(Int32 value) { }
	// RVA: 0x2daa968 VA: 0x75953c2968
	public Int32 get_count() { }
	// RVA: 0x2daa9d0 VA: 0x75953c29d0
	private Void set_count(Int32 value) { }
	// RVA: 0x2daaa4c VA: 0x75953c2a4c
	public Void SetData(Act35SideMaterialData matData, Int32 count) { }
	// RVA: 0x2daab0c VA: 0x75953c2b0c
	public Void .ctor() { }
}
```