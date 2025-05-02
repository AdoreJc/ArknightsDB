# TopBarStatus

**Namespace:** ` `


## Fields

- `Text _timerText`

- `Color _timerTextDefaultColor`

- `Color _timerTextFinalColor`

- `Color _timerTextBlinkColor`

- `Vector3 _timerTextTweenScale`

- `Int32 _timerBeginTweenTime`

- `Single _timerTweenDuration`

- `Text _scoreText`

- `Transform _scoreSuffix`

- `Slider _scoreSliderRight`

- `Slider _scoreSliderLeft`

- `Vector3 _scoreTextTweenScale`

- `Vector3 _scoreSuffixTweenScale`

- `Single _scoreTweenDuration`

- `Int32 m_maxPlayTime`

- `Int32 m_playTime`

- `Int32 m_score`

- `Sequence m_scoreTweenSequence`

- `Vector3 m_scoreTextDefaultScale`

- `Vector3 m_scoreSuffixDefaultScale`

- `Sequence m_timerTweenSequence`

- `Vector3 m_timerTextDefaultScale`

- `Color m_timerTextDefaultColor`


## Methods

- `Void Init(Act20SideGameMode)`

- `Void UpdateData(BattleController)`

- `Void _UpdateBattleTimeInfo(BattleController)`

- `Void _TweenTimeText()`

- `Void UpdateScore(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TopBarStatus
{
	private Text _timerText; // 0x10
	private Color _timerTextDefaultColor; // 0x18
	private Color _timerTextFinalColor; // 0x28
	private Color _timerTextBlinkColor; // 0x38
	private Vector3 _timerTextTweenScale; // 0x48
	private Int32 _timerBeginTweenTime; // 0x54
	private Single _timerTweenDuration; // 0x58
	private Text _scoreText; // 0x60
	private Transform _scoreSuffix; // 0x68
	private Slider _scoreSliderRight; // 0x70
	private Slider _scoreSliderLeft; // 0x78
	private Vector3 _scoreTextTweenScale; // 0x80
	private Vector3 _scoreSuffixTweenScale; // 0x8c
	private Single _scoreTweenDuration; // 0x98
	private Int32 m_maxPlayTime; // 0x9c
	private Int32 m_playTime; // 0xa0
	private Int32 m_score; // 0xa4
	private Sequence m_scoreTweenSequence; // 0xa8
	private Vector3 m_scoreTextDefaultScale; // 0xb0
	private Vector3 m_scoreSuffixDefaultScale; // 0xbc
	private Sequence m_timerTweenSequence; // 0xc8
	private Vector3 m_timerTextDefaultScale; // 0xd0
	private Color m_timerTextDefaultColor; // 0xdc


	// RVA: 0x3305744 VA: 0x759591d744
	public Void Init(Act20SideGameMode gameMode) { }
	// RVA: 0x3305950 VA: 0x759591d950
	public Void UpdateData(BattleController controller) { }
	// RVA: 0x33060bc VA: 0x759591e0bc
	private Void _UpdateBattleTimeInfo(BattleController controller) { }
	// RVA: 0x3306354 VA: 0x759591e354
	private Void _TweenTimeText() { }
	// RVA: 0x33059ec VA: 0x759591d9ec
	public Void UpdateScore(Int32 value) { }
	// RVA: 0x3306590 VA: 0x759591e590
	public Void .ctor() { }
}
```