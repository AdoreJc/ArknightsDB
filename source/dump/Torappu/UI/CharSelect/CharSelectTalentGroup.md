# CharSelectTalentGroup

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `Transform _talentContainer`

- `GameObject _contentItemPrefab`


## Methods

- `Void RenderTalent(CharacterTalentViewModel[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectTalentGroup : MonoBehaviour, IHotfixable
{
	private Transform _talentContainer; // 0x18
	private GameObject _contentItemPrefab; // 0x20
	private CharacterTalentViewModel[] m_talentsCache; // 0x28
	private static DelegateBridge __Hotfix0_RenderTalent; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2cf78d0 VA: 0x759530f8d0
	public Void RenderTalent(CharacterTalentViewModel[] talents) { }
	// RVA: 0x2cf7ac8 VA: 0x759530fac8
	public Void .ctor() { }
}
```