# CarvingMainRoundEndView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `TwoStateToggle _achieveGoalToggle`

- `Text _targetScoreText`

- `Text _curScoreText`

- `Text _curRoundText`

- `Text _targetRoundText`

- `Text _coinText`

- `GameObject _levelClearPanel`

- `GameObject _unlimitedNotice`

- `GameObject _coinPart`

- `GameObject _nextRoundBtn`

- `GameObject _endClassBtn`

- `UIAnimationLocation _successEnterAnim`

- `UIAnimationLocation _failEnterAnim`

- `Tween m_enterAnim`


## Methods

- `Void ClearTween()`

- `Void _GenerateEnterAnim(Boolean, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainRoundEndView : DataBinder`1
{
	private const String TARGET_ROUND_TEXT_FORMAT; // 0x0
	private const String COIN_TEXT_FORMAT; // 0x0
	private const Int32 SCORE_ANIM_START_VALUE; // 0x0
	private const Single SCORE_ANIM_FADETIME; // 0x0
	private const Single SCORE_ANIM_DELAY; // 0x0
	private TwoStateToggle _achieveGoalToggle; // 0x20
	private Text _targetScoreText; // 0x28
	private Text _curScoreText; // 0x30
	private Text _curRoundText; // 0x38
	private Text _targetRoundText; // 0x40
	private Text _coinText; // 0x48
	private GameObject _levelClearPanel; // 0x50
	private GameObject _unlimitedNotice; // 0x58
	private GameObject _coinPart; // 0x60
	private GameObject _nextRoundBtn; // 0x68
	private GameObject _endClassBtn; // 0x70
	private UIAnimationLocation _successEnterAnim; // 0x78
	private UIAnimationLocation _failEnterAnim; // 0x88
	private Tween m_enterAnim; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_ClearTween; // 0x8
	private static DelegateBridge __Hotfix0__GenerateEnterAnim; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2db5cc0 VA: 0x75953cdcc0
	public override Void OnValueChanged(CarvingMainRoundEndProperty property) { }
	// RVA: 0x2db5b08 VA: 0x75953cdb08
	public Void ClearTween() { }
	// RVA: 0x2db6324 VA: 0x75953ce324
	private Void _GenerateEnterAnim(Boolean passRound, Int32 curScore) { }
	// RVA: 0x2db64e8 VA: 0x75953ce4e8
	public Void .ctor() { }
}
```