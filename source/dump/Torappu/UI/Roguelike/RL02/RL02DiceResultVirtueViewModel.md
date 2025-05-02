# RL02DiceResultVirtueViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Sprite <virtueIcon>k__BackingField`

- `String <desc>k__BackingField`

- `String <tips>k__BackingField`


## Properties

- `Sprite virtueIcon`

- `String desc`

- `String tips`


## Methods

- `Sprite get_virtueIcon()`

- `Void set_virtueIcon(Sprite)`

- `String get_desc()`

- `Void set_desc(String)`

- `String get_tips()`

- `Void set_tips(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02DiceResultVirtueViewModel : RoguelikeDiceResultViewModel
{
	private Sprite <virtueIcon>k__BackingField; // 0x10
	private String <desc>k__BackingField; // 0x18
	private String <tips>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_virtueIcon; // 0x0
	private static DelegateBridge __Hotfix0_set_virtueIcon; // 0x8
	private static DelegateBridge __Hotfix0_get_desc; // 0x10
	private static DelegateBridge __Hotfix0_set_desc; // 0x18
	private static DelegateBridge __Hotfix0_get_tips; // 0x20
	private static DelegateBridge __Hotfix0_set_tips; // 0x28
	private static DelegateBridge __Hotfix0_LoadFromPlayerData; // 0x30
	private static DelegateBridge __Hotfix0_get_viewType; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Sprite virtueIcon { get; set; }
	public String desc { get; set; }
	public String tips { get; set; }
	public override Type viewType { get; }

	// RVA: 0x2b5fc74 VA: 0x7595177c74
	public Sprite get_virtueIcon() { }
	// RVA: 0x2b5fcdc VA: 0x7595177cdc
	private Void set_virtueIcon(Sprite value) { }
	// RVA: 0x2b5fd60 VA: 0x7595177d60
	public String get_desc() { }
	// RVA: 0x2b5fdc8 VA: 0x7595177dc8
	private Void set_desc(String value) { }
	// RVA: 0x2b5fe4c VA: 0x7595177e4c
	public String get_tips() { }
	// RVA: 0x2b5feb4 VA: 0x7595177eb4
	private Void set_tips(String value) { }
	// RVA: 0x2b5ff38 VA: 0x7595177f38
	public override Void LoadFromPlayerData(String topicId, Result result, RoguelikeDiceRuleData data) { }
	// RVA: 0x2b60140 VA: 0x7595178140
	public override Type get_viewType() { }
	// RVA: 0x2b601e8 VA: 0x75951781e8
	public Void .ctor() { }
}
```