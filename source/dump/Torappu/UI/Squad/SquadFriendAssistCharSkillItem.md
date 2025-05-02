# SquadFriendAssistCharSkillItem

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _panelEnable`

- `GameObject _panelLocked`

- `GameObject _panelEmpty`

- `GameObject _selectFrame`

- `Image _imageSkill`

- `Text _textCost`

- `Text _textInit`

- `GameObject _skillCost`

- `GameObject _skillInit`

- `Image _imgSpecIcon`

- `Text _textMainLv`

- `UIColorGraphic _colorGraphic`

- `Single _skillUnselectAlpha`

- `Image _mainLevelBg`

- `Color _unlimitLevelBgColor`

- `Color _limitLevelBgColor`

- `UIStateFinder m_stateFinder`

- `Int32 m_cachedIndex`


## Methods

- `Void Render(SkillItemViewModel, Boolean, Int32, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendAssistCharSkillItem : MonoBehaviour, IHotfixable
{
	private GameObject _panelEnable; // 0x18
	private GameObject _panelLocked; // 0x20
	private GameObject _panelEmpty; // 0x28
	private GameObject _selectFrame; // 0x30
	private Image _imageSkill; // 0x38
	private Text _textCost; // 0x40
	private Text _textInit; // 0x48
	private GameObject _skillCost; // 0x50
	private GameObject _skillInit; // 0x58
	private Image _imgSpecIcon; // 0x60
	private Text _textMainLv; // 0x68
	private UIColorGraphic _colorGraphic; // 0x70
	private Single _skillUnselectAlpha; // 0x78
	private Image _mainLevelBg; // 0x80
	private Color _unlimitLevelBgColor; // 0x88
	private Color _limitLevelBgColor; // 0x98
	private UIStateFinder m_stateFinder; // 0xa8
	private Int32 m_cachedIndex; // 0xb8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23c5b84 VA: 0x75949ddb84
	public Void Render(SkillItemViewModel skillModel, Boolean isSelected, Int32 skillIndex, Boolean isLimited) { }
	// RVA: 0x23c5e70 VA: 0x75949dde70
	public Void OnClick() { }
	// RVA: 0x23c5f60 VA: 0x75949ddf60
	public Void .ctor() { }
}
```