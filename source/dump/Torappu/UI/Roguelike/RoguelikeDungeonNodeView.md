# RoguelikeDungeonNodeView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeNodeViewData _viewData`

- `Settings _settings`

- `UIColorGraphic _colorGraphic`

- `AnimationWrapper _animationWrapper`

- `AnimationWrapper _curveAnimationWrapper`

- `AnimationWrapper _vertAnimationWrapper`

- `AnimationWrapper _connectorAnimationWrapper`

- `RoguelikeVerticalLine _vertLine`

- `RectTransform _panelFromConnectors`

- `RectTransform _panelToConnectors`

- `Image _imageBkg`

- `Image _imageSelectableBkg`

- `Image _imageBlurBkg`

- `Image _imageIcon`

- `Image _imageBoss`

- `Image _imageBossIcon`

- `Image _imageTag`

- `Image _panelColorDesc`

- `Image _panelBlackDesc`

- `RectTransform _panelNext`

- `ParticleSystem _particleSystem`

- `Text _textName`

- `Button _buttonSelf`

- `GameObject _haveLockedInfo`

- `Image _isBattleIcon`

- `RoguelikeDungeonNodePlugin _plugin`

- `RogueLogic _logic`

- `RoguelikeDungeonNode m_cacheNode`

- `String m_topicId`

- `Coroutine m_animCoroutine`

- `Boolean m_isBoss`

- `Boolean m_isFinalBoss`

- `Boolean m_isBattle`

- `Boolean m_isCurrent`

- `Boolean m_isDiscarded`

- `Boolean m_isFuture`

- `Boolean m_isSelectable`

- `Boolean m_needParticles`

- `Boolean m_isInTrace`

- `Boolean m_isLocked`

- `Color m_selectableColor`

- `Color m_bottomBarColor`

- `Boolean m_needToPlayVertUpAnim`

- `Boolean m_needToPlayVertDownAnim`

- `Boolean m_isInSpecialZone`

- `GameObject m_cacheParticle`

- `EffectCache m_effectCache`


## Properties

- `RoguelikeNodeViewData viewData`

- `Settings settings`

- `UIColorGraphic colorGraphic`

- `AnimationWrapper animationWrapper`

- `AnimationWrapper curveAnimationWrapper`

- `AnimationWrapper vertAnimationWrapper`

- `AnimationWrapper connectorAnimationWrapper`

- `RoguelikeVerticalLine vertLine`

- `RectTransform panelFromConnectors`

- `RectTransform panelToConnectors`

- `Image imageBkg`

- `Image imageSelectableBkg`

- `Image imageBlurBkg`

- `Image imageIcon`

- `Image imageBoss`

- `Image imageBossIcon`

- `Image imageTag`

- `Image panelColorDesc`

- `Image panelBlackDesc`

- `RectTransform panelNext`

- `ParticleSystem particleSystem`

- `Text textName`

- `Button buttonSelf`

- `GameObject haveLockedInfo`

- `Image isBattleIcon`

- `RoguelikeDungeonNode cacheNode`

- `String topicId`

- `Coroutine animCoroutine`

- `Boolean isBoss`

- `Boolean isFinalBoss`

- `Boolean isBattle`

- `Boolean isCurrent`

- `Boolean isDiscarded`

- `Boolean isFuture`

- `Boolean isSelectable`

- `Boolean needParticles`

- `Boolean isInTrace`

- `Boolean isLocked`

- `Color selectableColor`

- `Color bottomBarColor`

- `Boolean needToPlayVertUpAnim`

- `Boolean needToPlayVertDownAnim`

- `Boolean isInSpecialZone`

- `GameObject cacheParticle`

- `EffectCache effectCache`

- `Boolean isVisible`


## Methods

- `RoguelikeNodeViewData get_viewData()`

- `Settings get_settings()`

- `UIColorGraphic get_colorGraphic()`

- `AnimationWrapper get_animationWrapper()`

- `AnimationWrapper get_curveAnimationWrapper()`

- `AnimationWrapper get_vertAnimationWrapper()`

- `AnimationWrapper get_connectorAnimationWrapper()`

- `RoguelikeVerticalLine get_vertLine()`

- `RectTransform get_panelFromConnectors()`

- `RectTransform get_panelToConnectors()`

- `Image get_imageBkg()`

- `Image get_imageSelectableBkg()`

- `Image get_imageBlurBkg()`

- `Image get_imageIcon()`

- `Image get_imageBoss()`

- `Image get_imageBossIcon()`

- `Image get_imageTag()`

- `Image get_panelColorDesc()`

- `Image get_panelBlackDesc()`

- `RectTransform get_panelNext()`

- `ParticleSystem get_particleSystem()`

- `Text get_textName()`

- `Button get_buttonSelf()`

- `GameObject get_haveLockedInfo()`

- `Image get_isBattleIcon()`

- `RoguelikeDungeonNode get_cacheNode()`

- `String get_topicId()`

- `Coroutine get_animCoroutine()`

- `Boolean get_isBoss()`

- `Boolean get_isFinalBoss()`

- `Boolean get_isBattle()`

- `Boolean get_isCurrent()`

- `Boolean get_isDiscarded()`

- `Boolean get_isFuture()`

- `Boolean get_isSelectable()`

- `Boolean get_needParticles()`

- `Boolean get_isInTrace()`

- `Boolean get_isLocked()`

- `Color get_selectableColor()`

- `Color get_bottomBarColor()`

- `Boolean get_needToPlayVertUpAnim()`

- `Boolean get_needToPlayVertDownAnim()`

- `Boolean get_isInSpecialZone()`

- `GameObject get_cacheParticle()`

- `EffectCache get_effectCache()`

- `Void set_onClicked(Action`1)`

- `Void set_isVisible(Boolean)`

- `Void EventOnClicked()`

- `Void AnimationEventOnPlayParticle()`

- `RectTransform GetConnector(Boolean, Int32)`

- `RoguelikeVerticalLine GetVertLine()`

- `RoguelikeCurve GetCurve(Int32)`

- `Void Render(String, RoguelikeDungeonNode)`

- `Void _PreprocessData()`

- `Void _ResetAnim()`

- `Void ClearEffect()`

- `IEnumerator _UpdateAnim()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonNodeView : MonoBehaviour, IHotfixable
{
	private const String ANIM_CURRENT_NODE; // 0x0
	private const String ANIM_SELECTABLE_NODE; // 0x0
	private const String ANIM_CURVE; // 0x0
	private const String ANIM_VERTI_UP; // 0x0
	private const String ANIM_VERTI_DOWN; // 0x0
	private const String ANIM_CONNECTOR; // 0x0
	private RoguelikeNodeViewData _viewData; // 0x18
	private Settings _settings; // 0x20
	private UIColorGraphic _colorGraphic; // 0x28
	private AnimationWrapper _animationWrapper; // 0x30
	private AnimationWrapper _curveAnimationWrapper; // 0x38
	private AnimationWrapper _vertAnimationWrapper; // 0x40
	private AnimationWrapper _connectorAnimationWrapper; // 0x48
	private RoguelikeVerticalLine _vertLine; // 0x50
	private RectTransform _panelFromConnectors; // 0x58
	private RectTransform _panelToConnectors; // 0x60
	private List`1 _fromConnectors; // 0x68
	private List`1 _fromReflectConnectors; // 0x70
	private List`1 _toConnectors; // 0x78
	private List`1 _curves; // 0x80
	private Image _imageBkg; // 0x88
	private Image _imageSelectableBkg; // 0x90
	private Image _imageBlurBkg; // 0x98
	private Image _imageIcon; // 0xa0
	private Image _imageBoss; // 0xa8
	private Image _imageBossIcon; // 0xb0
	private Image _imageTag; // 0xb8
	private Image _panelColorDesc; // 0xc0
	private Image _panelBlackDesc; // 0xc8
	private RectTransform _panelNext; // 0xd0
	private ParticleSystem _particleSystem; // 0xd8
	private Text _textName; // 0xe0
	private Button _buttonSelf; // 0xe8
	private GameObject _haveLockedInfo; // 0xf0
	private Image _isBattleIcon; // 0xf8
	private RoguelikeDungeonNodePlugin _plugin; // 0x100
	private RogueLogic _logic; // 0x108
	private RoguelikeDungeonNode m_cacheNode; // 0x110
	private String m_topicId; // 0x118
	private Coroutine m_animCoroutine; // 0x120
	private Boolean m_isBoss; // 0x128
	private Boolean m_isFinalBoss; // 0x129
	private Boolean m_isBattle; // 0x12a
	private Boolean m_isCurrent; // 0x12b
	private Boolean m_isDiscarded; // 0x12c
	private Boolean m_isFuture; // 0x12d
	private Boolean m_isSelectable; // 0x12e
	private Boolean m_needParticles; // 0x12f
	private Boolean m_isInTrace; // 0x130
	private Boolean m_isLocked; // 0x131
	private Color m_selectableColor; // 0x134
	private Color m_bottomBarColor; // 0x144
	private Boolean m_needToPlayVertUpAnim; // 0x154
	private Boolean m_needToPlayVertDownAnim; // 0x155
	private Boolean m_isInSpecialZone; // 0x156
	private GameObject m_cacheParticle; // 0x158
	private EffectCache m_effectCache; // 0x160
	private Action`1 <onClicked>k__BackingField; // 0x168
	private static DelegateBridge __Hotfix0_get_viewData; // 0x0
	private static DelegateBridge __Hotfix0_get_settings; // 0x8
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x10
	private static DelegateBridge __Hotfix0_get_animationWrapper; // 0x18
	private static DelegateBridge __Hotfix0_get_curveAnimationWrapper; // 0x20
	private static DelegateBridge __Hotfix0_get_vertAnimationWrapper; // 0x28
	private static DelegateBridge __Hotfix0_get_connectorAnimationWrapper; // 0x30
	private static DelegateBridge __Hotfix0_get_vertLine; // 0x38
	private static DelegateBridge __Hotfix0_get_panelFromConnectors; // 0x40
	private static DelegateBridge __Hotfix0_get_panelToConnectors; // 0x48
	private static DelegateBridge __Hotfix0_get_fromConnectors; // 0x50
	private static DelegateBridge __Hotfix0_get_fromReflectConnectors; // 0x58
	private static DelegateBridge __Hotfix0_get_toConnectors; // 0x60
	private static DelegateBridge __Hotfix0_get_curves; // 0x68
	private static DelegateBridge __Hotfix0_get_imageBkg; // 0x70
	private static DelegateBridge __Hotfix0_get_imageSelectableBkg; // 0x78
	private static DelegateBridge __Hotfix0_get_imageBlurBkg; // 0x80
	private static DelegateBridge __Hotfix0_get_imageIcon; // 0x88
	private static DelegateBridge __Hotfix0_get_imageBoss; // 0x90
	private static DelegateBridge __Hotfix0_get_imageBossIcon; // 0x98
	private static DelegateBridge __Hotfix0_get_imageTag; // 0xa0
	private static DelegateBridge __Hotfix0_get_panelColorDesc; // 0xa8
	private static DelegateBridge __Hotfix0_get_panelBlackDesc; // 0xb0
	private static DelegateBridge __Hotfix0_get_panelNext; // 0xb8
	private static DelegateBridge __Hotfix0_get_particleSystem; // 0xc0
	private static DelegateBridge __Hotfix0_get_textName; // 0xc8
	private static DelegateBridge __Hotfix0_get_buttonSelf; // 0xd0
	private static DelegateBridge __Hotfix0_get_haveLockedInfo; // 0xd8
	private static DelegateBridge __Hotfix0_get_isBattleIcon; // 0xe0
	private static DelegateBridge __Hotfix0_get_cacheNode; // 0xe8
	private static DelegateBridge __Hotfix0_get_topicId; // 0xf0
	private static DelegateBridge __Hotfix0_get_animCoroutine; // 0xf8
	private static DelegateBridge __Hotfix0_get_isBoss; // 0x100
	private static DelegateBridge __Hotfix0_get_isFinalBoss; // 0x108
	private static DelegateBridge __Hotfix0_get_isBattle; // 0x110
	private static DelegateBridge __Hotfix0_get_isCurrent; // 0x118
	private static DelegateBridge __Hotfix0_get_isDiscarded; // 0x120
	private static DelegateBridge __Hotfix0_get_isFuture; // 0x128
	private static DelegateBridge __Hotfix0_get_isSelectable; // 0x130
	private static DelegateBridge __Hotfix0_get_needParticles; // 0x138
	private static DelegateBridge __Hotfix0_get_isInTrace; // 0x140
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x148
	private static DelegateBridge __Hotfix0_get_selectableColor; // 0x150
	private static DelegateBridge __Hotfix0_get_bottomBarColor; // 0x158
	private static DelegateBridge __Hotfix0_get_needToPlayVertUpAnim; // 0x160
	private static DelegateBridge __Hotfix0_get_needToPlayVertDownAnim; // 0x168
	private static DelegateBridge __Hotfix0_get_isInSpecialZone; // 0x170
	private static DelegateBridge __Hotfix0_get_cacheParticle; // 0x178
	private static DelegateBridge __Hotfix0_get_effectCache; // 0x180
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x188
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x190
	private static DelegateBridge __Hotfix0_set_isVisible; // 0x198
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x1a0
	private static DelegateBridge __Hotfix0_AnimationEventOnPlayParticle; // 0x1a8
	private static DelegateBridge __Hotfix0_GetConnector; // 0x1b0
	private static DelegateBridge __Hotfix0_GetVertLine; // 0x1b8
	private static DelegateBridge __Hotfix0_GetCurve; // 0x1c0
	private static DelegateBridge __Hotfix0_Render; // 0x1c8
	private static DelegateBridge __Hotfix0__PreprocessData; // 0x1d0
	private static DelegateBridge __Hotfix0_GetColorData; // 0x1d8
	private static DelegateBridge __Hotfix0__ResetAnim; // 0x1e0
	private static DelegateBridge __Hotfix0_RenderBossWidgets; // 0x1e8
	private static DelegateBridge __Hotfix0_RenderNonBossWidigets; // 0x1f0
	private static DelegateBridge __Hotfix0_ClearEffect; // 0x1f8
	private static DelegateBridge __Hotfix0_RenderVertLines; // 0x200
	private static DelegateBridge __Hotfix0_RenderCurves; // 0x208
	private static DelegateBridge __Hotfix0_RenderParticles; // 0x210
	private static DelegateBridge __Hotfix0_RenderOtherWidgets; // 0x218
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x220
	private static DelegateBridge __Hotfix0__UpdateAnim; // 0x228
	private static DelegateBridge __Hotfix0_OnDisable; // 0x230
	private static DelegateBridge _c__Hotfix0_ctor; // 0x238

	public RoguelikeNodeViewData viewData { get; }
	public Settings settings { get; }
	public UIColorGraphic colorGraphic { get; }
	public AnimationWrapper animationWrapper { get; }
	public AnimationWrapper curveAnimationWrapper { get; }
	public AnimationWrapper vertAnimationWrapper { get; }
	public AnimationWrapper connectorAnimationWrapper { get; }
	public RoguelikeVerticalLine vertLine { get; }
	public RectTransform panelFromConnectors { get; }
	public RectTransform panelToConnectors { get; }
	public List`1 fromConnectors { get; }
	public List`1 fromReflectConnectors { get; }
	public List`1 toConnectors { get; }
	public List`1 curves { get; }
	public Image imageBkg { get; }
	public Image imageSelectableBkg { get; }
	public Image imageBlurBkg { get; }
	public Image imageIcon { get; }
	public Image imageBoss { get; }
	public Image imageBossIcon { get; }
	public Image imageTag { get; }
	public Image panelColorDesc { get; }
	public Image panelBlackDesc { get; }
	public RectTransform panelNext { get; }
	public ParticleSystem particleSystem { get; }
	public Text textName { get; }
	public Button buttonSelf { get; }
	public GameObject haveLockedInfo { get; }
	public Image isBattleIcon { get; }
	public RoguelikeDungeonNode cacheNode { get; }
	public String topicId { get; }
	public Coroutine animCoroutine { get; }
	public Boolean isBoss { get; }
	public Boolean isFinalBoss { get; }
	public Boolean isBattle { get; }
	public Boolean isCurrent { get; }
	public Boolean isDiscarded { get; }
	public Boolean isFuture { get; }
	public Boolean isSelectable { get; }
	public Boolean needParticles { get; }
	public Boolean isInTrace { get; }
	public Boolean isLocked { get; }
	public Color selectableColor { get; }
	public Color bottomBarColor { get; }
	public Boolean needToPlayVertUpAnim { get; }
	public Boolean needToPlayVertDownAnim { get; }
	public Boolean isInSpecialZone { get; }
	public GameObject cacheParticle { get; }
	public EffectCache effectCache { get; }
	public Action`1 onClicked { get; set; }
	public Boolean isVisible { set; }

	// RVA: 0x2a0cd48 VA: 0x7595024d48
	public RoguelikeNodeViewData get_viewData() { }
	// RVA: 0x2a0d028 VA: 0x7595025028
	public Settings get_settings() { }
	// RVA: 0x2a0ecc8 VA: 0x7595026cc8
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x2a0ef4c VA: 0x7595026f4c
	public AnimationWrapper get_animationWrapper() { }
	// RVA: 0x2a0efb4 VA: 0x7595026fb4
	public AnimationWrapper get_curveAnimationWrapper() { }
	// RVA: 0x2a0f01c VA: 0x759502701c
	public AnimationWrapper get_vertAnimationWrapper() { }
	// RVA: 0x2a0f084 VA: 0x7595027084
	public AnimationWrapper get_connectorAnimationWrapper() { }
	// RVA: 0x2a0f0ec VA: 0x75950270ec
	public RoguelikeVerticalLine get_vertLine() { }
	// RVA: 0x2a0d090 VA: 0x7595025090
	public RectTransform get_panelFromConnectors() { }
	// RVA: 0x2a0d0f8 VA: 0x75950250f8
	public RectTransform get_panelToConnectors() { }
	// RVA: 0x2a0cc10 VA: 0x7595024c10
	public List`1 get_fromConnectors() { }
	// RVA: 0x2a0cdb0 VA: 0x7595024db0
	public List`1 get_fromReflectConnectors() { }
	// RVA: 0x2a0cf58 VA: 0x7595024f58
	public List`1 get_toConnectors() { }
	// RVA: 0x2a0cce0 VA: 0x7595024ce0
	public List`1 get_curves() { }
	// RVA: 0x2a0d644 VA: 0x7595025644
	public Image get_imageBkg() { }
	// RVA: 0x2a0d6ac VA: 0x75950256ac
	public Image get_imageSelectableBkg() { }
	// RVA: 0x2a0d714 VA: 0x7595025714
	public Image get_imageBlurBkg() { }
	// RVA: 0x2a0d77c VA: 0x759502577c
	public Image get_imageIcon() { }
	// RVA: 0x2a0d50c VA: 0x759502550c
	public Image get_imageBoss() { }
	// RVA: 0x2a0d574 VA: 0x7595025574
	public Image get_imageBossIcon() { }
	// RVA: 0x2a0d984 VA: 0x7595025984
	public Image get_imageTag() { }
	// RVA: 0x2a0d84c VA: 0x759502584c
	public Image get_panelColorDesc() { }
	// RVA: 0x2a0d7e4 VA: 0x75950257e4
	public Image get_panelBlackDesc() { }
	// RVA: 0x2a0e1a0 VA: 0x75950261a0
	public RectTransform get_panelNext() { }
	// RVA: 0x2a0f154 VA: 0x7595027154
	public ParticleSystem get_particleSystem() { }
	// RVA: 0x2a0d8b4 VA: 0x75950258b4
	public Text get_textName() { }
	// RVA: 0x2a0e138 VA: 0x7595026138
	public Button get_buttonSelf() { }
	// RVA: 0x2a0e270 VA: 0x7595026270
	public GameObject get_haveLockedInfo() { }
	// RVA: 0x2a0d91c VA: 0x759502591c
	public Image get_isBattleIcon() { }
	// RVA: 0x2a0cc78 VA: 0x7595024c78
	public RoguelikeDungeonNode get_cacheNode() { }
	// RVA: 0x2a0dc30 VA: 0x7595025c30
	public String get_topicId() { }
	// RVA: 0x2a0f1bc VA: 0x75950271bc
	public Coroutine get_animCoroutine() { }
	// RVA: 0x2a0cfc0 VA: 0x7595024fc0
	public Boolean get_isBoss() { }
	// RVA: 0x2a0d5dc VA: 0x75950255dc
	public Boolean get_isFinalBoss() { }
	// RVA: 0x2a0e208 VA: 0x7595026208
	public Boolean get_isBattle() { }
	// RVA: 0x2a0ce18 VA: 0x7595024e18
	public Boolean get_isCurrent() { }
	// RVA: 0x2a0ed30 VA: 0x7595026d30
	public Boolean get_isDiscarded() { }
	// RVA: 0x2a0ed98 VA: 0x7595026d98
	public Boolean get_isFuture() { }
	// RVA: 0x2a0ce80 VA: 0x7595024e80
	public Boolean get_isSelectable() { }
	// RVA: 0x2a0f224 VA: 0x7595027224
	public Boolean get_needParticles() { }
	// RVA: 0x2a0ec60 VA: 0x7595026c60
	public Boolean get_isInTrace() { }
	// RVA: 0x2a0e2d8 VA: 0x75950262d8
	public Boolean get_isLocked() { }
	// RVA: 0x2a0ebf0 VA: 0x7595026bf0
	public Color get_selectableColor() { }
	// RVA: 0x2a0cee8 VA: 0x7595024ee8
	public Color get_bottomBarColor() { }
	// RVA: 0x2a0f28c VA: 0x759502728c
	public Boolean get_needToPlayVertUpAnim() { }
	// RVA: 0x2a0f2f4 VA: 0x75950272f4
	public Boolean get_needToPlayVertDownAnim() { }
	// RVA: 0x2a0f35c VA: 0x759502735c
	public Boolean get_isInSpecialZone() { }
	// RVA: 0x2a0f3c4 VA: 0x75950273c4
	public GameObject get_cacheParticle() { }
	// RVA: 0x2a0f42c VA: 0x759502742c
	public EffectCache get_effectCache() { }
	// RVA: 0x2a0f494 VA: 0x7595027494
	public Action`1 get_onClicked() { }
	// RVA: 0x2a0f4fc VA: 0x75950274fc
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2a0f580 VA: 0x7595027580
	public Void set_isVisible(Boolean value) { }
	// RVA: 0x2a0f62c VA: 0x759502762c
	public Void EventOnClicked() { }
	// RVA: 0x2a0f6cc VA: 0x75950276cc
	public Void AnimationEventOnPlayParticle() { }
	// RVA: 0x2a0f770 VA: 0x7595027770
	public RectTransform GetConnector(Boolean isFromConnector, Int32 index) { }
	// RVA: 0x2a0f8a8 VA: 0x75950278a8
	public RoguelikeVerticalLine GetVertLine() { }
	// RVA: 0x2a0f910 VA: 0x7595027910
	public RoguelikeCurve GetCurve(Int32 index) { }
	// RVA: 0x2a0f9ec VA: 0x75950279ec
	public Void Render(String topicId, RoguelikeDungeonNode node) { }
	// RVA: 0x2a0fba0 VA: 0x7595027ba0
	private Void _PreprocessData() { }
	// RVA: 0x2a0fe84 VA: 0x7595027e84
	protected virtual Void GetColorData() { }
	// RVA: 0x2a0fcb4 VA: 0x7595027cb4
	private Void _ResetAnim() { }
	// RVA: 0x2a0ffa0 VA: 0x7595027fa0
	protected virtual Void RenderBossWidgets() { }
	// RVA: 0x2a10018 VA: 0x7595028018
	protected virtual Void RenderNonBossWidigets() { }
	// RVA: 0x2a10090 VA: 0x7595028090
	public Void ClearEffect() { }
	// RVA: 0x2a102c4 VA: 0x75950282c4
	protected virtual Void RenderVertLines() { }
	// RVA: 0x2a10684 VA: 0x7595028684
	protected virtual Void RenderCurves() { }
	// RVA: 0x2a106fc VA: 0x75950286fc
	protected virtual Void RenderParticles() { }
	// RVA: 0x2a109ac VA: 0x75950289ac
	protected virtual Void RenderOtherWidgets() { }
	// RVA: 0x2a10a24 VA: 0x7595028a24
	protected virtual Void PlayAnim() { }
	// RVA: 0x2a10bf0 VA: 0x7595028bf0
	private IEnumerator _UpdateAnim() { }
	// RVA: 0x2a10cc4 VA: 0x7595028cc4
	public Void OnDisable() { }
	// RVA: 0x2a10dd8 VA: 0x7595028dd8
	public Void .ctor() { }
}
```