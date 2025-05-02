# RL04DifficultyItem

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `GameObject _normalTitle`

- `GameObject _hardTitle`

- `Text _name`

- `Text _subName`

- `Text _gradeLvl`

- `SimpleLayoutContent _descList`

- `Color _descNormalColor`

- `Color _descBuffColor`

- `GameObject _warnningTag`

- `GameObject _lockedTag`

- `Text _lockedDesc`

- `GameObject _newTag`

- `TwoStateFadeSwitcher _buffTag`

- `Image _colorLine`

- `Int32 m_index`

- `DescListAdapter m_descAdapter`


## Methods

- `Void _InitIfNot()`

- `Void Render(ViewData)`

- `Void UpdateState(ViewData, Boolean, Boolean, Boolean)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04DifficultyItem : MonoBehaviour, IHotfixable
{
	private GameObject _normalTitle; // 0x18
	private GameObject _hardTitle; // 0x20
	private Text _name; // 0x28
	private Text _subName; // 0x30
	private Text _gradeLvl; // 0x38
	private SimpleLayoutContent _descList; // 0x40
	private Color _descNormalColor; // 0x48
	private Color _descBuffColor; // 0x58
	private GameObject _warnningTag; // 0x68
	private GameObject _lockedTag; // 0x70
	private Text _lockedDesc; // 0x78
	private GameObject _newTag; // 0x80
	private TwoStateFadeSwitcher _buffTag; // 0x88
	private RoguelikeTopicDifficultyItemColors[] _stateClrTargets; // 0x90
	private RoguelikeTopicDifficultyItemColors[] _mainClrTargets; // 0x98
	private Image _colorLine; // 0xa0
	private Action`1 m_onClick; // 0xa8
	private Int32 m_index; // 0xb0
	private DescListAdapter m_descAdapter; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_UpdateState; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26e8e78 VA: 0x7594d00e78
	private Void _InitIfNot() { }
	// RVA: 0x26e902c VA: 0x7594d0102c
	public Void Render(ViewData data) { }
	// RVA: 0x26e9574 VA: 0x7594d01574
	public Void UpdateState(ViewData data, Boolean include, Boolean selected, Boolean immediately) { }
	// RVA: 0x26e988c VA: 0x7594d0188c
	public Void EventOnClick() { }
	// RVA: 0x26e9914 VA: 0x7594d01914
	public Void .ctor() { }
}
```