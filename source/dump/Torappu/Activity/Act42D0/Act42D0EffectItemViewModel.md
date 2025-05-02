# Act42D0EffectItemViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String m_actId`

- `String m_effectId`

- `Int32 m_groupSortId`

- `Int32 m_row`

- `Int32 m_col`

- `String m_effectName`

- `String m_effectIcon`

- `Int32 m_cost`

- `String m_effectDesc`

- `PackedRuneData m_runeData`

- `Boolean isSelected`


## Properties

- `String actId`

- `String effectId`

- `Int32 groupSortId`

- `Int32 row`

- `Int32 col`

- `String effectName`

- `String effectIcon`

- `Int32 cost`

- `String effectDesc`

- `PackedRuneData runeData`


## Methods

- `String get_actId()`

- `String get_effectId()`

- `Int32 get_groupSortId()`

- `Int32 get_row()`

- `Int32 get_col()`

- `String get_effectName()`

- `String get_effectIcon()`

- `Int32 get_cost()`

- `String get_effectDesc()`

- `PackedRuneData get_runeData()`

- `Void LoadData(String, Act42D0EffectInfoData, Int32)`

- `Int32 CompareTo(Act42D0EffectItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectItemViewModel : IHotfixable, IComparable`1
{
	private String m_actId; // 0x10
	private String m_effectId; // 0x18
	private Int32 m_groupSortId; // 0x20
	private Int32 m_row; // 0x24
	private Int32 m_col; // 0x28
	private String m_effectName; // 0x30
	private String m_effectIcon; // 0x38
	private Int32 m_cost; // 0x40
	private String m_effectDesc; // 0x48
	private PackedRuneData m_runeData; // 0x50
	public Boolean isSelected; // 0x58
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_effectId; // 0x8
	private static DelegateBridge __Hotfix0_get_groupSortId; // 0x10
	private static DelegateBridge __Hotfix0_get_row; // 0x18
	private static DelegateBridge __Hotfix0_get_col; // 0x20
	private static DelegateBridge __Hotfix0_get_effectName; // 0x28
	private static DelegateBridge __Hotfix0_get_effectIcon; // 0x30
	private static DelegateBridge __Hotfix0_get_cost; // 0x38
	private static DelegateBridge __Hotfix0_get_effectDesc; // 0x40
	private static DelegateBridge __Hotfix0_get_runeData; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_CompareTo; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String actId { get; }
	public String effectId { get; }
	public Int32 groupSortId { get; }
	public Int32 row { get; }
	public Int32 col { get; }
	public String effectName { get; }
	public String effectIcon { get; }
	public Int32 cost { get; }
	public String effectDesc { get; }
	public PackedRuneData runeData { get; }

	// RVA: 0x3211f0c VA: 0x7595829f0c
	public String get_actId() { }
	// RVA: 0x3211f74 VA: 0x7595829f74
	public String get_effectId() { }
	// RVA: 0x3211fdc VA: 0x7595829fdc
	public Int32 get_groupSortId() { }
	// RVA: 0x3212044 VA: 0x759582a044
	public Int32 get_row() { }
	// RVA: 0x32120ac VA: 0x759582a0ac
	public Int32 get_col() { }
	// RVA: 0x3212114 VA: 0x759582a114
	public String get_effectName() { }
	// RVA: 0x321217c VA: 0x759582a17c
	public String get_effectIcon() { }
	// RVA: 0x32121e4 VA: 0x759582a1e4
	public Int32 get_cost() { }
	// RVA: 0x321224c VA: 0x759582a24c
	public String get_effectDesc() { }
	// RVA: 0x32122b4 VA: 0x759582a2b4
	public PackedRuneData get_runeData() { }
	// RVA: 0x321231c VA: 0x759582a31c
	public Void LoadData(String actId, Act42D0EffectInfoData effectInfoData, Int32 groupSortId) { }
	// RVA: 0x3212438 VA: 0x759582a438
	public Int32 CompareTo(Act42D0EffectItemViewModel other) { }
	// RVA: 0x32124fc VA: 0x759582a4fc
	public Void .ctor() { }
}
```