# Act1VAutoChessMultiCharSkillEquipEditItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessShopQuickEditType <quickEditType>k__BackingField`

- `String <selectedSkillId>k__BackingField`

- `String <selectedEquipId>k__BackingField`

- `Act1VAutoChessShopCharChessCardViewModel m_cardViewModel`

- `String m_selectedEquipId`


## Properties

- `String chessId`

- `Int32 chessLv`

- `Act1VAutoChessShopQuickEditType quickEditType`

- `String selectedSkillId`

- `String selectedEquipId`

- `Int32 selectedEquipIndex`


## Methods

- `String get_chessId()`

- `Int32 get_chessLv()`

- `Act1VAutoChessShopQuickEditType get_quickEditType()`

- `Void set_quickEditType(Act1VAutoChessShopQuickEditType)`

- `String get_selectedSkillId()`

- `Void set_selectedSkillId(String)`

- `String get_selectedEquipId()`

- `Void set_selectedEquipId(String)`

- `Int32 get_selectedEquipIndex()`

- `Void LoadData(Act1VAutoChessShopCharChessCardViewModel)`

- `Void RefreshEditType(Act1VAutoChessShopQuickEditType)`

- `Void UpdateSelectSkill(String)`

- `Void UpdateSelectEquip(String)`

- `Void _LoadSkill(Act1VAutoChessShopCharChessCardViewModel)`

- `SkillItemViewModel _CreateSkill(CharacterData, Act1VAutoChessCharChessStatusData, Int32, Int32, Int32)`

- `Void _LoadEquip(Act1VAutoChessShopCharChessCardViewModel)`

- `Int32 _GetSelectEquipIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessMultiCharSkillEquipEditItemViewModel : IHotfixable
{
	public ListDict`2 skills; // 0x10
	public ListDict`2 equips; // 0x18
	private Act1VAutoChessShopQuickEditType <quickEditType>k__BackingField; // 0x20
	private String <selectedSkillId>k__BackingField; // 0x28
	private String <selectedEquipId>k__BackingField; // 0x30
	private Act1VAutoChessShopCharChessCardViewModel m_cardViewModel; // 0x38
	private String m_selectedEquipId; // 0x40
	private static DelegateBridge __Hotfix0_get_chessId; // 0x0
	private static DelegateBridge __Hotfix0_get_chessLv; // 0x8
	private static DelegateBridge __Hotfix0_get_quickEditType; // 0x10
	private static DelegateBridge __Hotfix0_set_quickEditType; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedSkillId; // 0x20
	private static DelegateBridge __Hotfix0_set_selectedSkillId; // 0x28
	private static DelegateBridge __Hotfix0_get_selectedEquipId; // 0x30
	private static DelegateBridge __Hotfix0_set_selectedEquipId; // 0x38
	private static DelegateBridge __Hotfix0_get_selectedEquipIndex; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_RefreshEditType; // 0x50
	private static DelegateBridge __Hotfix0_UpdateSelectSkill; // 0x58
	private static DelegateBridge __Hotfix0_UpdateSelectEquip; // 0x60
	private static DelegateBridge __Hotfix0__LoadSkill; // 0x68
	private static DelegateBridge __Hotfix0__CreateSkill; // 0x70
	private static DelegateBridge __Hotfix0__LoadEquip; // 0x78
	private static DelegateBridge __Hotfix0__GetSelectEquipIndex; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String chessId { get; }
	public Int32 chessLv { get; }
	public Act1VAutoChessShopQuickEditType quickEditType { get; set; }
	public String selectedSkillId { get; set; }
	public String selectedEquipId { get; set; }
	public Int32 selectedEquipIndex { get; }

	// RVA: 0x33326f4 VA: 0x759594a6f4
	public String get_chessId() { }
	// RVA: 0x3332790 VA: 0x759594a790
	public Int32 get_chessLv() { }
	// RVA: 0x3332810 VA: 0x759594a810
	public Act1VAutoChessShopQuickEditType get_quickEditType() { }
	// RVA: 0x3332878 VA: 0x759594a878
	private Void set_quickEditType(Act1VAutoChessShopQuickEditType value) { }
	// RVA: 0x33328f4 VA: 0x759594a8f4
	public String get_selectedSkillId() { }
	// RVA: 0x333295c VA: 0x759594a95c
	private Void set_selectedSkillId(String value) { }
	// RVA: 0x33329e0 VA: 0x759594a9e0
	public String get_selectedEquipId() { }
	// RVA: 0x3332a48 VA: 0x759594aa48
	private Void set_selectedEquipId(String value) { }
	// RVA: 0x3332acc VA: 0x759594aacc
	public Int32 get_selectedEquipIndex() { }
	// RVA: 0x3332c4c VA: 0x759594ac4c
	public Void LoadData(Act1VAutoChessShopCharChessCardViewModel cardViewModel) { }
	// RVA: 0x3333510 VA: 0x759594b510
	public Void RefreshEditType(Act1VAutoChessShopQuickEditType editType) { }
	// RVA: 0x3333378 VA: 0x759594b378
	public Void UpdateSelectSkill(String selectId) { }
	// RVA: 0x3333444 VA: 0x759594b444
	public Void UpdateSelectEquip(String selectId) { }
	// RVA: 0x3332d2c VA: 0x759594ad2c
	private Void _LoadSkill(Act1VAutoChessShopCharChessCardViewModel charCardViewModel) { }
	// RVA: 0x33335a4 VA: 0x759594b5a4
	private SkillItemViewModel _CreateSkill(CharacterData charData, Act1VAutoChessCharChessStatusData chessAttr, Int32 allLevel, Int32 specLevel, Int32 skillIndex) { }
	// RVA: 0x3332f80 VA: 0x759594af80
	private Void _LoadEquip(Act1VAutoChessShopCharChessCardViewModel charCardViewModel) { }
	// RVA: 0x3332b34 VA: 0x759594ab34
	private Int32 _GetSelectEquipIndex() { }
	// RVA: 0x3333790 VA: 0x759594b790
	public Void .ctor() { }
}
```