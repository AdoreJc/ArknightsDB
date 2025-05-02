# SkillGroupViewModel

**Namespace:** `Torappu.UI`


## Fields

- `String selectedSkillId`

- `Int32 skillAllLevel`

- `CharQuery charQuery`

- `Boolean allMaxFlag`


## Methods

- `Void LoadData(PlayerCharacter, CharacterData)`

- `SkillItemViewModel AchieveSkillModelById(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SkillGroupViewModel
{
	public String selectedSkillId; // 0x10
	public SkillItemViewModel[] skills; // 0x18
	public Int32 skillAllLevel; // 0x20
	public CharQuery charQuery; // 0x28
	public Boolean allMaxFlag; // 0x40


	// RVA: 0x2197ba4 VA: 0x75947afba4
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x2197fd4 VA: 0x75947affd4
	public SkillItemViewModel AchieveSkillModelById(String skillId) { }
	// RVA: 0x2198060 VA: 0x75947b0060
	public Void .ctor() { }
}
```