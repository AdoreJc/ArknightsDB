# MeetingClueReceiveView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `MeetingClueAdapter _clueAdapter`

- `Button _receiveAllButton`

- `CanvasGroup _receiveAllButtonCanvasGroup`

- `GameObject _receiveBonusHint`

- `GameObject _receiveNoBonusHint`

- `GameObject _ruleHint`

- `GameObject _emptyHint`

- `IMeetingSession m_session`

- `Action m_receiveAllCallback`

- `RectTransform m_rect`

- `Vector2 m_tweenBase`

- `Vector2 m_tweenTarget`


## Properties

- `Boolean receiveAllAvailable`


## Methods

- `Void set_receiveAllAvailable(Boolean)`

- `Void Setup(IMeetingSession, Action`2, Action)`

- `Void RefreshClueList()`

- `Void _SetupClueList()`

- `Void _OnCluePressed(IMeetingClue, MeetingClueItemView)`

- `Void OnReceiveAllPressed()`

- `Void OnInfoButtonPressed()`

- `Void OnRuleHintPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueReceiveView : MonoBehaviour
{
	private MeetingClueAdapter _clueAdapter; // 0x18
	private Button _receiveAllButton; // 0x20
	private CanvasGroup _receiveAllButtonCanvasGroup; // 0x28
	private GameObject _receiveBonusHint; // 0x30
	private GameObject _receiveNoBonusHint; // 0x38
	private GameObject _ruleHint; // 0x40
	private GameObject _emptyHint; // 0x48
	private IMeetingSession m_session; // 0x50
	private Action`2 m_clickCallback; // 0x58
	private Action m_receiveAllCallback; // 0x60
	private RectTransform m_rect; // 0x68
	private Vector2 m_tweenBase; // 0x70
	private Vector2 m_tweenTarget; // 0x78

	private Boolean receiveAllAvailable { set; }

	// RVA: 0x3df96f8 VA: 0x75964116f8
	private Void set_receiveAllAvailable(Boolean value) { }
	// RVA: 0x3df9748 VA: 0x7596411748
	public Void Setup(IMeetingSession session, Action`2 clickCallback, Action receiveAllCallback) { }
	// RVA: 0x3df9b4c VA: 0x7596411b4c
	public Void RefreshClueList() { }
	// RVA: 0x3df9860 VA: 0x7596411860
	private Void _SetupClueList() { }
	// RVA: 0x3df9b50 VA: 0x7596411b50
	private Void _OnCluePressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3df9b6c VA: 0x7596411b6c
	public Void OnReceiveAllPressed() { }
	// RVA: 0x3df9b88 VA: 0x7596411b88
	public Void OnInfoButtonPressed() { }
	// RVA: 0x3df9b98 VA: 0x7596411b98
	public Void OnRuleHintPressed() { }
	// RVA: 0x3df9ba8 VA: 0x7596411ba8
	public Void .ctor() { }
}
```