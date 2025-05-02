# BattleTimer

**Namespace:** ` `


## Fields

- `GameObject _panelContent`

- `BattleController m_battleController`

- `Text _timerText`

- `Single m_timerTextPlaytime`

- `Button _timerPlayNPause`

- `Text m_timerPlayNPauseText`

- `Button _timerRecord`

- `Button _timerReset`

- `TimerRecordScrollController m_timerRecordScrollController`

- `Single _timerRecordScrollSpeed`

- `Boolean _isDownward`

- `Int32 m_timerRecordCurrentIndex`

- `Boolean m_isResetPause`


## Properties

- `Single timerTextPlaytime`


## Methods

- `Single get_timerTextPlaytime()`

- `Void set_timerTextPlaytime(Single)`

- `String _GetPlaytimeFormat(Single)`

- `Void EventOnEntryClick()`

- `Void EventOnTimerPlayNPause()`

- `Void EventOnTimerRecord()`

- `Void EventOnTimerReset()`

- `Void EventOnRestartGame()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BattleTimer : MonoBehaviour
{
	private GameObject _panelContent; // 0x18
	private BattleController m_battleController; // 0x20
	private Text _timerText; // 0x28
	private Single m_timerTextPlaytime; // 0x30
	private Button _timerPlayNPause; // 0x38
	private Text m_timerPlayNPauseText; // 0x40
	private Button _timerRecord; // 0x48
	private Button _timerReset; // 0x50
	private Text[] _timerRecordTexts; // 0x58
	private TimerRecordScrollController m_timerRecordScrollController; // 0x60
	private Single _timerRecordScrollSpeed; // 0x68
	private Boolean _isDownward; // 0x6c
	private Int32 m_timerRecordCurrentIndex; // 0x70
	private List`1 m_timerRecords; // 0x78
	private Boolean m_isResetPause; // 0x80

	private Single timerTextPlaytime { get; set; }

	// RVA: 0x1b29b14 VA: 0x7594141b14
	private Single get_timerTextPlaytime() { }
	// RVA: 0x1b29b1c VA: 0x7594141b1c
	private Void set_timerTextPlaytime(Single value) { }
	// RVA: 0x1b29b50 VA: 0x7594141b50
	private String _GetPlaytimeFormat(Single playTime) { }
	// RVA: 0x1b29e1c VA: 0x7594141e1c
	public Void EventOnEntryClick() { }
	// RVA: 0x1b29e20 VA: 0x7594141e20
	public Void EventOnTimerPlayNPause() { }
	// RVA: 0x1b29e24 VA: 0x7594141e24
	public Void EventOnTimerRecord() { }
	// RVA: 0x1b29e28 VA: 0x7594141e28
	public Void EventOnTimerReset() { }
	// RVA: 0x1b29e2c VA: 0x7594141e2c
	public Void EventOnRestartGame() { }
	// RVA: 0x1b29e30 VA: 0x7594141e30
	public Void .ctor() { }
}
```