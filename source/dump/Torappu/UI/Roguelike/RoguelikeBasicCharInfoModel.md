# RoguelikeBasicCharInfoModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Int32 mainSkillLvl`

- `Int32 defaultSkillIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeBasicCharInfoModel : BasicCharInfoModel, IHotfixable
{
	public Int32 mainSkillLvl; // 0xa0
	public Int32 defaultSkillIndex; // 0xa4
	public PlayerCharSkill[] skills; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x2aef074 VA: 0x7595107074
	public Void .ctor(PlayerCharacter playerChar, CharacterData charData) { }
}
```