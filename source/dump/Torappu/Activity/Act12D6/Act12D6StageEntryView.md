# Act12D6StageEntryView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `GameObject _panelStageEndTime`

- `GameObject _panelRewardEndTime`

- `Text _textStageEndTime`

- `Text _textRewardEndTime`

- `Text _textRemainTime`

- `Color _remainTimeColor`

- `Button _btnMillstone`

- `GameObject _lockEntry`

- `GameObject _endBtn`

- `Button _btnPlayerBuff`

- `GameObject _objbuff`

- `GameObject _panelContinue`

- `Text _textCurrentDifficulty`

- `Text _textLastStartTime`

- `Text _textLastNode`

- `GameObject _imageBuffLocked`

- `Image _imageChosenModeBg`

- `GameObject _panelStartNew`

- `Text _textDifficultyChosen`

- `Image _imageDifficultyBg`

- `Animator _diffDescAnimator`

- `Button _btnNewGame`

- `GameObject _panelNewGameLock`

- `Text _textNewGameLock`

- `String m_difficulty`

- `Status m_status`

- `CountDownTask m_reOpenTask`


## Properties

- `String Difficulty`


## Methods

- `String get_Difficulty()`

- `Void set_Difficulty(String)`

- `Void _RenderDifficulty()`

- `String _FormatRemainTime(TimeSpan)`

- `Void Render(CurrentData)`

- `Void Update()`

- `Void EventOnNewGameLockClicked()`

- `Void _DealWithNewGameCoolDown()`

- `Void _TickNewGameCoolDownTime(TickValue)`

- `Int64 _CheckReOpenRemainSeconds()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6StageEntryView : MonoBehaviour, IHotfixable
{
	private GameObject _panelStageEndTime; // 0x18
	private GameObject _panelRewardEndTime; // 0x20
	private Text _textStageEndTime; // 0x28
	private Text _textRewardEndTime; // 0x30
	private Text _textRemainTime; // 0x38
	private Color _remainTimeColor; // 0x40
	private Button _btnMillstone; // 0x50
	private GameObject _lockEntry; // 0x58
	private GameObject _endBtn; // 0x60
	private Button _btnPlayerBuff; // 0x68
	private GameObject _objbuff; // 0x70
	private GameObject _panelContinue; // 0x78
	private Text _textCurrentDifficulty; // 0x80
	private Text _textLastStartTime; // 0x88
	private Text _textLastNode; // 0x90
	private GameObject _imageBuffLocked; // 0x98
	private Image _imageChosenModeBg; // 0xa0
	private GameObject _panelStartNew; // 0xa8
	private Text _textDifficultyChosen; // 0xb0
	private Toggle[] _toggles; // 0xb8
	private Image _imageDifficultyBg; // 0xc0
	private Animator _diffDescAnimator; // 0xc8
	private Button _btnNewGame; // 0xd0
	private GameObject _panelNewGameLock; // 0xd8
	private Text _textNewGameLock; // 0xe0
	private String m_difficulty; // 0xe8
	private Status m_status; // 0xf0
	private CountDownTask m_reOpenTask; // 0x118
	private static DelegateBridge __Hotfix0_get_Difficulty; // 0x0
	private static DelegateBridge __Hotfix0_set_Difficulty; // 0x8
	private static DelegateBridge __Hotfix0__RenderDifficulty; // 0x10
	private static DelegateBridge __Hotfix0__FormatRemainTime; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge __Hotfix0_EventOnNewGameLockClicked; // 0x30
	private static DelegateBridge __Hotfix0__DealWithNewGameCoolDown; // 0x38
	private static DelegateBridge __Hotfix0__TickNewGameCoolDownTime; // 0x40
	private static DelegateBridge __Hotfix0__CheckReOpenRemainSeconds; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String Difficulty { get; set; }

	// RVA: 0x3479b7c VA: 0x7595a91b7c
	public String get_Difficulty() { }
	// RVA: 0x3479be4 VA: 0x7595a91be4
	public Void set_Difficulty(String value) { }
	// RVA: 0x3479c70 VA: 0x7595a91c70
	private Void _RenderDifficulty() { }
	// RVA: 0x3479e98 VA: 0x7595a91e98
	private String _FormatRemainTime(TimeSpan timeSpan) { }
	// RVA: 0x347a0f0 VA: 0x7595a920f0
	public Void Render(CurrentData currentData) { }
	// RVA: 0x347b620 VA: 0x7595a93620
	private Void Update() { }
	// RVA: 0x347b69c VA: 0x7595a9369c
	public Void EventOnNewGameLockClicked() { }
	// RVA: 0x347b3cc VA: 0x7595a933cc
	private Void _DealWithNewGameCoolDown() { }
	// RVA: 0x347b834 VA: 0x7595a93834
	private Void _TickNewGameCoolDownTime(TickValue tickValue) { }
	// RVA: 0x347b734 VA: 0x7595a93734
	private Int64 _CheckReOpenRemainSeconds() { }
	// RVA: 0x347b98c VA: 0x7595a9398c
	public Void .ctor() { }
}
```