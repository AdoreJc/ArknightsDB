# RoguelikeTopicModeForegroundView

**Namespace:** `Torappu.UI.RoguelikeTopic.Mode`


## Fields

- `GameObject _activePart`

- `Text _zoneName`

- `RoguelikeTopicCurrentDifficultyBaseView _activeDiffView`

- `Text _startTime`

- `GameObject _giveUpButton`

- `GameObject _unActivePart`

- `GameObject _countDownPart`

- `Text _countDownInfo`

- `RoguelikeTopicModeForegroundPluginContext m_pluginContext`

- `RoguelikeTopicModeViewProperty m_exploreProp`

- `CountDownTask m_cacheCountDownTask`

- `String m_topicId`

- `Boolean m_hasInited`


## Methods

- `Void Update()`

- `Void _InitIfNot()`

- `Void EventOnCreateGame()`

- `Void EventOnCancelGame()`

- `Void EventOnContinueGame()`

- `Void _OnDiffDetailShow()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Mode
public class RoguelikeTopicModeForegroundView : RoguelikeTopicSubView
{
	private GameObject _activePart; // 0x28
	private Text _zoneName; // 0x30
	private RoguelikeTopicCurrentDifficultyBaseView _activeDiffView; // 0x38
	private Text _startTime; // 0x40
	private GameObject _giveUpButton; // 0x48
	private GameObject _unActivePart; // 0x50
	private GameObject _countDownPart; // 0x58
	private Text _countDownInfo; // 0x60
	protected RoguelikeTopicModeForegroundPluginContext m_pluginContext; // 0x68
	private RoguelikeTopicModeViewProperty m_exploreProp; // 0x70
	private CountDownTask m_cacheCountDownTask; // 0x78
	private String m_topicId; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RefreshData; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCreateGame; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCancelGame; // 0x28
	private static DelegateBridge __Hotfix0_EventOnContinueGame; // 0x30
	private static DelegateBridge __Hotfix0__OnDiffDetailShow; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x26d6dac VA: 0x7594ceedac
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26d6fd8 VA: 0x7594ceefd8
	private Void Update() { }
	// RVA: 0x26d6e94 VA: 0x7594ceee94
	private Void _InitIfNot() { }
	// RVA: 0x26d7054 VA: 0x7594cef054
	protected virtual Void _RefreshData(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26d7524 VA: 0x7594cef524
	public Void EventOnCreateGame() { }
	// RVA: 0x26d7768 VA: 0x7594cef768
	public Void EventOnCancelGame() { }
	// RVA: 0x26d77f8 VA: 0x7594cef7f8
	public Void EventOnContinueGame() { }
	// RVA: 0x26d7888 VA: 0x7594cef888
	private Void _OnDiffDetailShow() { }
	// RVA: 0x26d7964 VA: 0x7594cef964
	public Void .ctor() { }
	// RVA: 0x26d79d0 VA: 0x7594cef9d0
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```