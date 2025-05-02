# RL02DiceResultMutationViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Sprite <mutationIcon>k__BackingField`

- `String <desc>k__BackingField`

- `String <tips>k__BackingField`


## Properties

- `Sprite mutationIcon`

- `String desc`

- `String tips`


## Methods

- `Sprite get_mutationIcon()`

- `Void set_mutationIcon(Sprite)`

- `String get_desc()`

- `Void set_desc(String)`

- `String get_tips()`

- `Void set_tips(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02DiceResultMutationViewModel : RoguelikeDiceResultViewModel
{
	private Sprite <mutationIcon>k__BackingField; // 0x10
	private String <desc>k__BackingField; // 0x18
	private String <tips>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_mutationIcon; // 0x0
	private static DelegateBridge __Hotfix0_set_mutationIcon; // 0x8
	private static DelegateBridge __Hotfix0_get_desc; // 0x10
	private static DelegateBridge __Hotfix0_set_desc; // 0x18
	private static DelegateBridge __Hotfix0_get_tips; // 0x20
	private static DelegateBridge __Hotfix0_set_tips; // 0x28
	private static DelegateBridge __Hotfix0_get_viewType; // 0x30
	private static DelegateBridge __Hotfix0_LoadFromPlayerData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Sprite mutationIcon { get; set; }
	public String desc { get; set; }
	public String tips { get; set; }
	public override Type viewType { get; }

	// RVA: 0x2b5f174 VA: 0x7595177174
	public Sprite get_mutationIcon() { }
	// RVA: 0x2b5f1dc VA: 0x75951771dc
	private Void set_mutationIcon(Sprite value) { }
	// RVA: 0x2b5f260 VA: 0x7595177260
	public String get_desc() { }
	// RVA: 0x2b5f2c8 VA: 0x75951772c8
	private Void set_desc(String value) { }
	// RVA: 0x2b5f34c VA: 0x759517734c
	public String get_tips() { }
	// RVA: 0x2b5f3b4 VA: 0x75951773b4
	private Void set_tips(String value) { }
	// RVA: 0x2b5f438 VA: 0x7595177438
	public override Type get_viewType() { }
	// RVA: 0x2b5f4e0 VA: 0x75951774e0
	public override Void LoadFromPlayerData(String topicId, Result result, RoguelikeDiceRuleData data) { }
	// RVA: 0x2b5f980 VA: 0x7595177980
	public Void .ctor() { }
}
```