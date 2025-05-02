# RoguelikeEntryBottomItemView

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelNotEmpty`

- `Image _imgTopic`

- `Text _textBpName`

- `Text _textBpLevel`

- `GameObject _panelBpMax`

- `Image _imgMedal`

- `GameObject _panelMedal`

- `GameObject _panelCannotEntry`

- `GameObject _panelOnBattle`

- `MaskableGraphic _imgOnBattle`

- `GameObject _panelSelectedBtn`

- `GameObject _panelDLCUpdate`

- `GameObject _panelReviewUpdate`

- `UIAnimationLocation _switchAnim`

- `UIStateFinder m_stateFinder`

- `String m_cachedTopicId`

- `UISwitchTween m_switchTween`

- `Boolean m_hasInited`


## Methods

- `Void Render(RoguelikeEntryItemViewModel, Boolean)`

- `Void OnItemSelectClicked()`

- `Void OnEntryClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryBottomItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelNotEmpty; // 0x20
	private Image _imgTopic; // 0x28
	private Text _textBpName; // 0x30
	private Text _textBpLevel; // 0x38
	private GameObject _panelBpMax; // 0x40
	private Image _imgMedal; // 0x48
	private GameObject _panelMedal; // 0x50
	private GameObject[] _panelEntry; // 0x58
	private GameObject _panelCannotEntry; // 0x60
	private GameObject _panelOnBattle; // 0x68
	private MaskableGraphic _imgOnBattle; // 0x70
	private GameObject _panelSelectedBtn; // 0x78
	private GameObject[] _panelUnselectedBtn; // 0x80
	private GameObject _panelDLCUpdate; // 0x88
	private GameObject _panelReviewUpdate; // 0x90
	private UIAnimationLocation _switchAnim; // 0x98
	private UIStateFinder m_stateFinder; // 0xa8
	private String m_cachedTopicId; // 0xb8
	private UISwitchTween m_switchTween; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnItemSelectClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnEntryClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x262f6f4 VA: 0x7594c476f4
	public Void Render(RoguelikeEntryItemViewModel model, Boolean isFocusItem) { }
	// RVA: 0x262fc08 VA: 0x7594c47c08
	public Void OnItemSelectClicked() { }
	// RVA: 0x262fd08 VA: 0x7594c47d08
	public Void OnEntryClicked() { }
	// RVA: 0x262fb18 VA: 0x7594c47b18
	private Void _InitIfNot() { }
	// RVA: 0x262fe08 VA: 0x7594c47e08
	public Void .ctor() { }
}
```