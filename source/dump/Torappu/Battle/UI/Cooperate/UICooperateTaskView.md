# UICooperateTaskView

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UIAnimationLocation _animStartBasic`

- `UIAnimationLocation _animEndBasic`

- `UIAnimationLocation _animStartAdvance`

- `UIAnimationLocation _animStage`

- `UIAnimationLocation _animComplete`

- `UIAnimationLocation _animOuterLoop`

- `UIAnimationLocation _animTimer`

- `Int32 _animTimerShow`

- `Text _stageInfo`

- `RectTransform _basicPart`

- `Text _basicScore`

- `Text _advanceScore`

- `GameObject _advanceAccomplishDeco`

- `GameObject _advanceAccomplishGroup`

- `Slider _progressSlider`

- `Image _progressSliderMask`

- `RectTransform _sliderMask`

- `Single _sliderSpeed`

- `Text _stageTimerNormal`

- `Text _stageTimer`

- `GameObject _sliderCover`

- `CanvasGroup _fillField`

- `Slider _progressOuterSlider`

- `GameObject _timerAlarmDecoLeft`

- `GameObject _timerAlarmDecoRight`

- `GameObject _timerBg`

- `Single _outerStartOffset`

- `Single _outerEndOffset`

- `Single _silderZeroValueOffset`

- `Single _silderZeroValurMargin`

- `Boolean m_sliderBasicReach`

- `Boolean m_sliderAdvanceReach`

- `Boolean m_sliderValueHold`

- `Single m_outerSliderValue`

- `Single m_innerSliderValue`

- `Boolean m_isOuterShown`

- `Vector2 m_sliderMaskOrigPos`


## Properties

- `Boolean sliderValueHold`

- `Text basicScore`

- `Text advanceScore`


## Methods

- `Boolean get_sliderValueHold()`

- `Text get_basicScore()`

- `Text get_advanceScore()`

- `Void OnGameReady(Boolean)`

- `Void RegistTask(String, Boolean)`

- `Void RestoreFromRest()`

- `Void SliderReachBasic(Boolean)`

- `Void SliderReachAdvance(Boolean, Boolean)`

- `Void SliderReachAdvanceStage1()`

- `Void StageEndAnim()`

- `Void SetOuterSlider(Single)`

- `Void SetReachBasic(FP)`

- `Void SetStageTimer(FP)`

- `String TimeToShow(FP)`

- `Void StopTimerAnim()`

- `Single SetSliderValue(Single)`

- `Void HardSetSliderValue(Single)`

- `Void SetFontSize(Boolean)`

- `Void _OnStageEndAnimFinish()`

- `Void _PlayAnimation(UIAnimationLocation)`

- `Void _PlayAnimationWithTween(UIAnimationLocation, TweenCallback)`

- `Void <SliderReachAdvanceStage1>b__53_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateTaskView : MonoBehaviour, IHotfixable
{
	private const String TIME_FORMAT; // 0x0
	private const Single OUTER_MIN_SHOW_VALUE; // 0x0
	public static Single BASIC_SPLIT_CNT; // 0x0
	private const Int32 BASIC_FONT_SIZE; // 0x0
	private const Int32 SPECIAL_FONT_SIZE; // 0x0
	private UIAnimationLocation _animStartBasic; // 0x18
	private UIAnimationLocation _animEndBasic; // 0x28
	private UIAnimationLocation _animStartAdvance; // 0x38
	private UIAnimationLocation _animStage; // 0x48
	private UIAnimationLocation _animComplete; // 0x58
	private UIAnimationLocation _animOuterLoop; // 0x68
	private UIAnimationLocation _animTimer; // 0x78
	private Int32 _animTimerShow; // 0x88
	private Text _stageInfo; // 0x90
	private RectTransform _basicPart; // 0x98
	private Text _basicScore; // 0xa0
	private Text _advanceScore; // 0xa8
	private GameObject _advanceAccomplishDeco; // 0xb0
	private GameObject _advanceAccomplishGroup; // 0xb8
	private Slider _progressSlider; // 0xc0
	private Image _progressSliderMask; // 0xc8
	private RectTransform _sliderMask; // 0xd0
	private Single _sliderSpeed; // 0xd8
	private Text _stageTimerNormal; // 0xe0
	private Text _stageTimer; // 0xe8
	private GameObject _sliderCover; // 0xf0
	private CanvasGroup _fillField; // 0xf8
	private Slider _progressOuterSlider; // 0x100
	private GameObject _timerAlarmDecoLeft; // 0x108
	private GameObject _timerAlarmDecoRight; // 0x110
	private GameObject _timerBg; // 0x118
	private Single _outerStartOffset; // 0x120
	private Single _outerEndOffset; // 0x124
	private Single _silderZeroValueOffset; // 0x128
	private Single _silderZeroValurMargin; // 0x12c
	private Boolean m_sliderBasicReach; // 0x130
	private Boolean m_sliderAdvanceReach; // 0x131
	private Boolean m_sliderValueHold; // 0x132
	private Single m_outerSliderValue; // 0x134
	private Single m_innerSliderValue; // 0x138
	private Boolean m_isOuterShown; // 0x13c
	private Vector2 m_sliderMaskOrigPos; // 0x140
	private static DelegateBridge __Hotfix0_get_sliderValueHold; // 0x8
	private static DelegateBridge __Hotfix0_get_basicScore; // 0x10
	private static DelegateBridge __Hotfix0_get_advanceScore; // 0x18
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x20
	private static DelegateBridge __Hotfix0_RegistTask; // 0x28
	private static DelegateBridge __Hotfix0_RestoreFromRest; // 0x30
	private static DelegateBridge __Hotfix0_SliderReachBasic; // 0x38
	private static DelegateBridge __Hotfix0_SliderReachAdvance; // 0x40
	private static DelegateBridge __Hotfix0_SliderReachAdvanceStage1; // 0x48
	private static DelegateBridge __Hotfix0_StageEndAnim; // 0x50
	private static DelegateBridge __Hotfix0_SetOuterSlider; // 0x58
	private static DelegateBridge __Hotfix0_SetReachBasic; // 0x60
	private static DelegateBridge __Hotfix0_SetStageTimer; // 0x68
	private static DelegateBridge __Hotfix0_TimeToShow; // 0x70
	private static DelegateBridge __Hotfix0_StopTimerAnim; // 0x78
	private static DelegateBridge __Hotfix0_SetSliderValue; // 0x80
	private static DelegateBridge __Hotfix0_HardSetSliderValue; // 0x88
	private static DelegateBridge __Hotfix0_SetFontSize; // 0x90
	private static DelegateBridge __Hotfix0__OnStageEndAnimFinish; // 0x98
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0xa0
	private static DelegateBridge __Hotfix0__PlayAnimationWithTween; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public Boolean sliderValueHold { get; }
	public Text basicScore { get; }
	public Text advanceScore { get; }

	// RVA: 0x20d75f4 VA: 0x75946ef5f4
	public Boolean get_sliderValueHold() { }
	// RVA: 0x20d4cf4 VA: 0x75946eccf4
	public Text get_basicScore() { }
	// RVA: 0x20d4c7c VA: 0x75946ecc7c
	public Text get_advanceScore() { }
	// RVA: 0x20da240 VA: 0x75946f2240
	public Void OnGameReady(Boolean isFortessMode) { }
	// RVA: 0x20d6fdc VA: 0x75946eefdc
	public Void RegistTask(String taskDesc, Boolean isFirstStage) { }
	// RVA: 0x20d7220 VA: 0x75946ef220
	public Void RestoreFromRest() { }
	// RVA: 0x20d78ac VA: 0x75946ef8ac
	public Void SliderReachBasic(Boolean reach) { }
	// RVA: 0x20d79e8 VA: 0x75946ef9e8
	public Void SliderReachAdvance(Boolean reach, Boolean advanceFinish) { }
	// RVA: 0x20d7794 VA: 0x75946ef794
	public Void SliderReachAdvanceStage1() { }
	// RVA: 0x20d753c VA: 0x75946ef53c
	public Void StageEndAnim() { }
	// RVA: 0x20da440 VA: 0x75946f2440
	public Void SetOuterSlider(Single value) { }
	// RVA: 0x20d3878 VA: 0x75946eb878
	public Void SetReachBasic(FP percentage) { }
	// RVA: 0x20d3738 VA: 0x75946eb738
	public Void SetStageTimer(FP time) { }
	// RVA: 0x20da544 VA: 0x75946f2544
	public String TimeToShow(FP time) { }
	// RVA: 0x20d73a0 VA: 0x75946ef3a0
	public Void StopTimerAnim() { }
	// RVA: 0x20d766c VA: 0x75946ef66c
	public Single SetSliderValue(Single value) { }
	// RVA: 0x20da7c4 VA: 0x75946f27c4
	public Void HardSetSliderValue(Single value) { }
	// RVA: 0x20d7144 VA: 0x75946ef144
	public Void SetFontSize(Boolean specialFontSize) { }
	// RVA: 0x20da8ac VA: 0x75946f28ac
	private Void _OnStageEndAnimFinish() { }
	// RVA: 0x20da380 VA: 0x75946f2380
	private Void _PlayAnimation(UIAnimationLocation animLocation) { }
	// RVA: 0x20da954 VA: 0x75946f2954
	private Void _PlayAnimationWithTween(UIAnimationLocation animLocation, TweenCallback onComplete) { }
	// RVA: 0x20daa50 VA: 0x75946f2a50
	public Void .ctor() { }
	// RVA: 0x20daaec VA: 0x75946f2aec
	private static Void .cctor() { }
	// RVA: 0x20dab3c VA: 0x75946f2b3c
	private Void <SliderReachAdvanceStage1>b__53_0() { }
}
```