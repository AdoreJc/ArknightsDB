# ActMultiV3BattleFinishDefenceModeView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `GameObject _newStarGO`

- `GameObject _newDamageGO`

- `Text _textDesc`

- `Image _imgType`

- `Text _textCurrWave`

- `Text _textMaxWave`

- `Text _textBossDamage`

- `Slider _sliderBossHealth`

- `Text _textProgressVal1`

- `Text _textProgressVal2`

- `Text _textProgressVal3`

- `Text _textProgressMax1`

- `Text _textProgressMax2`

- `Text _textProgressMax3`

- `Slider _sliderProgress`

- `Single _sliderTweenDuration`

- `Single _finalTweenDuration`

- `Single _finalTweenDelay`

- `UIAnimationLocation _animEnter`

- `UIAnimationLocation _animFinalWaveEnter`

- `UIAnimationLocation _animBossKill`

- `UIAnimationLocation _animNewRecord`

- `Boolean m_hasInited`

- `BattleFinishDefenceMapModel m_defenceModel`

- `Tween m_animTween`


## Methods

- `Void _RenderProgress(Text, Text, Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishDefenceModeView : ActMultiV3BattleFinishModeViewBase
{
	private GameObject _newStarGO; // 0x30
	private GameObject _newDamageGO; // 0x38
	private Text _textDesc; // 0x40
	private Image _imgType; // 0x48
	private Text _textCurrWave; // 0x50
	private Text _textMaxWave; // 0x58
	private Text _textBossDamage; // 0x60
	private Slider _sliderBossHealth; // 0x68
	private Text _textProgressVal1; // 0x70
	private Text _textProgressVal2; // 0x78
	private Text _textProgressVal3; // 0x80
	private Text _textProgressMax1; // 0x88
	private Text _textProgressMax2; // 0x90
	private Text _textProgressMax3; // 0x98
	private Slider _sliderProgress; // 0xa0
	private Single _sliderTweenDuration; // 0xa8
	private Single _finalTweenDuration; // 0xac
	private Single _finalTweenDelay; // 0xb0
	private UIAnimationLocation[] _animCompleteList; // 0xb8
	private UIAnimationLocation _animEnter; // 0xc0
	private UIAnimationLocation _animFinalWaveEnter; // 0xd0
	private UIAnimationLocation _animBossKill; // 0xe0
	private UIAnimationLocation _animNewRecord; // 0xf0
	private Boolean m_hasInited; // 0x100
	private BattleFinishDefenceMapModel m_defenceModel; // 0x108
	private Tween m_animTween; // 0x110
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__RenderProgress; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x317c5b4 VA: 0x75957945b4
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x317c61c VA: 0x759579461c
	public override Tween GenerateShowTween() { }
	// RVA: 0x317ccac VA: 0x7595794cac
	protected override Void OnEnter() { }
	// RVA: 0x317d108 VA: 0x7595795108
	private Void _RenderProgress(Text textProgressVal, Text textProgressMax, Int32 targetIdx) { }
	// RVA: 0x317cfc4 VA: 0x7595794fc4
	private Void _InitIfNot() { }
	// RVA: 0x317d2b8 VA: 0x75957952b8
	public Void .ctor() { }
}
```