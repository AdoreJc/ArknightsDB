# RL04ModeViewExtModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `String <relicDesc>k__BackingField`

- `String <buffDesc>k__BackingField`


## Properties

- `String relicDesc`

- `String buffDesc`


## Methods

- `String get_relicDesc()`

- `Void set_relicDesc(String)`

- `String get_buffDesc()`

- `Void set_buffDesc(String)`

- `Void _LoadExtDifficultyList(RoguelikeTopicModeViewModel)`

- `Void _LoadBuffs()`

- `RL04DifficultyExt _GetExtDiffData(RoguelikeTopicMode, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04ModeViewExtModel : RoguelikeTopicModeViewModelExtension
{
	public List`1 difficultyList; // 0x18
	private String <relicDesc>k__BackingField; // 0x20
	private String <buffDesc>k__BackingField; // 0x28
	public List`1 buffList; // 0x30
	private static DelegateBridge __Hotfix0_get_relicDesc; // 0x0
	private static DelegateBridge __Hotfix0_set_relicDesc; // 0x8
	private static DelegateBridge __Hotfix0_get_buffDesc; // 0x10
	private static DelegateBridge __Hotfix0_set_buffDesc; // 0x18
	private static DelegateBridge __Hotfix0_Load; // 0x20
	private static DelegateBridge __Hotfix0__LoadExtDifficultyList; // 0x28
	private static DelegateBridge __Hotfix0__LoadBuffs; // 0x30
	private static DelegateBridge __Hotfix0__GetExtDiffData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String relicDesc { get; set; }
	public String buffDesc { get; set; }

	// RVA: 0x26eaa3c VA: 0x7594d02a3c
	public String get_relicDesc() { }
	// RVA: 0x26ee640 VA: 0x7594d06640
	private Void set_relicDesc(String value) { }
	// RVA: 0x26eaaa4 VA: 0x7594d02aa4
	public String get_buffDesc() { }
	// RVA: 0x26ee6c4 VA: 0x7594d066c4
	private Void set_buffDesc(String value) { }
	// RVA: 0x26ee748 VA: 0x7594d06748
	public override Void Load(RoguelikeTopicModeViewModel mainModel) { }
	// RVA: 0x26ee860 VA: 0x7594d06860
	private Void _LoadExtDifficultyList(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26eead4 VA: 0x7594d06ad4
	private Void _LoadBuffs() { }
	// RVA: 0x26ef0ec VA: 0x7594d070ec
	private RL04DifficultyExt _GetExtDiffData(RoguelikeTopicMode modeDifficulty, Int32 grade) { }
	// RVA: 0x26ef2e4 VA: 0x7594d072e4
	public Void .ctor() { }
}
```