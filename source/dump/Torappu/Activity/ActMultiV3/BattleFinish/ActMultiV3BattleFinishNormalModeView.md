# ActMultiV3BattleFinishNormalModeView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `GameObject _penaltyHintGO`

- `Text _textTitle`

- `Text _textDesc`

- `Image _imgType`

- `Slider _sliderStage1`

- `Slider _sliderStage2`

- `Text _textProgressVal1`

- `Text _textProgressVal2`

- `Text _textProgressVal3`

- `Text _textProgressMax1`

- `Text _textProgressMax2`

- `Text _textProgressMax3`

- `Single _sliderTweenDuration`

- `UIAnimationLocation _animComplete1`

- `UIAnimationLocation _animComplete2`

- `UIAnimationLocation _animComplete3`

- `UIAnimationLocation _animEnter`

- `GameObject _newStarGO`

- `Boolean m_hasInited`

- `Tween m_animTween`

- `BattleFinishNormalMapModel m_normalModel`


## Methods

- `Void _RenderProgress(Text, Text, Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishNormalModeView : ActMultiV3BattleFinishModeViewBase
{
	private GameObject _penaltyHintGO; // 0x30
	private Text _textTitle; // 0x38
	private Text _textDesc; // 0x40
	private Image _imgType; // 0x48
	private Slider _sliderStage1; // 0x50
	private Slider _sliderStage2; // 0x58
	private Text _textProgressVal1; // 0x60
	private Text _textProgressVal2; // 0x68
	private Text _textProgressVal3; // 0x70
	private Text _textProgressMax1; // 0x78
	private Text _textProgressMax2; // 0x80
	private Text _textProgressMax3; // 0x88
	private Single _sliderTweenDuration; // 0x90
	private UIAnimationLocation _animComplete1; // 0x98
	private UIAnimationLocation _animComplete2; // 0xa8
	private UIAnimationLocation _animComplete3; // 0xb8
	private UIAnimationLocation _animEnter; // 0xc8
	private GameObject _newStarGO; // 0xd8
	private Boolean m_hasInited; // 0xe0
	private Tween m_animTween; // 0xe8
	private BattleFinishNormalMapModel m_normalModel; // 0xf0
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__RenderProgress; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x317e224 VA: 0x7595796224
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x317e28c VA: 0x759579628c
	public override Tween GenerateShowTween() { }
	// RVA: 0x317e8b4 VA: 0x75957968b4
	protected override Void OnEnter() { }
	// RVA: 0x317eddc VA: 0x7595796ddc
	private Void _RenderProgress(Text textProgressVal, Text textProgressMax, Int32 targetIdx) { }
	// RVA: 0x317eac4 VA: 0x7595796ac4
	private Void _InitIfNot() { }
	// RVA: 0x317ef80 VA: 0x7595796f80
	public Void .ctor() { }
}
```