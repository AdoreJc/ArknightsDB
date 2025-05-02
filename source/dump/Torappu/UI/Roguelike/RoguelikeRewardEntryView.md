# RoguelikeRewardEntryView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _imageBackground`

- `Text _stageName`

- `RectTransform _rect`

- `Transform _illustCont`

- `AVGTypeWriterText _illustText`

- `GameObject _illustTextPanel`

- `GameObject _panelTextSuccess`

- `GameObject _panelTextFail`

- `UIAnimationLocation _animationLocationEntry`

- `GameObject _hpPart`

- `GameObject _hpNormPart`

- `Text _currentHP`

- `GameObject _hpLoseImg`

- `GameObject _hpWithMaxPart`

- `Text _currentHpWithMax`

- `Text _currentMaxHp`

- `GameObject _hpWithMaxLoseImg`

- `Text _minusHP`

- `CanvasGroup _noHpLosePart`

- `RectTransform _perfectItemHolder`

- `CanvasGroup _hpLosePart`

- `GameObject _shieldPart`

- `GameObject _shieldLoseBg`

- `Text _currentShield`

- `Text _textHpLoseTitle`

- `AnimationWrapper _hpAnimationWrapper`

- `RLRewardEntryLevelPartView _normalLevelPartView`

- `RectTransform _spLevelPartContainer`

- `AnimationWrapper _popAddAnimationWrapper`

- `GameObject _popAddObj`

- `RoguelikePopBarView _barView`

- `RoguelikeRewardStyle <uiStyle>k__BackingField`

- `RoguelikeRewardPerfectItemView m_perfectItemView`

- `Boolean m_isRendered`

- `GameObject m_cacheView`

- `String m_illustWord`

- `RLRewardEntryLevelPartView m_spLevelPartPrefab`

- `RLRewardEntryLevelPartView m_levelPartView`

- `Boolean isEffectFinishFlag`

- `Boolean m_inited`

- `Tween m_effectTween`

- `Boolean isHpNoLoseShowFar`

- `UIStateFinder m_finder`

- `RoguelikeRewardState <bindRewardState>k__BackingField`

- `RectTransform _hpDecoHolder`

- `HpBarDecorationView m_hpDecorationView`


## Properties

- `RoguelikeRewardStyle uiStyle`

- `RoguelikeRewardState bindRewardState`


## Methods

- `RoguelikeRewardStyle get_uiStyle()`

- `Void set_uiStyle(RoguelikeRewardStyle)`

- `RoguelikeRewardState get_bindRewardState()`

- `Void set_bindRewardState(RoguelikeRewardState)`

- `Void _InitIfNot(String)`

- `Void _RenderInitPart(RenderParam)`

- `Void _RenderDelta(RenderParam)`

- `IEnumerator EffectPart(RenderParam)`

- `HpBarDecorationView _LoadHpDeco(String, UIStateFinder)`

- `CharWordShowType _ShowWhichCharWord(RoguelikeGameStageData, RoguelikeRewardEarnViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardEntryView : DataBinder`1
{
	private Image _imageBackground; // 0x20
	private Text _stageName; // 0x28
	private RectTransform _rect; // 0x30
	private Transform _illustCont; // 0x38
	private AVGTypeWriterText _illustText; // 0x40
	private GameObject _illustTextPanel; // 0x48
	private GameObject _panelTextSuccess; // 0x50
	private GameObject _panelTextFail; // 0x58
	private UIAnimationLocation _animationLocationEntry; // 0x60
	private GameObject _hpPart; // 0x70
	private GameObject _hpNormPart; // 0x78
	private Text _currentHP; // 0x80
	private GameObject _hpLoseImg; // 0x88
	private GameObject _hpWithMaxPart; // 0x90
	private Text _currentHpWithMax; // 0x98
	private Text _currentMaxHp; // 0xa0
	private GameObject _hpWithMaxLoseImg; // 0xa8
	private Text _minusHP; // 0xb0
	private CanvasGroup _noHpLosePart; // 0xb8
	private RectTransform _perfectItemHolder; // 0xc0
	private CanvasGroup _hpLosePart; // 0xc8
	private GameObject _shieldPart; // 0xd0
	private GameObject _shieldLoseBg; // 0xd8
	private Text _currentShield; // 0xe0
	private Text _textHpLoseTitle; // 0xe8
	private AnimationWrapper _hpAnimationWrapper; // 0xf0
	private RLRewardEntryLevelPartView _normalLevelPartView; // 0xf8
	private RectTransform _spLevelPartContainer; // 0x100
	private AnimationWrapper _popAddAnimationWrapper; // 0x108
	private GameObject _popAddObj; // 0x110
	private RoguelikePopBarView _barView; // 0x118
	private RoguelikeRewardStyle <uiStyle>k__BackingField; // 0x120
	private RoguelikeRewardPerfectItemView m_perfectItemView; // 0x128
	private Boolean m_isRendered; // 0x130
	private GameObject m_cacheView; // 0x138
	private String m_illustWord; // 0x140
	private RLRewardEntryLevelPartView m_spLevelPartPrefab; // 0x148
	private RLRewardEntryLevelPartView m_levelPartView; // 0x150
	public Boolean isEffectFinishFlag; // 0x158
	private Boolean m_inited; // 0x159
	private Tween m_effectTween; // 0x160
	private Boolean isHpNoLoseShowFar; // 0x168
	private const Single CONST_ALPHA; // 0x0
	private const Single INIT_HEIGHT; // 0x0
	private const Single TARGET_HEIGHT; // 0x0
	private const Single HP_NO_LOSE_POS_1; // 0x0
	private const Single HP_NO_LOSE_POS_2; // 0x0
	private const Int32 OBJ_BEFORE_HP_NO_LOSE; // 0x0
	private UIStateFinder m_finder; // 0x170
	private RoguelikeRewardState <bindRewardState>k__BackingField; // 0x180
	private RectTransform _hpDecoHolder; // 0x188
	private HpBarDecorationView m_hpDecorationView; // 0x190
	private static DelegateBridge __Hotfix0_get_uiStyle; // 0x0
	private static DelegateBridge __Hotfix0_set_uiStyle; // 0x8
	private static DelegateBridge __Hotfix0_get_bindRewardState; // 0x10
	private static DelegateBridge __Hotfix0_set_bindRewardState; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__RenderInitPart; // 0x28
	private static DelegateBridge __Hotfix0__RenderDelta; // 0x30
	private static DelegateBridge __Hotfix0_EffectPart; // 0x38
	private static DelegateBridge __Hotfix0__LoadHpDeco; // 0x40
	private static DelegateBridge __Hotfix0__ShowWhichCharWord; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public RoguelikeRewardStyle uiStyle { get; set; }
	private RoguelikeRewardState bindRewardState { get; set; }

	// RVA: 0x2a96afc VA: 0x75950aeafc
	public RoguelikeRewardStyle get_uiStyle() { }
	// RVA: 0x2a93da4 VA: 0x75950abda4
	public Void set_uiStyle(RoguelikeRewardStyle value) { }
	// RVA: 0x2a96b64 VA: 0x75950aeb64
	private RoguelikeRewardState get_bindRewardState() { }
	// RVA: 0x2a93e28 VA: 0x75950abe28
	public Void set_bindRewardState(RoguelikeRewardState value) { }
	// RVA: 0x2a96bcc VA: 0x75950aebcc
	private Void _InitIfNot(String topicId) { }
	// RVA: 0x2a97074 VA: 0x75950af074
	private Void _RenderInitPart(RenderParam renderParam) { }
	// RVA: 0x2a97f78 VA: 0x75950aff78
	private Void _RenderDelta(RenderParam renderParam) { }
	// RVA: 0x2a98150 VA: 0x75950b0150
	private IEnumerator EffectPart(RenderParam renderParam) { }
	// RVA: 0x2a96ef4 VA: 0x75950aeef4
	private HpBarDecorationView _LoadHpDeco(String topicId, UIStateFinder finder) { }
	// RVA: 0x2a97e90 VA: 0x75950afe90
	private CharWordShowType _ShowWhichCharWord(RoguelikeGameStageData stageData, RoguelikeRewardEarnViewModel earnViewModel, Boolean isPefectAndSuccessBattle) { }
	// RVA: 0x2a982fc VA: 0x75950b02fc
	public override Void OnValueChanged(RoguelikeRewardViewProperty property) { }
	// RVA: 0x2a98bf0 VA: 0x75950b0bf0
	public Void .ctor() { }
}
```