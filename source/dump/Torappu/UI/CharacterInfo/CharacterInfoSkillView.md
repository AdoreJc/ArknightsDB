# CharacterInfoSkillView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _panelEnable`

- `GameObject _panelLocked`

- `GameObject _panelEmpty`

- `Image _imageSkillIcon`

- `Text _textCost`

- `Text _textInitCost`

- `GameObject _textCostObj`

- `GameObject _textInitCostObj`

- `Text _textName`

- `UISkillTagGroup _tagGroup`

- `UICommentedText _textDesc`

- `Text _textUnlockCond`

- `String m_skillIdCache`

- `SkillItemViewModel m_cachedViewModel`

- `Boolean isSkillLvUpGroupDownPos`


## Methods

- `Void RenderCommentedTextVisible(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEnable; // 0x18
	private GameObject _panelLocked; // 0x20
	private GameObject _panelEmpty; // 0x28
	private Image _imageSkillIcon; // 0x30
	private Text _textCost; // 0x38
	private Text _textInitCost; // 0x40
	private GameObject _textCostObj; // 0x48
	private GameObject _textInitCostObj; // 0x50
	private Text _textName; // 0x58
	private UISkillTagGroup _tagGroup; // 0x60
	private UICommentedText _textDesc; // 0x68
	private Text _textUnlockCond; // 0x70
	private String m_skillIdCache; // 0x78
	private SkillItemViewModel m_cachedViewModel; // 0x80
	public Boolean isSkillLvUpGroupDownPos; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RenderCommentedTextVisible; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d89710 VA: 0x75953a1710
	public virtual Void Render(SkillItemViewModel viewModel) { }
	// RVA: 0x2d89988 VA: 0x75953a1988
	public Void RenderCommentedTextVisible(Boolean isDownState) { }
	// RVA: 0x2d89a90 VA: 0x75953a1a90
	public Void .ctor() { }
}
```