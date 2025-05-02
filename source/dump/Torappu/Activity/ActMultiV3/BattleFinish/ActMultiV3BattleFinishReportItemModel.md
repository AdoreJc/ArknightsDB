# ActMultiV3BattleFinishReportItemModel

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `String <id>k__BackingField`

- `String <name>k__BackingField`

- `String <desc>k__BackingField`

- `Int32 <sortId>k__BackingField`


## Properties

- `String id`

- `String name`

- `String desc`

- `Int32 sortId`


## Methods

- `String get_id()`

- `Void set_id(String)`

- `String get_name()`

- `Void set_name(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Void LoadData(ActMultiV3ReportData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishReportItemModel : IHotfixable
{
	private String <id>k__BackingField; // 0x10
	private String <name>k__BackingField; // 0x18
	private String <desc>k__BackingField; // 0x20
	private Int32 <sortId>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_id; // 0x0
	private static DelegateBridge __Hotfix0_set_id; // 0x8
	private static DelegateBridge __Hotfix0_get_name; // 0x10
	private static DelegateBridge __Hotfix0_set_name; // 0x18
	private static DelegateBridge __Hotfix0_get_desc; // 0x20
	private static DelegateBridge __Hotfix0_set_desc; // 0x28
	private static DelegateBridge __Hotfix0_get_sortId; // 0x30
	private static DelegateBridge __Hotfix0_set_sortId; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String id { get; set; }
	public String name { get; set; }
	public String desc { get; set; }
	public Int32 sortId { get; set; }

	// RVA: 0x3181d50 VA: 0x7595799d50
	public String get_id() { }
	// RVA: 0x3183180 VA: 0x759579b180
	private Void set_id(String value) { }
	// RVA: 0x3181bc8 VA: 0x7595799bc8
	public String get_name() { }
	// RVA: 0x3183204 VA: 0x759579b204
	private Void set_name(String value) { }
	// RVA: 0x3181c30 VA: 0x7595799c30
	public String get_desc() { }
	// RVA: 0x3183288 VA: 0x759579b288
	private Void set_desc(String value) { }
	// RVA: 0x3183118 VA: 0x759579b118
	public Int32 get_sortId() { }
	// RVA: 0x318330c VA: 0x759579b30c
	private Void set_sortId(Int32 value) { }
	// RVA: 0x3182aec VA: 0x759579aaec
	public Void LoadData(ActMultiV3ReportData reportItemData) { }
	// RVA: 0x3182a7c VA: 0x759579aa7c
	public Void .ctor() { }
}
```