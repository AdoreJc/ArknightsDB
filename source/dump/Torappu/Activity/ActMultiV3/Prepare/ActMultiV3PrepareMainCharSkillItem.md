# ActMultiV3PrepareMainCharSkillItem

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `GameObject _selectBgGo`

- `GameObject _normalPartGo`

- `GameObject _emptyPartGo`

- `GameObject _lockPartGo`

- `Image _imgSkill`

- `Text _textSkillLv`

- `Image _imgSpecializeLv`

- `CanvasGroup _canvasGroup`

- `Single _unselectAlpha`

- `Int32 m_cardId`

- `Boolean m_isSelect`

- `SkillItemViewModel m_skillModel`


## Methods

- `Void set_onSkillSelect(Action`2)`

- `Void Render(Int32, Boolean, SkillItemViewModel)`

- `Void OnSkillSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainCharSkillItem : MonoBehaviour, IHotfixable
{
	private GameObject _selectBgGo; // 0x18
	private GameObject _normalPartGo; // 0x20
	private GameObject _emptyPartGo; // 0x28
	private GameObject _lockPartGo; // 0x30
	private Image _imgSkill; // 0x38
	private Text _textSkillLv; // 0x40
	private Image _imgSpecializeLv; // 0x48
	private Sprite[] _skillLevelImages; // 0x50
	private CanvasGroup _canvasGroup; // 0x58
	private Single _unselectAlpha; // 0x60
	private Int32 m_cardId; // 0x64
	private Boolean m_isSelect; // 0x68
	private SkillItemViewModel m_skillModel; // 0x70
	private Action`2 <onSkillSelect>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnSkillSelect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`2 onSkillSelect { get; set; }

	// RVA: 0x315fb30 VA: 0x7595777b30
	private Action`2 get_onSkillSelect() { }
	// RVA: 0x315fb98 VA: 0x7595777b98
	public Void set_onSkillSelect(Action`2 value) { }
	// RVA: 0x315fc1c VA: 0x7595777c1c
	public Void Render(Int32 cardId, Boolean isSelect, SkillItemViewModel skillModel) { }
	// RVA: 0x315fe5c VA: 0x7595777e5c
	public Void OnSkillSelect() { }
	// RVA: 0x315ff10 VA: 0x7595777f10
	public Void .ctor() { }
}
```