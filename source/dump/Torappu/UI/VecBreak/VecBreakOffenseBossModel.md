# VecBreakOffenseBossModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Boolean <isEmpty>k__BackingField`

- `String <enemyId>k__BackingField`

- `String <name>k__BackingField`

- `String <desc>k__BackingField`

- `Int32 <level>k__BackingField`

- `String <iconId>k__BackingField`


## Properties

- `Boolean isEmpty`

- `String enemyId`

- `String name`

- `String desc`

- `Int32 level`

- `String iconId`

- `Boolean showHardBg`

- `Boolean showHardMask`


## Methods

- `Boolean get_isEmpty()`

- `Void set_isEmpty(Boolean)`

- `String get_enemyId()`

- `Void set_enemyId(String)`

- `String get_name()`

- `Void set_name(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `String get_iconId()`

- `Void set_iconId(String)`

- `Boolean get_showHardBg()`

- `Boolean get_showHardMask()`

- `Void LoadData(ActVecBreakOffenseBossData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseBossModel : IHotfixable
{
	private const Int32 HARD_BG_THRESHOLD; // 0x0
	private const Int32 HARD_MASK_THRESHOLD; // 0x0
	private Boolean <isEmpty>k__BackingField; // 0x10
	private String <enemyId>k__BackingField; // 0x18
	private String <name>k__BackingField; // 0x20
	private String <desc>k__BackingField; // 0x28
	private Int32 <level>k__BackingField; // 0x30
	private String <iconId>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x0
	private static DelegateBridge __Hotfix0_set_isEmpty; // 0x8
	private static DelegateBridge __Hotfix0_get_enemyId; // 0x10
	private static DelegateBridge __Hotfix0_set_enemyId; // 0x18
	private static DelegateBridge __Hotfix0_get_name; // 0x20
	private static DelegateBridge __Hotfix0_set_name; // 0x28
	private static DelegateBridge __Hotfix0_get_desc; // 0x30
	private static DelegateBridge __Hotfix0_set_desc; // 0x38
	private static DelegateBridge __Hotfix0_get_level; // 0x40
	private static DelegateBridge __Hotfix0_set_level; // 0x48
	private static DelegateBridge __Hotfix0_get_iconId; // 0x50
	private static DelegateBridge __Hotfix0_set_iconId; // 0x58
	private static DelegateBridge __Hotfix0_get_showHardBg; // 0x60
	private static DelegateBridge __Hotfix0_get_showHardMask; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Boolean isEmpty { get; set; }
	public String enemyId { get; set; }
	public String name { get; set; }
	public String desc { get; set; }
	public Int32 level { get; set; }
	public String iconId { get; set; }
	public Boolean showHardBg { get; }
	public Boolean showHardMask { get; }

	// RVA: 0x22cf914 VA: 0x75948e7914
	public Boolean get_isEmpty() { }
	// RVA: 0x22cf97c VA: 0x75948e797c
	private Void set_isEmpty(Boolean value) { }
	// RVA: 0x22cf9fc VA: 0x75948e79fc
	public String get_enemyId() { }
	// RVA: 0x22cfa64 VA: 0x75948e7a64
	private Void set_enemyId(String value) { }
	// RVA: 0x22cfae8 VA: 0x75948e7ae8
	public String get_name() { }
	// RVA: 0x22cfb50 VA: 0x75948e7b50
	private Void set_name(String value) { }
	// RVA: 0x22cfbd4 VA: 0x75948e7bd4
	public String get_desc() { }
	// RVA: 0x22cfc3c VA: 0x75948e7c3c
	private Void set_desc(String value) { }
	// RVA: 0x22cfcc0 VA: 0x75948e7cc0
	public Int32 get_level() { }
	// RVA: 0x22cfd28 VA: 0x75948e7d28
	private Void set_level(Int32 value) { }
	// RVA: 0x22cfda4 VA: 0x75948e7da4
	public String get_iconId() { }
	// RVA: 0x22cfe0c VA: 0x75948e7e0c
	private Void set_iconId(String value) { }
	// RVA: 0x22cfe90 VA: 0x75948e7e90
	public Boolean get_showHardBg() { }
	// RVA: 0x22cff04 VA: 0x75948e7f04
	public Boolean get_showHardMask() { }
	// RVA: 0x22cff78 VA: 0x75948e7f78
	public Void LoadData(ActVecBreakOffenseBossData bossData) { }
	// RVA: 0x22d005c VA: 0x75948e805c
	public Void .ctor() { }
}
```