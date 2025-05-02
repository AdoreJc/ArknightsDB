# Act24sideMeldingView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `CanvasGroup _contentDetailCanvas`

- `RectTransform _transContentDetail`

- `Vector2 _contentDetailHidePos`

- `Vector2 _contentDetailShowPos`

- `SimpleLayoutContent _layoutContentMeldingDetail`

- `SimpleLayoutContent _layoutContentMeldingSimple`

- `Text _txtMeldingProgress`

- `CanvasGroup _canvasMeldingBtnGray`

- `CanvasGroup _canvasMeldingBtnNormal`

- `Slider _sliderSlot`

- `Slider _sliderInputMeldingProgress`

- `Slider _sliderMeldingProgress`

- `GameObject _objFastInputBtn`

- `GameObject _objClearAllInputBtn`

- `GameObject _objBlockerQuickInput`

- `UIAnimationLocation _gachaBoxSwitchAnim`

- `UIAnimationLocation _slotSwitchAnim`

- `Image _imgTotum1`

- `Image _imgTotum2`

- `UICommonPageEffectHolder _effectMeldingGlowingHolder`

- `UICommonPageEffectHolder _effectMeldingTailHolder`

- `Act24sideMeldingViewModel m_model`

- `MeldingDetailAdapter m_meldingDetailAdapter`

- `MeldingSimpleAdapter m_meldingSimpleAdapter`

- `Boolean m_hasInited`

- `Boolean m_isChoosing`

- `String m_cachedCurGachaBoxId`

- `Boolean m_isGachaGroup1Scrolled`

- `Boolean m_isGachaGroup2Scrolled`

- `FadeTranslationSwitchTween m_contentDetailTween`

- `Boolean m_isSwitchBoxAnimFastMode`

- `GachaBoxSwitchTween m_switchBoxTween`

- `UIStateFinder m_finder`

- `Boolean m_isMeldingInputProgressAnimFastMode`

- `MeldingProgressSwitchTween m_meldingInputProgressTween`

- `Int32 m_cachedInputMeldingPrice`

- `Sequence m_cachedMeldingSucTween`

- `Sequence m_cachedMeldingSucGlowingTween`

- `Material m_matTotum1`

- `Material m_matTotum2`

- `TweenWrapper m_progressTween`

- `TweenWrapper m_gachaBoxSwitchTween`

- `FadeSwitchTween m_meldBtnGrayTween`

- `FadeSwitchTween m_meldBtnNormalTween`

- `UIPage m_page`


## Methods

- `Void InitView(UIPage)`

- `Void TryScrollGachaBoxToRemainCountRarePart()`

- `Single TryPlayMeldingSucSequnce(String, List`1)`

- `Void TryPauseInputProgressTweening()`

- `Void ClearMeldingSucSeq()`

- `Void _InitIfNot()`

- `Void _PlaySwitchGachaBoxAnim(Boolean, Boolean)`

- `Void _InitGachaBoxes()`

- `Void _RenderGachaBoxes()`

- `Void _TryScrollGachasToProperLine()`

- `Void _PlayGachaBoxAndSlotSwitchAnim(Boolean, Boolean)`

- `Void _PlayInputMeldingProgressSwitchAnim(Boolean)`

- `Void _ClearInputCache()`

- `Single _TryPlayMeldingSucProgressSeq(String, List`1)`

- `Boolean _IsInputProgressTweening()`

- `Boolean _IsSwitchBoxTweening()`

- `Void _SetQuickInputBlockShow(Boolean)`

- `Void _TryQuickInputMeldings()`

- `Void EventOnSwitchGachaPool()`

- `Void EventOnFastInput()`

- `Void EventOnClearAllInput()`

- `Void EventOnChoiceDetailShow()`

- `Void EventOnChoiceDetailHide()`

- `Void EventOnMeldClick()`

- `Void EventOnQuickInputClick()`

- `Void <_TryPlayMeldingSucProgressSeq>b__77_2(Single)`

- `Void <_TryPlayMeldingSucProgressSeq>b__77_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingView : DataBinder`1
{
	private List`1 _gachaGroupList; // 0x20
	private CanvasGroup _contentDetailCanvas; // 0x28
	private RectTransform _transContentDetail; // 0x30
	private Vector2 _contentDetailHidePos; // 0x38
	private Vector2 _contentDetailShowPos; // 0x40
	private SimpleLayoutContent _layoutContentMeldingDetail; // 0x48
	private SimpleLayoutContent _layoutContentMeldingSimple; // 0x50
	private Text _txtMeldingProgress; // 0x58
	private List`1 _slotLightItemAnimList; // 0x60
	private CanvasGroup _canvasMeldingBtnGray; // 0x68
	private CanvasGroup _canvasMeldingBtnNormal; // 0x70
	private Slider _sliderSlot; // 0x78
	private Slider _sliderInputMeldingProgress; // 0x80
	private Slider _sliderMeldingProgress; // 0x88
	private GameObject _objFastInputBtn; // 0x90
	private GameObject _objClearAllInputBtn; // 0x98
	private GameObject _objBlockerQuickInput; // 0xa0
	private UIAnimationLocation _gachaBoxSwitchAnim; // 0xa8
	private UIAnimationLocation _slotSwitchAnim; // 0xb8
	private Image _imgTotum1; // 0xc8
	private Image _imgTotum2; // 0xd0
	private UICommonPageEffectHolder _effectMeldingGlowingHolder; // 0xd8
	private UICommonPageEffectHolder _effectMeldingTailHolder; // 0xe0
	private Act24sideMeldingViewModel m_model; // 0xe8
	private MeldingDetailAdapter m_meldingDetailAdapter; // 0xf0
	private MeldingSimpleAdapter m_meldingSimpleAdapter; // 0xf8
	private Boolean m_hasInited; // 0x100
	private Boolean m_isChoosing; // 0x101
	private String m_cachedCurGachaBoxId; // 0x108
	private Boolean m_isGachaGroup1Scrolled; // 0x110
	private Boolean m_isGachaGroup2Scrolled; // 0x111
	private FadeTranslationSwitchTween m_contentDetailTween; // 0x118
	private Boolean m_isSwitchBoxAnimFastMode; // 0x120
	private GachaBoxSwitchTween m_switchBoxTween; // 0x128
	private UIStateFinder m_finder; // 0x130
	private Boolean m_isMeldingInputProgressAnimFastMode; // 0x140
	private MeldingProgressSwitchTween m_meldingInputProgressTween; // 0x148
	private Int32 m_cachedInputMeldingPrice; // 0x150
	private Sequence m_cachedMeldingSucTween; // 0x158
	private Sequence m_cachedMeldingSucGlowingTween; // 0x160
	private Material m_matTotum1; // 0x168
	private Material m_matTotum2; // 0x170
	private TweenWrapper m_progressTween; // 0x178
	private List`1 m_progressSlotLightTweenList; // 0x180
	private TweenWrapper m_gachaBoxSwitchTween; // 0x188
	private FadeSwitchTween m_meldBtnGrayTween; // 0x190
	private FadeSwitchTween m_meldBtnNormalTween; // 0x198
	private UIPage m_page; // 0x1a0
	private const Single SWITCH_GACHA_ANIM_DURATION; // 0x0
	private const Single SLOT_LIGHT_UP_ANIM_DURATION; // 0x0
	private const Single SLOT_SWITCH_ANIM_DURATION; // 0x0
	private const Single TOTEM_SHOW_START_TIME; // 0x0
	private const Single TOTEM_SHOW_DURATION; // 0x0
	private const Single TOTEM_HIDE_DURATION; // 0x0
	private const String TOTEM_MAT_AMOUNT_NAME; // 0x0
	private const Single TOTEM_SHOW_AMOUNT; // 0x0
	private const Single TOTEM_HIDE_AMOUNT; // 0x0
	private const String FORMAT_MELDING_COUNT; // 0x0
	private const Single MELDING_SUC_GLOWING_ANIM_DUR; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_InitView; // 0x8
	private static DelegateBridge __Hotfix0_TryScrollGachaBoxToRemainCountRarePart; // 0x10
	private static DelegateBridge __Hotfix0_TryPlayMeldingSucSequnce; // 0x18
	private static DelegateBridge __Hotfix0_TryPauseInputProgressTweening; // 0x20
	private static DelegateBridge __Hotfix0_ClearMeldingSucSeq; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__PlaySwitchGachaBoxAnim; // 0x38
	private static DelegateBridge __Hotfix0__InitGachaBoxes; // 0x40
	private static DelegateBridge __Hotfix0__RenderGachaBoxes; // 0x48
	private static DelegateBridge __Hotfix0__TryScrollGachasToProperLine; // 0x50
	private static DelegateBridge __Hotfix0__PlayGachaBoxAndSlotSwitchAnim; // 0x58
	private static DelegateBridge __Hotfix0__PlayInputMeldingProgressSwitchAnim; // 0x60
	private static DelegateBridge __Hotfix0__ClearInputCache; // 0x68
	private static DelegateBridge __Hotfix0__TryPlayMeldingSucProgressSeq; // 0x70
	private static DelegateBridge __Hotfix0__IsInputProgressTweening; // 0x78
	private static DelegateBridge __Hotfix0__IsSwitchBoxTweening; // 0x80
	private static DelegateBridge __Hotfix0__SetQuickInputBlockShow; // 0x88
	private static DelegateBridge __Hotfix0__TryQuickInputMeldings; // 0x90
	private static DelegateBridge __Hotfix0_EventOnSwitchGachaPool; // 0x98
	private static DelegateBridge __Hotfix0_EventOnFastInput; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnClearAllInput; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnChoiceDetailShow; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnChoiceDetailHide; // 0xb8
	private static DelegateBridge __Hotfix0_EventOnMeldClick; // 0xc0
	private static DelegateBridge __Hotfix0_EventOnQuickInputClick; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0


	// RVA: 0x32a727c VA: 0x75958bf27c
	public override Void OnValueChanged(Act24sideMeldingProperty property) { }
	// RVA: 0x32a3af8 VA: 0x75958bbaf8
	public Void InitView(UIPage page) { }
	// RVA: 0x32a4470 VA: 0x75958bc470
	public Void TryScrollGachaBoxToRemainCountRarePart() { }
	// RVA: 0x32a7088 VA: 0x75958bf088
	public Single TryPlayMeldingSucSequnce(String gachaBoxId, List`1 changeInfoList) { }
	// RVA: 0x32a5eac VA: 0x75958bdeac
	public Void TryPauseInputProgressTweening() { }
	// RVA: 0x32a7114 VA: 0x75958bf114
	public Void ClearMeldingSucSeq() { }
	// RVA: 0x32a74d4 VA: 0x75958bf4d4
	private Void _InitIfNot() { }
	// RVA: 0x32a7b38 VA: 0x75958bfb38
	private Void _PlaySwitchGachaBoxAnim(Boolean isFirst, Boolean isFastMode) { }
	// RVA: 0x32a84a0 VA: 0x75958c04a0
	private Void _InitGachaBoxes() { }
	// RVA: 0x32a7964 VA: 0x75958bf964
	private Void _RenderGachaBoxes() { }
	// RVA: 0x32a7dc0 VA: 0x75958bfdc0
	private Void _TryScrollGachasToProperLine() { }
	// RVA: 0x32a87dc VA: 0x75958c07dc
	private Void _PlayGachaBoxAndSlotSwitchAnim(Boolean isShow, Boolean isFastMode) { }
	// RVA: 0x32a7c30 VA: 0x75958bfc30
	private Void _PlayInputMeldingProgressSwitchAnim(Boolean isFastMode) { }
	// RVA: 0x32a7d4c VA: 0x75958bfd4c
	private Void _ClearInputCache() { }
	// RVA: 0x32a7f34 VA: 0x75958bff34
	private Single _TryPlayMeldingSucProgressSeq(String gachaId, List`1 changeInfoList) { }
	// RVA: 0x32a839c VA: 0x75958c039c
	private Boolean _IsInputProgressTweening() { }
	// RVA: 0x32a9608 VA: 0x75958c1608
	private Boolean _IsSwitchBoxTweening() { }
	// RVA: 0x32a7cc8 VA: 0x75958bfcc8
	private Void _SetQuickInputBlockShow(Boolean show) { }
	// RVA: 0x32a968c VA: 0x75958c168c
	private Void _TryQuickInputMeldings() { }
	// RVA: 0x32a971c VA: 0x75958c171c
	public Void EventOnSwitchGachaPool() { }
	// RVA: 0x32a97d0 VA: 0x75958c17d0
	public Void EventOnFastInput() { }
	// RVA: 0x32a98d8 VA: 0x75958c18d8
	public Void EventOnClearAllInput() { }
	// RVA: 0x32a998c VA: 0x75958c198c
	public Void EventOnChoiceDetailShow() { }
	// RVA: 0x32a9a90 VA: 0x75958c1a90
	public Void EventOnChoiceDetailHide() { }
	// RVA: 0x32a9b94 VA: 0x75958c1b94
	public Void EventOnMeldClick() { }
	// RVA: 0x32a9c9c VA: 0x75958c1c9c
	public Void EventOnQuickInputClick() { }
	// RVA: 0x32a9d04 VA: 0x75958c1d04
	public Void .ctor() { }
	// RVA: 0x32a9d94 VA: 0x75958c1d94
	private Void <_TryPlayMeldingSucProgressSeq>b__77_2(Single val) { }
	// RVA: 0x32a9db8 VA: 0x75958c1db8
	private Void <_TryPlayMeldingSucProgressSeq>b__77_0() { }
}
```