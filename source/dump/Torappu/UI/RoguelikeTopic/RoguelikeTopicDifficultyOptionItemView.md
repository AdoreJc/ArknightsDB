# RoguelikeTopicDifficultyOptionItemView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _textName`

- `Graphic _imgBg`

- `Graphic _imgGlow`

- `GameObject _selectedPartGo`

- `GameObject _lockedImg`

- `RoguelikeTopicDifficultyViewModel m_diffModel`

- `Boolean m_isSelected`


## Methods

- `Void set_onDiffSelected(Action`1)`

- `Void Render(RoguelikeTopicDifficultyViewModel, Boolean)`

- `Void _SetImageColor(Graphic, Color)`

- `Void OnDiffSelected()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicDifficultyOptionItemView : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private Graphic _imgBg; // 0x20
	private Graphic _imgGlow; // 0x28
	private GameObject _selectedPartGo; // 0x30
	private GameObject _lockedImg; // 0x38
	private Action`1 <onDiffSelected>k__BackingField; // 0x40
	private RoguelikeTopicDifficultyViewModel m_diffModel; // 0x48
	private Boolean m_isSelected; // 0x50
	private static DelegateBridge __Hotfix0_get_onDiffSelected; // 0x0
	private static DelegateBridge __Hotfix0_set_onDiffSelected; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__SetImageColor; // 0x18
	private static DelegateBridge __Hotfix0_OnDiffSelected; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onDiffSelected { get; set; }

	// RVA: 0x265103c VA: 0x7594c6903c
	private Action`1 get_onDiffSelected() { }
	// RVA: 0x26510a4 VA: 0x7594c690a4
	public Void set_onDiffSelected(Action`1 value) { }
	// RVA: 0x2651128 VA: 0x7594c69128
	public Void Render(RoguelikeTopicDifficultyViewModel diffModel, Boolean isSelected) { }
	// RVA: 0x2651344 VA: 0x7594c69344
	private Void _SetImageColor(Graphic image, Color c) { }
	// RVA: 0x265142c VA: 0x7594c6942c
	public Void OnDiffSelected() { }
	// RVA: 0x2651520 VA: 0x7594c69520
	public Void .ctor() { }
}
```