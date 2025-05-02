# ActMultiV3BattleFinishFootballModeView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `UIAnimationLocation _animEnter`

- `Text _textGoalMine`

- `Text _textGoalOther`

- `Text _textGoalDiff`

- `GameObject _newGoalGO`

- `Boolean m_hasInited`

- `Tween m_animTween`

- `BattleFinishFootballMapModel m_footballModel`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishFootballModeView : ActMultiV3BattleFinishModeViewBase
{
	private UIAnimationLocation _animEnter; // 0x30
	private Text _textGoalMine; // 0x40
	private Text _textGoalOther; // 0x48
	private Text _textGoalDiff; // 0x50
	private GameObject _newGoalGO; // 0x58
	private Boolean m_hasInited; // 0x60
	private Tween m_animTween; // 0x68
	private BattleFinishFootballMapModel m_footballModel; // 0x70
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x317d79c VA: 0x759579579c
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x317d804 VA: 0x7595795804
	public override Tween GenerateShowTween() { }
	// RVA: 0x317d8e8 VA: 0x75957958e8
	protected override Void OnEnter() { }
	// RVA: 0x317da8c VA: 0x7595795a8c
	private Void _InitIfNot() { }
	// RVA: 0x317dd08 VA: 0x7595795d08
	public Void .ctor() { }
}
```