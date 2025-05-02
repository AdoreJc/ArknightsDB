# RoguelikeCharSelectTalentGroup

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _talentContainer`

- `GameObject _contentItemPrefab`


## Methods

- `Void RenderTalent(RoguelikeTalentViewModel[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectTalentGroup : MonoBehaviour, IHotfixable
{
	private Transform _talentContainer; // 0x18
	private GameObject _contentItemPrefab; // 0x20
	private RoguelikeTalentViewModel[] m_talentsCache; // 0x28
	private static DelegateBridge __Hotfix0_RenderTalent; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2aceff8 VA: 0x75950e6ff8
	public Void RenderTalent(RoguelikeTalentViewModel[] talents) { }
	// RVA: 0x2acf1ec VA: 0x75950e71ec
	public Void .ctor() { }
}
```