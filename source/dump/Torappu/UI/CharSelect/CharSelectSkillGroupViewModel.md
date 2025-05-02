# CharSelectSkillGroupViewModel

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `String selectedSkillId`

- `Int32 skillAllLevel`

- `String charId`

- `Boolean isEnabled`

- `String disableText`


## Methods

- `CharSelectSkillItemViewModel AchieveSkillModelById(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectSkillGroupViewModel
{
	public String selectedSkillId; // 0x10
	public CharSelectSkillItemViewModel[] skills; // 0x18
	public Int32 skillAllLevel; // 0x20
	public String charId; // 0x28
	public Boolean isEnabled; // 0x30
	public String disableText; // 0x38


	// RVA: 0x2cf084c VA: 0x759530884c
	public CharSelectSkillItemViewModel AchieveSkillModelById(String skillId) { }
	// RVA: 0x2cf040c VA: 0x759530840c
	public Void .ctor() { }
}
```