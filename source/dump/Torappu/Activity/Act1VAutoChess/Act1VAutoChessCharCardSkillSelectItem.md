# Act1VAutoChessCharCardSkillSelectItem

**Namespace:** `Torappu.Activity.Act1VAutoChess`


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

- `String m_chessId`

- `Int32 m_chessLv`

- `SkillItemViewModel m_skillModel`


## Methods

- `Void set_onSkillSelect(Action`3)`

- `Void Render(String, Int32, Boolean, SkillItemViewModel)`

- `Void OnSkillSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessCharCardSkillSelectItem : MonoBehaviour, IHotfixable
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
	private String m_chessId; // 0x70
	private Int32 m_chessLv; // 0x78
	private SkillItemViewModel m_skillModel; // 0x80
	private Action`3 <onSkillSelect>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnSkillSelect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`3 onSkillSelect { get; set; }

	// RVA: 0x3322430 VA: 0x759593a430
	private Action`3 get_onSkillSelect() { }
	// RVA: 0x3322498 VA: 0x759593a498
	public Void set_onSkillSelect(Action`3 value) { }
	// RVA: 0x332251c VA: 0x759593a51c
	public Void Render(String chessId, Int32 chessLv, Boolean isSelect, SkillItemViewModel skillModel) { }
	// RVA: 0x3322780 VA: 0x759593a780
	public Void OnSkillSelect() { }
	// RVA: 0x3322830 VA: 0x759593a830
	public Void .ctor() { }
}
```