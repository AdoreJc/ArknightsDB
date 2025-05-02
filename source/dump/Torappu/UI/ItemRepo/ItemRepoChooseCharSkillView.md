# ItemRepoChooseCharSkillView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Image _imgSkill`

- `Image _imgSpecializeLv`

- `GameObject _skillIconFrame`

- `GameObject _skillIconCover`

- `GameObject _specializeCover`


## Methods

- `Void Render(PlayerCharSkill)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharSkillView : MonoBehaviour, IHotfixable
{
	private Image _imgSkill; // 0x18
	private Image _imgSpecializeLv; // 0x20
	private GameObject _skillIconFrame; // 0x28
	private GameObject _skillIconCover; // 0x30
	private GameObject _specializeCover; // 0x38
	private Sprite[] _specializeImages; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d33428 VA: 0x759534b428
	public Void Render(PlayerCharSkill skillInfo) { }
	// RVA: 0x2d335c8 VA: 0x759534b5c8
	public Void .ctor() { }
}
```