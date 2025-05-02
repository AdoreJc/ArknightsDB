# RoguelikeEntryMainView

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `GameObject _panelUpdateUncomplete`

- `GameObject _panelUpdateComplete`

- `GameObject _panelReview`

- `Image _imgMain`

- `GameObject _panelPinned`

- `GameObject _panelBtnPin`

- `Text _textDesc`

- `UIAnimationLocation _fadeInAnim`

- `UIAnimationLocation _fadeOutAnim`

- `UIStateFinder m_stateFinder`

- `Int32 m_cachedEntrySequence`

- `String m_cachedTopicId`

- `Tween m_switchAnim`


## Methods

- `Void EventOnPinBtnClicked()`

- `Void EventOnArchiveBtnClicked()`

- `Void _Render(RoguelikeEntryItemViewModel)`

- `Void _KillSwitchAnimIfNecessary()`

- `Tween _GenerateSwitchAnim(RoguelikeEntryItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryMainView : DataBinder`1, IHotfixable
{
	private GameObject _panelUpdateUncomplete; // 0x20
	private GameObject _panelUpdateComplete; // 0x28
	private GameObject _panelReview; // 0x30
	private Image _imgMain; // 0x38
	private GameObject _panelPinned; // 0x40
	private GameObject _panelBtnPin; // 0x48
	private Text _textDesc; // 0x50
	private UIAnimationLocation _fadeInAnim; // 0x58
	private UIAnimationLocation _fadeOutAnim; // 0x68
	private UIStateFinder m_stateFinder; // 0x78
	private Int32 m_cachedEntrySequence; // 0x88
	private String m_cachedTopicId; // 0x90
	private Tween m_switchAnim; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnPinBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnArchiveBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0__KillSwitchAnimIfNecessary; // 0x20
	private static DelegateBridge __Hotfix0__GenerateSwitchAnim; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x26305c4 VA: 0x7594c485c4
	public override Void OnValueChanged(RoguelikeEntryProperty property) { }
	// RVA: 0x2630b64 VA: 0x7594c48b64
	public Void EventOnPinBtnClicked() { }
	// RVA: 0x2630c08 VA: 0x7594c48c08
	public Void EventOnArchiveBtnClicked() { }
	// RVA: 0x26307dc VA: 0x7594c487dc
	private Void _Render(RoguelikeEntryItemViewModel model) { }
	// RVA: 0x263073c VA: 0x7594c4873c
	private Void _KillSwitchAnimIfNecessary() { }
	// RVA: 0x2630988 VA: 0x7594c48988
	private Tween _GenerateSwitchAnim(RoguelikeEntryItemViewModel model) { }
	// RVA: 0x2630cac VA: 0x7594c48cac
	public Void .ctor() { }
}
```