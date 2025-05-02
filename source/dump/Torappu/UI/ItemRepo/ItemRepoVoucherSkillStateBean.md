# ItemRepoVoucherSkillStateBean

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoVoucherSkillViewProperty viewProperty`

- `Int32 charInstId`

- `UIItemViewModel voucherItemModel`

- `String <curCharId>k__BackingField`

- `String <curSkillId>k__BackingField`

- `Int32 <curSkillLevel>k__BackingField`


## Properties

- `String curCharId`

- `String curSkillId`

- `Int32 curSkillLevel`


## Methods

- `String get_curCharId()`

- `Void set_curCharId(String)`

- `String get_curSkillId()`

- `Void set_curSkillId(String)`

- `Int32 get_curSkillLevel()`

- `Void set_curSkillLevel(Int32)`

- `Void UpdateSelectedSkill(Int32)`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherSkillStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public ItemRepoVoucherSkillViewProperty viewProperty; // 0x18
	public Int32 charInstId; // 0x20
	public UIItemViewModel voucherItemModel; // 0x28
	private String <curCharId>k__BackingField; // 0x30
	private String <curSkillId>k__BackingField; // 0x38
	private Int32 <curSkillLevel>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_curCharId; // 0x0
	private static DelegateBridge __Hotfix0_set_curCharId; // 0x8
	private static DelegateBridge __Hotfix0_get_curSkillId; // 0x10
	private static DelegateBridge __Hotfix0_set_curSkillId; // 0x18
	private static DelegateBridge __Hotfix0_get_curSkillLevel; // 0x20
	private static DelegateBridge __Hotfix0_set_curSkillLevel; // 0x28
	private static DelegateBridge __Hotfix0_UpdateSelectedSkill; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String curCharId { get; set; }
	public String curSkillId { get; set; }
	public Int32 curSkillLevel { get; set; }

	// RVA: 0x2d27cbc VA: 0x759533fcbc
	public String get_curCharId() { }
	// RVA: 0x2d2e2b4 VA: 0x75953462b4
	private Void set_curCharId(String value) { }
	// RVA: 0x2d27d24 VA: 0x759533fd24
	public String get_curSkillId() { }
	// RVA: 0x2d2e338 VA: 0x7595346338
	private Void set_curSkillId(String value) { }
	// RVA: 0x2d27d8c VA: 0x759533fd8c
	public Int32 get_curSkillLevel() { }
	// RVA: 0x2d2e3bc VA: 0x75953463bc
	private Void set_curSkillLevel(Int32 value) { }
	// RVA: 0x2d281fc VA: 0x75953401fc
	public Void UpdateSelectedSkill(Int32 selectedIdx) { }
	// RVA: 0x2d27198 VA: 0x759533f198
	public Void LoadData() { }
	// RVA: 0x2d2e574 VA: 0x7595346574
	public Void .ctor() { }
}
```