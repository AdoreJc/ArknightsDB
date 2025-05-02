# CrisisV2RuneSingleTitleViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String <title>k__BackingField`

- `Int32 <dimension>k__BackingField`

- `Boolean <isDaily>k__BackingField`

- `String m_mapId`

- `String m_bagId`

- `Int32 m_uniqueSortId`


## Properties

- `String title`

- `Int32 dimension`

- `Boolean isDaily`


## Methods

- `String get_title()`

- `Void set_title(String)`

- `Int32 get_dimension()`

- `Void set_dimension(Int32)`

- `Boolean get_isDaily()`

- `Void set_isDaily(Boolean)`

- `Void LoadData(String, String, CrisisV2MapDetailData)`

- `String <>xLuaBaseProxy_GetGlobalId()`

- `String <>xLuaBaseProxy_GetItemId()`

- `String <>xLuaBaseProxy_GetBagId()`

- `SingleViewInfoType <>xLuaBaseProxy_GetViewType()`

- `Int32 <>xLuaBaseProxy_GetUniqueSortId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneSingleTitleViewModel : CrisisV2RuneSingleViewModel
{
	private String <title>k__BackingField; // 0x18
	private Int32 <dimension>k__BackingField; // 0x20
	private Boolean <isDaily>k__BackingField; // 0x24
	private String m_mapId; // 0x28
	private String m_bagId; // 0x30
	private Int32 m_uniqueSortId; // 0x38
	private static DelegateBridge __Hotfix0_get_title; // 0x0
	private static DelegateBridge __Hotfix0_set_title; // 0x8
	private static DelegateBridge __Hotfix0_get_dimension; // 0x10
	private static DelegateBridge __Hotfix0_set_dimension; // 0x18
	private static DelegateBridge __Hotfix0_get_isDaily; // 0x20
	private static DelegateBridge __Hotfix0_set_isDaily; // 0x28
	private static DelegateBridge __Hotfix0_GetGlobalId; // 0x30
	private static DelegateBridge __Hotfix0_GetItemId; // 0x38
	private static DelegateBridge __Hotfix0_GetBagId; // 0x40
	private static DelegateBridge __Hotfix0_GetViewType; // 0x48
	private static DelegateBridge __Hotfix0_GetUniqueSortId; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String title { get; set; }
	public Int32 dimension { get; set; }
	public Boolean isDaily { get; set; }

	// RVA: 0x2bf59fc VA: 0x759520d9fc
	public String get_title() { }
	// RVA: 0x2bf5a64 VA: 0x759520da64
	private Void set_title(String value) { }
	// RVA: 0x2bf5ae8 VA: 0x759520dae8
	public Int32 get_dimension() { }
	// RVA: 0x2bf5b50 VA: 0x759520db50
	private Void set_dimension(Int32 value) { }
	// RVA: 0x2bf5bcc VA: 0x759520dbcc
	public Boolean get_isDaily() { }
	// RVA: 0x2bf5c34 VA: 0x759520dc34
	private Void set_isDaily(Boolean value) { }
	// RVA: 0x2bf5cb4 VA: 0x759520dcb4
	public override String GetGlobalId() { }
	// RVA: 0x2bf5d38 VA: 0x759520dd38
	public override String GetItemId() { }
	// RVA: 0x2bf5da0 VA: 0x759520dda0
	public override String GetBagId() { }
	// RVA: 0x2bf5e08 VA: 0x759520de08
	public override SingleViewInfoType GetViewType() { }
	// RVA: 0x2bf5e70 VA: 0x759520de70
	public override Int32 GetUniqueSortId() { }
	// RVA: 0x2bf5ed8 VA: 0x759520ded8
	public Void LoadData(String runeMapId, String slotPackId, CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bf6018 VA: 0x759520e018
	public Void .ctor() { }
	// RVA: 0x2bf6084 VA: 0x759520e084
	private String <>xLuaBaseProxy_GetGlobalId() { }
	// RVA: 0x2bf6088 VA: 0x759520e088
	private String <>xLuaBaseProxy_GetItemId() { }
	// RVA: 0x2bf608c VA: 0x759520e08c
	private String <>xLuaBaseProxy_GetBagId() { }
	// RVA: 0x2bf6090 VA: 0x759520e090
	private SingleViewInfoType <>xLuaBaseProxy_GetViewType() { }
	// RVA: 0x2bf6094 VA: 0x759520e094
	private Int32 <>xLuaBaseProxy_GetUniqueSortId() { }
}
```