# RL03ModeViewExtModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `String <totemDesc>k__BackingField`

- `String <relicDesc>k__BackingField`

- `String <buffDesc>k__BackingField`


## Properties

- `String totemDesc`

- `String relicDesc`

- `String buffDesc`


## Methods

- `String get_totemDesc()`

- `Void set_totemDesc(String)`

- `String get_relicDesc()`

- `Void set_relicDesc(String)`

- `String get_buffDesc()`

- `Void set_buffDesc(String)`

- `Void _LoadExtDifficultyList(RoguelikeTopicModeViewModel)`

- `Void _LoadBuffs(RoguelikeTopicModeViewModel)`

- `RL03DifficultyExt _GetExtDiffData(RoguelikeTopicMode, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class RL03ModeViewExtModel : RoguelikeTopicModeViewModelExtension
{
	public List`1 difficultyList; // 0x18
	private String <totemDesc>k__BackingField; // 0x20
	private String <relicDesc>k__BackingField; // 0x28
	private String <buffDesc>k__BackingField; // 0x30
	public List`1 buffList; // 0x38
	private static DelegateBridge __Hotfix0_get_totemDesc; // 0x0
	private static DelegateBridge __Hotfix0_set_totemDesc; // 0x8
	private static DelegateBridge __Hotfix0_get_relicDesc; // 0x10
	private static DelegateBridge __Hotfix0_set_relicDesc; // 0x18
	private static DelegateBridge __Hotfix0_get_buffDesc; // 0x20
	private static DelegateBridge __Hotfix0_set_buffDesc; // 0x28
	private static DelegateBridge __Hotfix0_Load; // 0x30
	private static DelegateBridge __Hotfix0__LoadExtDifficultyList; // 0x38
	private static DelegateBridge __Hotfix0__LoadBuffs; // 0x40
	private static DelegateBridge __Hotfix0__GetExtDiffData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String totemDesc { get; set; }
	public String relicDesc { get; set; }
	public String buffDesc { get; set; }

	// RVA: 0x26a15e0 VA: 0x7594cb95e0
	public String get_totemDesc() { }
	// RVA: 0x26a53fc VA: 0x7594cbd3fc
	private Void set_totemDesc(String value) { }
	// RVA: 0x26a1648 VA: 0x7594cb9648
	public String get_relicDesc() { }
	// RVA: 0x26a5480 VA: 0x7594cbd480
	private Void set_relicDesc(String value) { }
	// RVA: 0x26a16b0 VA: 0x7594cb96b0
	public String get_buffDesc() { }
	// RVA: 0x26a5504 VA: 0x7594cbd504
	private Void set_buffDesc(String value) { }
	// RVA: 0x26a5588 VA: 0x7594cbd588
	public override Void Load(RoguelikeTopicModeViewModel mainModel) { }
	// RVA: 0x26a56d4 VA: 0x7594cbd6d4
	private Void _LoadExtDifficultyList(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26a5938 VA: 0x7594cbd938
	private Void _LoadBuffs(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26a5f60 VA: 0x7594cbdf60
	private RL03DifficultyExt _GetExtDiffData(RoguelikeTopicMode modeDifficulty, Int32 grade) { }
	// RVA: 0x26a6148 VA: 0x7594cbe148
	public Void .ctor() { }
}
```