# RoguelikeCharSelectSkillGroupViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean ableToSelectSkill`

- `Boolean isSelfChar`

- `Boolean isUpGraded`

- `String selectedSkillId`

- `Int32 skillAllLevel`

- `String charId`

- `Boolean isEnabled`

- `String disableText`


## Methods

- `RoguelikeCharSelectSkillItemViewModel AchieveSkillModelById(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectSkillGroupViewModel : IHotfixable
{
	public Boolean ableToSelectSkill; // 0x10
	public Boolean isSelfChar; // 0x11
	public Boolean isUpGraded; // 0x12
	public String selectedSkillId; // 0x18
	public RoguelikeCharSelectSkillItemViewModel[] skills; // 0x20
	public Int32 skillAllLevel; // 0x28
	public String charId; // 0x30
	public Boolean isEnabled; // 0x38
	public String disableText; // 0x40
	private static DelegateBridge __Hotfix0_AchieveSkillModelById; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2ad1924 VA: 0x75950e9924
	public RoguelikeCharSelectSkillItemViewModel AchieveSkillModelById(String skillId) { }
	// RVA: 0x2acc848 VA: 0x75950e4848
	public Void .ctor() { }
}
```