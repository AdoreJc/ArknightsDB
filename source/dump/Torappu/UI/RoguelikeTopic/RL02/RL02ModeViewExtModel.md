# RL02ModeViewExtModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


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

- `RL02DifficultyExt _GetExtDiffData(RoguelikeTopicMode, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02ModeViewExtModel : RoguelikeTopicModeViewModelExtension
{
	public List`1 difficultyList; // 0x18
	private String <relicDesc>k__BackingField; // 0x20
	private String <buffDesc>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_relicDesc; // 0x0
	private static DelegateBridge __Hotfix0_set_relicDesc; // 0x8
	private static DelegateBridge __Hotfix0_get_buffDesc; // 0x10
	private static DelegateBridge __Hotfix0_set_buffDesc; // 0x18
	private static DelegateBridge __Hotfix0_Load; // 0x20
	private static DelegateBridge __Hotfix0__LoadExtDifficultyList; // 0x28
	private static DelegateBridge __Hotfix0__GetExtDiffData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String relicDesc { get; set; }
	public String buffDesc { get; set; }

	// RVA: 0x26b8c2c VA: 0x7594cd0c2c
	public String get_relicDesc() { }
	// RVA: 0x26b8c94 VA: 0x7594cd0c94
	private Void set_relicDesc(String value) { }
	// RVA: 0x26b8d18 VA: 0x7594cd0d18
	public String get_buffDesc() { }
	// RVA: 0x26b8d80 VA: 0x7594cd0d80
	private Void set_buffDesc(String value) { }
	// RVA: 0x26b8e04 VA: 0x7594cd0e04
	public override Void Load(RoguelikeTopicModeViewModel mainModel) { }
	// RVA: 0x26b8f14 VA: 0x7594cd0f14
	private Void _LoadExtDifficultyList(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26b9188 VA: 0x7594cd1188
	private RL02DifficultyExt _GetExtDiffData(RoguelikeTopicMode modeDifficulty, Int32 grade) { }
	// RVA: 0x26b9380 VA: 0x7594cd1380
	public Void .ctor() { }
}
```