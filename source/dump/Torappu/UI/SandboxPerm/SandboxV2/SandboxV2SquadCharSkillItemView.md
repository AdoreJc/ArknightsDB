# SandboxV2SquadCharSkillItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _selectBgGo`

- `GameObject _iconSelectGo`

- `GameObject _normalPartGo`

- `GameObject _emptyPartGo`

- `GameObject _lockPartGo`

- `Image _imgSkill`

- `Text _textSkillLv`

- `Image _imgSpecializeLv`

- `CanvasGroup _canvasGroup`

- `Single _unselectAlpha`

- `Int32 m_instId`

- `Boolean m_isSelect`

- `SandboxV2CharSkillModel m_skillModel`


## Methods

- `Void set_onSkillSelect(Action`2)`

- `Void Render(Int32, SandboxV2CharSkillModel, Boolean)`

- `Void _HideAll()`

- `Void OnSkillSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadCharSkillItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectBgGo; // 0x18
	private GameObject _iconSelectGo; // 0x20
	private GameObject _normalPartGo; // 0x28
	private GameObject _emptyPartGo; // 0x30
	private GameObject _lockPartGo; // 0x38
	private Image _imgSkill; // 0x40
	private Text _textSkillLv; // 0x48
	private Image _imgSpecializeLv; // 0x50
	private Sprite[] _skillLevelImages; // 0x58
	private CanvasGroup _canvasGroup; // 0x60
	private Single _unselectAlpha; // 0x68
	private Int32 m_instId; // 0x6c
	private Boolean m_isSelect; // 0x70
	private SandboxV2CharSkillModel m_skillModel; // 0x78
	private Action`2 <onSkillSelect>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__HideAll; // 0x18
	private static DelegateBridge __Hotfix0_OnSkillSelect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`2 onSkillSelect { get; set; }

	// RVA: 0x26109a0 VA: 0x7594c289a0
	private Action`2 get_onSkillSelect() { }
	// RVA: 0x26106d8 VA: 0x7594c286d8
	public Void set_onSkillSelect(Action`2 value) { }
	// RVA: 0x261075c VA: 0x7594c2875c
	public Void Render(Int32 instId, SandboxV2CharSkillModel skillModel, Boolean isSelect) { }
	// RVA: 0x2610a08 VA: 0x7594c28a08
	private Void _HideAll() { }
	// RVA: 0x2610ab8 VA: 0x7594c28ab8
	public Void OnSkillSelect() { }
	// RVA: 0x2610b6c VA: 0x7594c28b6c
	public Void .ctor() { }
}
```