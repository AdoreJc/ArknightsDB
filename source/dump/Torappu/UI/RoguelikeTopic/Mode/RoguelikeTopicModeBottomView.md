# RoguelikeTopicModeBottomView

**Namespace:** `Torappu.UI.RoguelikeTopic.Mode`


## Fields

- `GameObject _pnlMonthModeRefresh`

- `Text _textMonthModeRefresh`

- `GameObject _trackpointMonthModeRefresh`

- `GameObject _trackpointChallengeModeRefresh`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnModeTabClicked(SerializeTabID)`

- `Void _RefreshMonthModeInfo(RoguelikeTopicModeViewModel)`

- `Void _RefreshChallengeModeInfo(RoguelikeTopicModeViewModel)`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Mode
public class RoguelikeTopicModeBottomView : RoguelikeTopicSubView
{
	private RoguelikeTopicModeToggle[] _toggles; // 0x28
	private GameObject _pnlMonthModeRefresh; // 0x30
	private Text _textMonthModeRefresh; // 0x38
	private GameObject _trackpointMonthModeRefresh; // 0x40
	private GameObject _trackpointChallengeModeRefresh; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnModeTabClicked; // 0x10
	private static DelegateBridge __Hotfix0__RefreshMonthModeInfo; // 0x18
	private static DelegateBridge __Hotfix0__RefreshChallengeModeInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26d6104 VA: 0x7594cee104
	private Void _InitIfNot() { }
	// RVA: 0x26d6290 VA: 0x7594cee290
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26d6c08 VA: 0x7594ceec08
	private Void _OnModeTabClicked(SerializeTabID clickedTab) { }
	// RVA: 0x26d6858 VA: 0x7594cee858
	private Void _RefreshMonthModeInfo(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26d6b28 VA: 0x7594ceeb28
	private Void _RefreshChallengeModeInfo(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26d6cb8 VA: 0x7594ceecb8
	public Void .ctor() { }
	// RVA: 0x26d6d24 VA: 0x7594ceed24
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```