# Act1VAutoChessItemChessDetailItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <itemId>k__BackingField`

- `String <trapId>k__BackingField`

- `Boolean <hasGoldenItem>k__BackingField`

- `Int32 <level>k__BackingField`

- `String <name>k__BackingField`

- `String <skillDesc>k__BackingField`

- `String <goldenSkillDesc>k__BackingField`

- `String <storyDesc>k__BackingField`


## Properties

- `String itemId`

- `String trapId`

- `Boolean hasGoldenItem`

- `Int32 level`

- `String name`

- `String skillDesc`

- `String goldenSkillDesc`

- `String storyDesc`


## Methods

- `String get_itemId()`

- `Void set_itemId(String)`

- `String get_trapId()`

- `Void set_trapId(String)`

- `Boolean get_hasGoldenItem()`

- `Void set_hasGoldenItem(Boolean)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `String get_name()`

- `Void set_name(String)`

- `String get_skillDesc()`

- `Void set_skillDesc(String)`

- `String get_goldenSkillDesc()`

- `Void set_goldenSkillDesc(String)`

- `String get_storyDesc()`

- `Void set_storyDesc(String)`

- `Void LoadData(ActivityAutoChessVerify1Data, String)`

- `String _GetChessSkillDesc(ActivityAutoChessVerify1Data, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessItemChessDetailItemViewModel : IHotfixable
{
	private String <itemId>k__BackingField; // 0x10
	private String <trapId>k__BackingField; // 0x18
	private Boolean <hasGoldenItem>k__BackingField; // 0x20
	private Int32 <level>k__BackingField; // 0x24
	private String <name>k__BackingField; // 0x28
	private String <skillDesc>k__BackingField; // 0x30
	private String <goldenSkillDesc>k__BackingField; // 0x38
	private String <storyDesc>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_itemId; // 0x0
	private static DelegateBridge __Hotfix0_set_itemId; // 0x8
	private static DelegateBridge __Hotfix0_get_trapId; // 0x10
	private static DelegateBridge __Hotfix0_set_trapId; // 0x18
	private static DelegateBridge __Hotfix0_get_hasGoldenItem; // 0x20
	private static DelegateBridge __Hotfix0_set_hasGoldenItem; // 0x28
	private static DelegateBridge __Hotfix0_get_level; // 0x30
	private static DelegateBridge __Hotfix0_set_level; // 0x38
	private static DelegateBridge __Hotfix0_get_name; // 0x40
	private static DelegateBridge __Hotfix0_set_name; // 0x48
	private static DelegateBridge __Hotfix0_get_skillDesc; // 0x50
	private static DelegateBridge __Hotfix0_set_skillDesc; // 0x58
	private static DelegateBridge __Hotfix0_get_goldenSkillDesc; // 0x60
	private static DelegateBridge __Hotfix0_set_goldenSkillDesc; // 0x68
	private static DelegateBridge __Hotfix0_get_storyDesc; // 0x70
	private static DelegateBridge __Hotfix0_set_storyDesc; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge __Hotfix0__GetChessSkillDesc; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public String itemId { get; set; }
	public String trapId { get; set; }
	public Boolean hasGoldenItem { get; set; }
	public Int32 level { get; set; }
	public String name { get; set; }
	public String skillDesc { get; set; }
	public String goldenSkillDesc { get; set; }
	public String storyDesc { get; set; }

	// RVA: 0x335a6a4 VA: 0x75959726a4
	public String get_itemId() { }
	// RVA: 0x335a70c VA: 0x759597270c
	private Void set_itemId(String value) { }
	// RVA: 0x335a790 VA: 0x7595972790
	public String get_trapId() { }
	// RVA: 0x335a7f8 VA: 0x75959727f8
	private Void set_trapId(String value) { }
	// RVA: 0x335a87c VA: 0x759597287c
	public Boolean get_hasGoldenItem() { }
	// RVA: 0x335a8e4 VA: 0x75959728e4
	private Void set_hasGoldenItem(Boolean value) { }
	// RVA: 0x335a964 VA: 0x7595972964
	public Int32 get_level() { }
	// RVA: 0x335a9cc VA: 0x75959729cc
	private Void set_level(Int32 value) { }
	// RVA: 0x335aa48 VA: 0x7595972a48
	public String get_name() { }
	// RVA: 0x335aab0 VA: 0x7595972ab0
	private Void set_name(String value) { }
	// RVA: 0x335ab34 VA: 0x7595972b34
	public String get_skillDesc() { }
	// RVA: 0x335ab9c VA: 0x7595972b9c
	private Void set_skillDesc(String value) { }
	// RVA: 0x335ac20 VA: 0x7595972c20
	public String get_goldenSkillDesc() { }
	// RVA: 0x335ac88 VA: 0x7595972c88
	private Void set_goldenSkillDesc(String value) { }
	// RVA: 0x335ad0c VA: 0x7595972d0c
	public String get_storyDesc() { }
	// RVA: 0x335ad74 VA: 0x7595972d74
	private Void set_storyDesc(String value) { }
	// RVA: 0x335adf8 VA: 0x7595972df8
	public Void LoadData(ActivityAutoChessVerify1Data actData, String itemId) { }
	// RVA: 0x335b0e8 VA: 0x75959730e8
	private String _GetChessSkillDesc(ActivityAutoChessVerify1Data actData, String chessId) { }
	// RVA: 0x335b320 VA: 0x7595973320
	public Void .ctor() { }
}
```