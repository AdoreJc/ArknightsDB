# SiracusaCharSelectView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIAtlasImage _imgBgTintTheme`

- `UIAtlasImage _imgBgGradientTheme`

- `GameObject _objStateActive`

- `UIAVGCharacter _avgChar`

- `Text _txtCharName`

- `UIDynImage _imgCharEspName`

- `GameObject _objCharUnknown`

- `Text _txtCharDesActive`

- `ScrollRect _scrollViewCharInfo`

- `Text _txtCharInfo`

- `GameObject _rewardListGo`

- `GameObject _objRewardClear`

- `SimpleLayoutContent _layoutRewardsPreview`

- `GameObject _objStateEmpty`

- `RectTransform _transHeadHighLight`

- `GameObject _objStateUnknown`

- `GameObject _objStateConfirm`

- `UIAtlasImage _imgConfirmBtnTheme`

- `GameObject _objStateSelected`

- `GameObject _objCharQuit`

- `GameObject _objBtnCharAction`

- `GameObject _objCompleted`

- `UIAtlasImage _imgReviewBtnTheme`

- `CanvasGroup _canvasRewardsDetail`

- `ScrollRect _scrollViewRewardsDetail`

- `SimpleLayoutContent _layoutRewardsSpecial`

- `SimpleLayoutContent _layoutRewardsNormal`

- `GameObject _objRewardsSpecialGroup`

- `GameObject _objRewardsNormalGroup`

- `SimpleLayoutContent _layoutCharCards`

- `AnimationWrapper _switchAnimWrapper`

- `AnimationWrapper _selectCharAnimWrapper`

- `AnimationWrapper _unloadAnimWrapper`

- `Boolean m_hasInited`

- `FadeSwitchTween m_rewardsDetailTween`

- `RewardAdapter m_rewardPreviewAdapter`

- `RewardAdapter m_rewardDetailSpecialAdapter`

- `RewardAdapter m_rewardDetailNormalAdapter`

- `CharCardAdapter m_charCardsAdapter`

- `AutoPackSpriteHub m_charItalyNameSpriteHub`

- `SiracusaCharSelectViewModel m_viewModel`

- `SiracusaCharSelectItemViewModel m_choosingItemViewModel`

- `String m_choosingCharId`

- `AutoPackSpriteHub m_charCardSpriteHub`

- `Single m_charCardCeilSize`

- `Coroutine m_coCharHighLight`

- `SiracusaMapController m_controller`

- `Boolean <isRewardsDetailShowing>k__BackingField`

- `Action <eventQuitCharCard>k__BackingField`


## Properties

- `Boolean isRewardsDetailShowing`

- `Action eventQuitCharCard`


## Methods

- `Boolean get_isRewardsDetailShowing()`

- `Void set_isRewardsDetailShowing(Boolean)`

- `Void set_eventCharCardSwitch(Action`1)`

- `Action get_eventQuitCharCard()`

- `Void set_eventQuitCharCard(Action)`

- `Void set_eventReview(Action`1)`

- `Void set_eventSelectCharCard(Action`1)`

- `Void _InitIfNot()`

- `Void _ResetAnims()`

- `Void _InitSwitchAnim()`

- `Void _PlaySwitchAnim()`

- `Void _InitUnloadAnim()`

- `Void _PlayUnloadAnim()`

- `Void _InitSelectCharCardAnim()`

- `Void _PlaySelectCharCardAnim()`

- `Void _Render(SiracusaCharSelectViewModel)`

- `Boolean _CheckIfSelectChange()`

- `Void _RenderTheme(SiracusaCharSelectItemViewModel)`

- `Void _RenderCharInfo(SiracusaCharSelectItemViewModel, Boolean, Boolean)`

- `Void _RenderCharCardRewardList(SiracusaCharSelectItemViewModel, Boolean)`

- `Void _RenderCharCardList()`

- `Void _RenderCharChoosingHighLight(SiracusaCharSelectItemViewModel)`

- `IEnumerator _CoRenderCharChoosingHighLight(SiracusaCharSelectItemViewModel)`

- `Void _RenderChoosingHighLight(SiracusaCharSelectItemViewModel)`

- `Void _TryCoPlayHighLightAnimWhenEnterView(SiracusaCharSelectItemViewModel)`

- `Void _TryStopCoroutineChoosingHighLight()`

- `Void _RefreshHeadHighLightPos(Int32)`

- `Void _ResetDetailRewardsPopView()`

- `Void _ShowDetailRewardsPopView(SiracusaCharSelectItemViewModel, Boolean)`

- `String _GetItalyNameSpritePath(String)`

- `Void Init(SiracusaMapController)`

- `Void CloseDetailRewardsPopView()`

- `Void OnRewardDetailCloseClick()`

- `Void OnRewardDetailClick()`

- `Void OnSelectConfirmClick()`

- `Void OnCharQuitClick()`

- `Void OnReviewClick()`

- `Void _OnCharCardItemClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectView : DataBinder`1
{
	private UIAtlasImage _imgBgTintTheme; // 0x20
	private UIAtlasImage _imgBgGradientTheme; // 0x28
	private GameObject _objStateActive; // 0x30
	private UIAVGCharacter _avgChar; // 0x38
	private Text _txtCharName; // 0x40
	private UIDynImage _imgCharEspName; // 0x48
	private GameObject _objCharUnknown; // 0x50
	private Text _txtCharDesActive; // 0x58
	private ScrollRect _scrollViewCharInfo; // 0x60
	private Text _txtCharInfo; // 0x68
	private GameObject _rewardListGo; // 0x70
	private GameObject _objRewardClear; // 0x78
	private SimpleLayoutContent _layoutRewardsPreview; // 0x80
	private GameObject _objStateEmpty; // 0x88
	private RectTransform _transHeadHighLight; // 0x90
	private GameObject _objStateUnknown; // 0x98
	private GameObject _objStateConfirm; // 0xa0
	private UIAtlasImage _imgConfirmBtnTheme; // 0xa8
	private GameObject _objStateSelected; // 0xb0
	private GameObject _objCharQuit; // 0xb8
	private GameObject _objBtnCharAction; // 0xc0
	private GameObject _objCompleted; // 0xc8
	private UIAtlasImage _imgReviewBtnTheme; // 0xd0
	private CanvasGroup _canvasRewardsDetail; // 0xd8
	private ScrollRect _scrollViewRewardsDetail; // 0xe0
	private SimpleLayoutContent _layoutRewardsSpecial; // 0xe8
	private SimpleLayoutContent _layoutRewardsNormal; // 0xf0
	private GameObject _objRewardsSpecialGroup; // 0xf8
	private GameObject _objRewardsNormalGroup; // 0x100
	private SimpleLayoutContent _layoutCharCards; // 0x108
	private AnimationWrapper _switchAnimWrapper; // 0x110
	private AnimationWrapper _selectCharAnimWrapper; // 0x118
	private AnimationWrapper _unloadAnimWrapper; // 0x120
	private Boolean m_hasInited; // 0x128
	private FadeSwitchTween m_rewardsDetailTween; // 0x130
	private RewardAdapter m_rewardPreviewAdapter; // 0x138
	private RewardAdapter m_rewardDetailSpecialAdapter; // 0x140
	private RewardAdapter m_rewardDetailNormalAdapter; // 0x148
	private CharCardAdapter m_charCardsAdapter; // 0x150
	private AutoPackSpriteHub m_charItalyNameSpriteHub; // 0x158
	private SiracusaCharSelectViewModel m_viewModel; // 0x160
	private SiracusaCharSelectItemViewModel m_choosingItemViewModel; // 0x168
	private String m_choosingCharId; // 0x170
	private AutoPackSpriteHub m_charCardSpriteHub; // 0x178
	private Single m_charCardCeilSize; // 0x180
	private Coroutine m_coCharHighLight; // 0x188
	private SiracusaMapController m_controller; // 0x190
	private const String SWITCH_ANIM; // 0x0
	private const String CHAR_HIGH_LIGHT_ANIM; // 0x0
	private const String UNLOAD_ANIM; // 0x0
	private const Single ENTER_VIEW_CHOOSING_HIGH_LIGHT_WAIT_TIME; // 0x0
	private Boolean <isRewardsDetailShowing>k__BackingField; // 0x198
	private Action`1 <eventCharCardSwitch>k__BackingField; // 0x1a0
	private Action <eventQuitCharCard>k__BackingField; // 0x1a8
	private Action`1 <eventReview>k__BackingField; // 0x1b0
	private Action`1 <eventSelectCharCard>k__BackingField; // 0x1b8
	private static DelegateBridge __Hotfix0_get_isRewardsDetailShowing; // 0x0
	private static DelegateBridge __Hotfix0_set_isRewardsDetailShowing; // 0x8
	private static DelegateBridge __Hotfix0_get_eventCharCardSwitch; // 0x10
	private static DelegateBridge __Hotfix0_set_eventCharCardSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_eventQuitCharCard; // 0x20
	private static DelegateBridge __Hotfix0_set_eventQuitCharCard; // 0x28
	private static DelegateBridge __Hotfix0_get_eventReview; // 0x30
	private static DelegateBridge __Hotfix0_set_eventReview; // 0x38
	private static DelegateBridge __Hotfix0_get_eventSelectCharCard; // 0x40
	private static DelegateBridge __Hotfix0_set_eventSelectCharCard; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__ResetAnims; // 0x58
	private static DelegateBridge __Hotfix0__InitSwitchAnim; // 0x60
	private static DelegateBridge __Hotfix0__PlaySwitchAnim; // 0x68
	private static DelegateBridge __Hotfix0__InitUnloadAnim; // 0x70
	private static DelegateBridge __Hotfix0__PlayUnloadAnim; // 0x78
	private static DelegateBridge __Hotfix0__InitSelectCharCardAnim; // 0x80
	private static DelegateBridge __Hotfix0__PlaySelectCharCardAnim; // 0x88
	private static DelegateBridge __Hotfix0__Render; // 0x90
	private static DelegateBridge __Hotfix0__CheckIfSelectChange; // 0x98
	private static DelegateBridge __Hotfix0__RenderTheme; // 0xa0
	private static DelegateBridge __Hotfix0__RenderCharInfo; // 0xa8
	private static DelegateBridge __Hotfix0__RenderCharCardRewardList; // 0xb0
	private static DelegateBridge __Hotfix0__RenderCharCardList; // 0xb8
	private static DelegateBridge __Hotfix0__RenderCharChoosingHighLight; // 0xc0
	private static DelegateBridge __Hotfix0__CoRenderCharChoosingHighLight; // 0xc8
	private static DelegateBridge __Hotfix0__RenderChoosingHighLight; // 0xd0
	private static DelegateBridge __Hotfix0__TryCoPlayHighLightAnimWhenEnterView; // 0xd8
	private static DelegateBridge __Hotfix0__TryStopCoroutineChoosingHighLight; // 0xe0
	private static DelegateBridge __Hotfix0__RefreshHeadHighLightPos; // 0xe8
	private static DelegateBridge __Hotfix0__ResetDetailRewardsPopView; // 0xf0
	private static DelegateBridge __Hotfix0__ShowDetailRewardsPopView; // 0xf8
	private static DelegateBridge __Hotfix0__GetItalyNameSpritePath; // 0x100
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x108
	private static DelegateBridge __Hotfix0_Init; // 0x110
	private static DelegateBridge __Hotfix0_CloseDetailRewardsPopView; // 0x118
	private static DelegateBridge __Hotfix0_OnRewardDetailCloseClick; // 0x120
	private static DelegateBridge __Hotfix0_OnRewardDetailClick; // 0x128
	private static DelegateBridge __Hotfix0_OnSelectConfirmClick; // 0x130
	private static DelegateBridge __Hotfix0_OnCharQuitClick; // 0x138
	private static DelegateBridge __Hotfix0_OnReviewClick; // 0x140
	private static DelegateBridge __Hotfix0__OnCharCardItemClick; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public Boolean isRewardsDetailShowing { get; set; }
	public Action`1 eventCharCardSwitch { get; set; }
	public Action eventQuitCharCard { get; set; }
	public Action`1 eventReview { get; set; }
	public Action`1 eventSelectCharCard { get; set; }

	// RVA: 0x23efcbc VA: 0x7594a07cbc
	public Boolean get_isRewardsDetailShowing() { }
	// RVA: 0x23f09a0 VA: 0x7594a089a0
	private Void set_isRewardsDetailShowing(Boolean value) { }
	// RVA: 0x23f0a20 VA: 0x7594a08a20
	public Action`1 get_eventCharCardSwitch() { }
	// RVA: 0x23ef8c8 VA: 0x7594a078c8
	public Void set_eventCharCardSwitch(Action`1 value) { }
	// RVA: 0x23f0a88 VA: 0x7594a08a88
	public Action get_eventQuitCharCard() { }
	// RVA: 0x23ef9d0 VA: 0x7594a079d0
	public Void set_eventQuitCharCard(Action value) { }
	// RVA: 0x23f0af0 VA: 0x7594a08af0
	public Action`1 get_eventReview() { }
	// RVA: 0x23ef94c VA: 0x7594a0794c
	public Void set_eventReview(Action`1 value) { }
	// RVA: 0x23f0b58 VA: 0x7594a08b58
	public Action`1 get_eventSelectCharCard() { }
	// RVA: 0x23efa54 VA: 0x7594a07a54
	public Void set_eventSelectCharCard(Action`1 value) { }
	// RVA: 0x23f0bc0 VA: 0x7594a08bc0
	private Void _InitIfNot() { }
	// RVA: 0x23f0ec0 VA: 0x7594a08ec0
	private Void _ResetAnims() { }
	// RVA: 0x23f0fc4 VA: 0x7594a08fc4
	private Void _InitSwitchAnim() { }
	// RVA: 0x23f1060 VA: 0x7594a09060
	private Void _PlaySwitchAnim() { }
	// RVA: 0x23f1140 VA: 0x7594a09140
	private Void _InitUnloadAnim() { }
	// RVA: 0x23f11dc VA: 0x7594a091dc
	private Void _PlayUnloadAnim() { }
	// RVA: 0x23f0f28 VA: 0x7594a08f28
	private Void _InitSelectCharCardAnim() { }
	// RVA: 0x23f12bc VA: 0x7594a092bc
	private Void _PlaySelectCharCardAnim() { }
	// RVA: 0x23f1358 VA: 0x7594a09358
	private Void _Render(SiracusaCharSelectViewModel viewModel) { }
	// RVA: 0x23f1774 VA: 0x7594a09774
	private Boolean _CheckIfSelectChange() { }
	// RVA: 0x23f15c8 VA: 0x7594a095c8
	private Void _RenderTheme(SiracusaCharSelectItemViewModel viewModel) { }
	// RVA: 0x23f18c0 VA: 0x7594a098c0
	private Void _RenderCharInfo(SiracusaCharSelectItemViewModel viewModel, Boolean selectChanged, Boolean isRetro) { }
	// RVA: 0x23f1ff4 VA: 0x7594a09ff4
	private Void _RenderCharCardRewardList(SiracusaCharSelectItemViewModel viewModel, Boolean isRetro) { }
	// RVA: 0x23f1cf8 VA: 0x7594a09cf8
	private Void _RenderCharCardList() { }
	// RVA: 0x23f21d0 VA: 0x7594a0a1d0
	private Void _RenderCharChoosingHighLight(SiracusaCharSelectItemViewModel viewModel) { }
	// RVA: 0x23f23b0 VA: 0x7594a0a3b0
	private IEnumerator _CoRenderCharChoosingHighLight(SiracusaCharSelectItemViewModel viewModel) { }
	// RVA: 0x23f1d70 VA: 0x7594a09d70
	private Void _RenderChoosingHighLight(SiracusaCharSelectItemViewModel choosingViewModel) { }
	// RVA: 0x23f24a8 VA: 0x7594a0a4a8
	private Void _TryCoPlayHighLightAnimWhenEnterView(SiracusaCharSelectItemViewModel choosingViewModel) { }
	// RVA: 0x23f25d8 VA: 0x7594a0a5d8
	private Void _TryStopCoroutineChoosingHighLight() { }
	// RVA: 0x23f22a4 VA: 0x7594a0a2a4
	private Void _RefreshHeadHighLightPos(Int32 index) { }
	// RVA: 0x23f1464 VA: 0x7594a09464
	private Void _ResetDetailRewardsPopView() { }
	// RVA: 0x23f26f0 VA: 0x7594a0a6f0
	private Void _ShowDetailRewardsPopView(SiracusaCharSelectItemViewModel viewModel, Boolean show) { }
	// RVA: 0x23f1f04 VA: 0x7594a09f04
	private String _GetItalyNameSpritePath(String charCardId) { }
	// RVA: 0x23f28c4 VA: 0x7594a0a8c4
	public override Void OnValueChanged(SiracusaCharSelectProperty property) { }
	// RVA: 0x23eef30 VA: 0x7594a06f30
	public Void Init(SiracusaMapController controller) { }
	// RVA: 0x23efd24 VA: 0x7594a07d24
	public Void CloseDetailRewardsPopView() { }
	// RVA: 0x23f297c VA: 0x7594a0a97c
	public Void OnRewardDetailCloseClick() { }
	// RVA: 0x23f29e4 VA: 0x7594a0a9e4
	public Void OnRewardDetailClick() { }
	// RVA: 0x23f2a54 VA: 0x7594a0aa54
	public Void OnSelectConfirmClick() { }
	// RVA: 0x23f2b18 VA: 0x7594a0ab18
	public Void OnCharQuitClick() { }
	// RVA: 0x23f2bc0 VA: 0x7594a0abc0
	public Void OnReviewClick() { }
	// RVA: 0x23f2c70 VA: 0x7594a0ac70
	private Void _OnCharCardItemClick(String charCardId) { }
	// RVA: 0x23f2d28 VA: 0x7594a0ad28
	public Void .ctor() { }
}
```