# CarvingMaterialModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String <materialId>k__BackingField`

- `String <materialIconId>k__BackingField`

- `Int32 <materialCnt>k__BackingField`

- `Boolean <isShowCnt>k__BackingField`

- `Boolean <isShowBg>k__BackingField`

- `Int32 <sortId>k__BackingField`


## Properties

- `String materialId`

- `String materialIconId`

- `Int32 materialCnt`

- `Boolean isShowCnt`

- `Boolean isShowBg`

- `Int32 sortId`


## Methods

- `String get_materialId()`

- `Void set_materialId(String)`

- `String get_materialIconId()`

- `Void set_materialIconId(String)`

- `Int32 get_materialCnt()`

- `Void set_materialCnt(Int32)`

- `Boolean get_isShowCnt()`

- `Void set_isShowCnt(Boolean)`

- `Boolean get_isShowBg()`

- `Void set_isShowBg(Boolean)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Void SetData(InputParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMaterialModel : IHotfixable
{
	private String <materialId>k__BackingField; // 0x10
	private String <materialIconId>k__BackingField; // 0x18
	private Int32 <materialCnt>k__BackingField; // 0x20
	private Boolean <isShowCnt>k__BackingField; // 0x24
	private Boolean <isShowBg>k__BackingField; // 0x25
	private Int32 <sortId>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_materialId; // 0x0
	private static DelegateBridge __Hotfix0_set_materialId; // 0x8
	private static DelegateBridge __Hotfix0_get_materialIconId; // 0x10
	private static DelegateBridge __Hotfix0_set_materialIconId; // 0x18
	private static DelegateBridge __Hotfix0_get_materialCnt; // 0x20
	private static DelegateBridge __Hotfix0_set_materialCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_isShowCnt; // 0x30
	private static DelegateBridge __Hotfix0_set_isShowCnt; // 0x38
	private static DelegateBridge __Hotfix0_get_isShowBg; // 0x40
	private static DelegateBridge __Hotfix0_set_isShowBg; // 0x48
	private static DelegateBridge __Hotfix0_get_sortId; // 0x50
	private static DelegateBridge __Hotfix0_set_sortId; // 0x58
	private static DelegateBridge __Hotfix0_SetData; // 0x60
	private static DelegateBridge __Hotfix0_Compare; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String materialId { get; set; }
	public String materialIconId { get; set; }
	public Int32 materialCnt { get; set; }
	public Boolean isShowCnt { get; set; }
	public Boolean isShowBg { get; set; }
	public Int32 sortId { get; set; }

	// RVA: 0x2dbfbac VA: 0x75953d7bac
	public String get_materialId() { }
	// RVA: 0x2dbfc14 VA: 0x75953d7c14
	private Void set_materialId(String value) { }
	// RVA: 0x2dbf940 VA: 0x75953d7940
	public String get_materialIconId() { }
	// RVA: 0x2dbfc98 VA: 0x75953d7c98
	private Void set_materialIconId(String value) { }
	// RVA: 0x2dbfac0 VA: 0x75953d7ac0
	public Int32 get_materialCnt() { }
	// RVA: 0x2dbfd1c VA: 0x75953d7d1c
	public Void set_materialCnt(Int32 value) { }
	// RVA: 0x2dbfa58 VA: 0x75953d7a58
	public Boolean get_isShowCnt() { }
	// RVA: 0x2dbfd98 VA: 0x75953d7d98
	private Void set_isShowCnt(Boolean value) { }
	// RVA: 0x2dbf8d8 VA: 0x75953d78d8
	public Boolean get_isShowBg() { }
	// RVA: 0x2dbfe18 VA: 0x75953d7e18
	private Void set_isShowBg(Boolean value) { }
	// RVA: 0x2dbfe98 VA: 0x75953d7e98
	public Int32 get_sortId() { }
	// RVA: 0x2dbff00 VA: 0x75953d7f00
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2dbf814 VA: 0x75953d7814
	public Void SetData(InputParam inputParam) { }
	// RVA: 0x2dbff7c VA: 0x75953d7f7c
	public static Int32 Compare(CarvingMaterialModel x, CarvingMaterialModel y) { }
	// RVA: 0x2dbf79c VA: 0x75953d779c
	public Void .ctor() { }
}
```