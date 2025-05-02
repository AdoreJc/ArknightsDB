# CrisisV2SettleRuneItemViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Boolean <isEmpty>k__BackingField`

- `Int32 <point>k__BackingField`

- `String <runeIconId>k__BackingField`

- `Int32 m_sortId`


## Properties

- `Boolean isEmpty`

- `Int32 point`

- `String runeIconId`


## Methods

- `Boolean get_isEmpty()`

- `Void set_isEmpty(Boolean)`

- `Int32 get_point()`

- `Void set_point(Int32)`

- `String get_runeIconId()`

- `Void set_runeIconId(String)`

- `Void LoadData(CrisisV2AchievementRuneViewModel)`

- `Void LoadData(String, CrisisV2MapDetailData, List`1)`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SettleRuneItemViewModel : IComparable, IHotfixable
{
	private Boolean <isEmpty>k__BackingField; // 0x10
	private Int32 <point>k__BackingField; // 0x14
	private String <runeIconId>k__BackingField; // 0x18
	private Int32 m_sortId; // 0x20
	public static readonly CrisisV2SettleRuneItemViewModel EMPTY; // 0x0
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x8
	private static DelegateBridge __Hotfix0_set_isEmpty; // 0x10
	private static DelegateBridge __Hotfix0_get_point; // 0x18
	private static DelegateBridge __Hotfix0_set_point; // 0x20
	private static DelegateBridge __Hotfix0_get_runeIconId; // 0x28
	private static DelegateBridge __Hotfix0_set_runeIconId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix1_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_CompareTo; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean isEmpty { get; set; }
	public Int32 point { get; set; }
	public String runeIconId { get; set; }

	// RVA: 0x2bd0a94 VA: 0x75951e8a94
	public Boolean get_isEmpty() { }
	// RVA: 0x2bd507c VA: 0x75951ed07c
	private Void set_isEmpty(Boolean value) { }
	// RVA: 0x2bd0b0c VA: 0x75951e8b0c
	public Int32 get_point() { }
	// RVA: 0x2bd510c VA: 0x75951ed10c
	private Void set_point(Int32 value) { }
	// RVA: 0x2bd0b84 VA: 0x75951e8b84
	public String get_runeIconId() { }
	// RVA: 0x2bd5198 VA: 0x75951ed198
	private Void set_runeIconId(String value) { }
	// RVA: 0x2bd522c VA: 0x75951ed22c
	public Void LoadData(CrisisV2AchievementRuneViewModel model) { }
	// RVA: 0x2bd52e8 VA: 0x75951ed2e8
	public Void LoadData(String runeId, CrisisV2MapDetailData stageDetailData, List`1 packedRuneList) { }
	// RVA: 0x2bd552c VA: 0x75951ed52c
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2bd5650 VA: 0x75951ed650
	public Void .ctor() { }
	// RVA: 0x2bd56d0 VA: 0x75951ed6d0
	private static Void .cctor() { }
}
```