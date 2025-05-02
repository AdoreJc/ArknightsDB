# UIAutoBattlePanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _topMask`

- `Image _bottomMask`

- `Material _normalTopMaterial`

- `Material _normalBottomMaterial`

- `Color _errorColor`

- `Sprite _errorMask`

- `Single _normalMaskHeight`

- `Single _errorMaskHeight`

- `Text _comboCardText`

- `Single _interval`

- `AutoState m_state`

- `Single m_interval`


## Methods

- `Void Display(Boolean)`

- `Void UpdateData(BattleController)`

- `Void OnAutoReplayFinished()`

- `Boolean TryHookGameOver(GameResult, PlayerBattleRank, BattleReward)`

- `Void _OnEnterState(AutoState)`

- `Boolean _CheckErrorOccurred(BattleController)`

- `Void EventOnExitAutoBattle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIAutoBattlePanel : MonoBehaviour
{
	private Transform[] _autoBattleStates; // 0x18
	private Image _topMask; // 0x20
	private Image _bottomMask; // 0x28
	private Material _normalTopMaterial; // 0x30
	private Material _normalBottomMaterial; // 0x38
	private Color _errorColor; // 0x40
	private Sprite _errorMask; // 0x50
	private Single _normalMaskHeight; // 0x58
	private Single _errorMaskHeight; // 0x5c
	private Text _comboCardText; // 0x60
	private Animator[] _buttonAnimation; // 0x68
	private Single _interval; // 0x70
	private AutoState m_state; // 0x74
	private Single m_interval; // 0x78


	// RVA: 0x2079fac VA: 0x7594691fac
	public Void Display(Boolean isShow) { }
	// RVA: 0x207a3c4 VA: 0x75946923c4
	public Void UpdateData(BattleController controller) { }
	// RVA: 0x207a5dc VA: 0x75946925dc
	public Void OnAutoReplayFinished() { }
	// RVA: 0x207a5e4 VA: 0x75946925e4
	public Boolean TryHookGameOver(GameResult result, PlayerBattleRank battleRank, BattleReward reward) { }
	// RVA: 0x2079ff4 VA: 0x7594691ff4
	private Void _OnEnterState(AutoState newState) { }
	// RVA: 0x207a4f0 VA: 0x75946924f0
	private Boolean _CheckErrorOccurred(BattleController controller) { }
	// RVA: 0x207abb4 VA: 0x7594692bb4
	public Void EventOnExitAutoBattle() { }
	// RVA: 0x207af58 VA: 0x7594692f58
	public Void .ctor() { }
}
```