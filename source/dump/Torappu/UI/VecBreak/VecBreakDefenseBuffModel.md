# VecBreakDefenseBuffModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Int64 m_unlockTs`

- `Status <status>k__BackingField`

- `String <actId>k__BackingField`

- `String <buffId>k__BackingField`

- `String <iconId>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `PackedRuneData <runeData>k__BackingField`


## Properties

- `Status status`

- `String actId`

- `String buffId`

- `String iconId`

- `Int32 sortId`

- `PackedRuneData runeData`


## Methods

- `Status get_status()`

- `Void set_status(Status)`

- `String get_actId()`

- `Void set_actId(String)`

- `String get_buffId()`

- `Void set_buffId(String)`

- `String get_iconId()`

- `Void set_iconId(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `PackedRuneData get_runeData()`

- `Void set_runeData(PackedRuneData)`

- `Void LoadData(String, ActVecBreakData, ActVecBreakDefenseStageData)`

- `Void UpdatePlayerData()`

- `Status _CalcBuffStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseBuffModel : IHotfixable
{
	private Int64 m_unlockTs; // 0x10
	private Status <status>k__BackingField; // 0x18
	private String <actId>k__BackingField; // 0x20
	private String <buffId>k__BackingField; // 0x28
	private String <iconId>k__BackingField; // 0x30
	private Int32 <sortId>k__BackingField; // 0x38
	private PackedRuneData <runeData>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_status; // 0x0
	private static DelegateBridge __Hotfix0_set_status; // 0x8
	private static DelegateBridge __Hotfix0_get_actId; // 0x10
	private static DelegateBridge __Hotfix0_set_actId; // 0x18
	private static DelegateBridge __Hotfix0_get_buffId; // 0x20
	private static DelegateBridge __Hotfix0_set_buffId; // 0x28
	private static DelegateBridge __Hotfix0_get_iconId; // 0x30
	private static DelegateBridge __Hotfix0_set_iconId; // 0x38
	private static DelegateBridge __Hotfix0_get_sortId; // 0x40
	private static DelegateBridge __Hotfix0_set_sortId; // 0x48
	private static DelegateBridge __Hotfix0_get_runeData; // 0x50
	private static DelegateBridge __Hotfix0_set_runeData; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x68
	private static DelegateBridge __Hotfix0__CalcBuffStatus; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Status status { get; set; }
	public String actId { get; set; }
	public String buffId { get; set; }
	public String iconId { get; set; }
	public Int32 sortId { get; set; }
	public PackedRuneData runeData { get; set; }

	// RVA: 0x22c5638 VA: 0x75948dd638
	public Status get_status() { }
	// RVA: 0x22cf19c VA: 0x75948e719c
	private Void set_status(Status value) { }
	// RVA: 0x22c56a0 VA: 0x75948dd6a0
	public String get_actId() { }
	// RVA: 0x22cf218 VA: 0x75948e7218
	private Void set_actId(String value) { }
	// RVA: 0x22cf29c VA: 0x75948e729c
	public String get_buffId() { }
	// RVA: 0x22cf304 VA: 0x75948e7304
	private Void set_buffId(String value) { }
	// RVA: 0x22c5708 VA: 0x75948dd708
	public String get_iconId() { }
	// RVA: 0x22cf388 VA: 0x75948e7388
	private Void set_iconId(String value) { }
	// RVA: 0x22cf40c VA: 0x75948e740c
	public Int32 get_sortId() { }
	// RVA: 0x22cf474 VA: 0x75948e7474
	private Void set_sortId(Int32 value) { }
	// RVA: 0x22cf4f0 VA: 0x75948e74f0
	public PackedRuneData get_runeData() { }
	// RVA: 0x22cf558 VA: 0x75948e7558
	private Void set_runeData(PackedRuneData value) { }
	// RVA: 0x22cf5dc VA: 0x75948e75dc
	public Void LoadData(String actId, ActVecBreakData actData, ActVecBreakDefenseStageData defenseData) { }
	// RVA: 0x22cf700 VA: 0x75948e7700
	public Void UpdatePlayerData() { }
	// RVA: 0x22cf774 VA: 0x75948e7774
	private Status _CalcBuffStatus() { }
	// RVA: 0x22cf8a4 VA: 0x75948e78a4
	public Void .ctor() { }
}
```