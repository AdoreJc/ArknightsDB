# SandboxV2RacerInfoModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2.BattleFinish`


## Fields

- `Int32 m_position`

- `String <instId>k__BackingField`

- `Int32 <time>k__BackingField`

- `String <name>k__BackingField`

- `String <typeName>k__BackingField`

- `String <itemId>k__BackingField`


## Properties

- `String instId`

- `Int32 time`

- `String name`

- `String typeName`

- `String itemId`

- `Boolean isUnfinished`

- `String pos`


## Methods

- `String get_instId()`

- `Void set_instId(String)`

- `Int32 get_time()`

- `Void set_time(Int32)`

- `String get_name()`

- `Void set_name(String)`

- `String get_typeName()`

- `Void set_typeName(String)`

- `String get_itemId()`

- `Void set_itemId(String)`

- `Boolean get_isUnfinished()`

- `String get_pos()`

- `Void LoadData(Int32, String, RacerInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2.BattleFinish
public class SandboxV2RacerInfoModel : IHotfixable
{
	private Int32 m_position; // 0x10
	private String <instId>k__BackingField; // 0x18
	private Int32 <time>k__BackingField; // 0x20
	private String <name>k__BackingField; // 0x28
	private String <typeName>k__BackingField; // 0x30
	private String <itemId>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_instId; // 0x0
	private static DelegateBridge __Hotfix0_set_instId; // 0x8
	private static DelegateBridge __Hotfix0_get_time; // 0x10
	private static DelegateBridge __Hotfix0_set_time; // 0x18
	private static DelegateBridge __Hotfix0_get_name; // 0x20
	private static DelegateBridge __Hotfix0_set_name; // 0x28
	private static DelegateBridge __Hotfix0_get_typeName; // 0x30
	private static DelegateBridge __Hotfix0_set_typeName; // 0x38
	private static DelegateBridge __Hotfix0_get_itemId; // 0x40
	private static DelegateBridge __Hotfix0_set_itemId; // 0x48
	private static DelegateBridge __Hotfix0_get_isUnfinished; // 0x50
	private static DelegateBridge __Hotfix0_get_pos; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String instId { get; set; }
	public Int32 time { get; set; }
	public String name { get; set; }
	public String typeName { get; set; }
	public String itemId { get; set; }
	public Boolean isUnfinished { get; }
	public String pos { get; }

	// RVA: 0x262c1cc VA: 0x7594c441cc
	public String get_instId() { }
	// RVA: 0x262c234 VA: 0x7594c44234
	private Void set_instId(String value) { }
	// RVA: 0x2626640 VA: 0x7594c3e640
	public Int32 get_time() { }
	// RVA: 0x262c2b8 VA: 0x7594c442b8
	private Void set_time(Int32 value) { }
	// RVA: 0x2626030 VA: 0x7594c3e030
	public String get_name() { }
	// RVA: 0x262c334 VA: 0x7594c44334
	private Void set_name(String value) { }
	// RVA: 0x26265d8 VA: 0x7594c3e5d8
	public String get_typeName() { }
	// RVA: 0x262c3b8 VA: 0x7594c443b8
	private Void set_typeName(String value) { }
	// RVA: 0x2626098 VA: 0x7594c3e098
	public String get_itemId() { }
	// RVA: 0x262c43c VA: 0x7594c4443c
	private Void set_itemId(String value) { }
	// RVA: 0x2626100 VA: 0x7594c3e100
	public Boolean get_isUnfinished() { }
	// RVA: 0x26264ec VA: 0x7594c3e4ec
	public String get_pos() { }
	// RVA: 0x262c4c0 VA: 0x7594c444c0
	public Void LoadData(Int32 position, String topicId, RacerInfo racerInfo) { }
	// RVA: 0x262c684 VA: 0x7594c44684
	public Void .ctor() { }
}
```