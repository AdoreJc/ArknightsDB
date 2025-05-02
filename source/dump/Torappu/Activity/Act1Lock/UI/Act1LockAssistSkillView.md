# Act1LockAssistSkillView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `GameObject _selectedPanel`

- `GameObject _dividerPanel`

- `Image _skillImg`

- `Text _skillLevelText`

- `Text _skillNameText`

- `UISkillTagGroup _sillTagGroup`

- `UICommentedText _skillDescText`

- `Int32 m_position`


## Methods

- `Void set_onClickAction(Action`1)`

- `Void Render(Act1LockAssistViewModel, Int32, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockAssistSkillView : MonoBehaviour, IHotfixable
{
	private GameObject _selectedPanel; // 0x18
	private GameObject _dividerPanel; // 0x20
	private Image _skillImg; // 0x28
	private Text _skillLevelText; // 0x30
	private Text _skillNameText; // 0x38
	private UISkillTagGroup _sillTagGroup; // 0x40
	private UICommentedText _skillDescText; // 0x48
	private Int32 m_position; // 0x50
	private Action`1 <onClickAction>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onClickAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickAction; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 onClickAction { get; set; }

	// RVA: 0x33a7c98 VA: 0x75959bfc98
	public Action`1 get_onClickAction() { }
	// RVA: 0x33a7d00 VA: 0x75959bfd00
	public Void set_onClickAction(Action`1 value) { }
	// RVA: 0x33a7d84 VA: 0x75959bfd84
	public Void Render(Act1LockAssistViewModel viewModel, Int32 position, Boolean needDivider) { }
	// RVA: 0x33a8004 VA: 0x75959c0004
	public Void OnClick() { }
	// RVA: 0x33a80a4 VA: 0x75959c00a4
	public Void .ctor() { }
}
```