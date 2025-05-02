# UICard

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _avatarImage`

- `Image _professionIcon`

- `Image _professionMark`

- `Image _rarityMark`

- `Image _eliteIcon`

- `Image _assistCharIcon`

- `Text _costLabel`

- `Image _remainingBackImage`

- `Text _remainingCntLabel`

- `Slider _respawnSlider`

- `Text _respawnLabel`

- `Toggle _toggle`

- `Color _defaultColor`

- `Color _disableColor`

- `Single _toggleDuration`

- `Single _toggleOffset`

- `Single _fadeDuration`

- `Single _blinkDuration`

- `Single _blinkEasePart`

- `Ease _blinkEaseStart`

- `Ease _blinkEaseEnd`

- `Image _comboImageUnder`

- `Image _comboImageIcon`

- `Image _mhImageUnder`

- `Image _mhImageIcon`

- `Transform _pluginRoot`

- `Boolean m_isEnabled`

- `Vector3 m_originLocalPosition`

- `RectTransform m_rectTransform`

- `Animator m_comboImageUnderAnimator`

- `Animator m_comboImageIconAnimator`

- `Card <card>k__BackingField`

- `Int32 <currentPointerId>k__BackingField`

- `Int32 <index>k__BackingField`

- `UICardList <cardList>k__BackingField`

- `UICardEffectHolder <effectHolder>k__BackingField`

- `Sequence m_tweenSeq`

- `Single m_localPositionY`


## Properties

- `Animator comboImageUnderAnimator`

- `Animator comboImageIconAnimator`

- `Card card`

- `Boolean isEnabled`

- `Boolean isOn`

- `RectTransform rectTransform`

- `Int32 currentPointerId`

- `Int32 index`

- `UICardList cardList`

- `UICardEffectHolder effectHolder`

- `Single localPositionY`


## Methods

- `Animator get_comboImageUnderAnimator()`

- `Animator get_comboImageIconAnimator()`

- `Card get_card()`

- `Void set_card(Card)`

- `Boolean get_isEnabled()`

- `Void set_isEnabled(Boolean)`

- `Boolean get_isOn()`

- `Void set_isOn(Boolean)`

- `RectTransform get_rectTransform()`

- `Int32 get_currentPointerId()`

- `Void set_currentPointerId(Int32)`

- `Int32 get_index()`

- `Void set_index(Int32)`

- `UICardList get_cardList()`

- `Void set_cardList(UICardList)`

- `UICardEffectHolder get_effectHolder()`

- `Void set_effectHolder(UICardEffectHolder)`

- `Single get_localPositionY()`

- `Void set_localPositionY(Single)`

- `Void SetToggleGroup(Boolean)`

- `Void SetData(Card, Int32, UICardList, UICardEffectHolder)`

- `Void RefreshCardAppearanceE(Card)`

- `Void RefreshEffect(Card)`

- `Void ShowCardSelectForLegion(Boolean)`

- `Void RefreshCost(Card)`

- `Void RefreshRespawnTime(Card)`

- `Void OnDrag(BaseEventData)`

- `Void OnBeginDrag(BaseEventData)`

- `Void OnEndDrag(BaseEventData)`

- `Void OnToggled()`

- `Void OnHover(Boolean)`

- `Void OnBlink()`

- `Void _UpdateComboState()`

- `Void _UpdateMhwrbgState()`

- `Void _SetRarityRank(RarityRank)`

- `Void _SetProfession(ProfessionCategory)`

- `Void _SetEvolvePhase(EvolvePhase)`

- `Void _SetEnabled(Boolean, Boolean)`

- `Void _UpdateStatus(Boolean)`

- `Void AttachPluginIfNot(UICardPlugin)`

- `Void AttachPluginIfNot(IEnumerable`1)`

- `Void Update()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICard : MonoBehaviour, IHotfixable
{
	private const String REMAINING_CNT_FORMAT; // 0x0
	private Image _avatarImage; // 0x18
	private Image _professionIcon; // 0x20
	private Image _professionMark; // 0x28
	private Image _rarityMark; // 0x30
	private Image _eliteIcon; // 0x38
	private Image _assistCharIcon; // 0x40
	private Text _costLabel; // 0x48
	private Image _remainingBackImage; // 0x50
	private Text _remainingCntLabel; // 0x58
	private Slider _respawnSlider; // 0x60
	private Text _respawnLabel; // 0x68
	private Toggle _toggle; // 0x70
	private ProfessionData[] _professionData; // 0x78
	private Sprite[] _rarityColors; // 0x80
	private Sprite[] _evolveIcons; // 0x88
	private Graphic[] _tintTargets; // 0x90
	private Color _defaultColor; // 0x98
	private Color _disableColor; // 0xa8
	private Single _toggleDuration; // 0xb8
	private Single _toggleOffset; // 0xbc
	private Single _fadeDuration; // 0xc0
	private Single _blinkDuration; // 0xc4
	private Single _blinkEasePart; // 0xc8
	private Ease _blinkEaseStart; // 0xcc
	private Ease _blinkEaseEnd; // 0xd0
	private Image _comboImageUnder; // 0xd8
	private Image _comboImageIcon; // 0xe0
	private Image _mhImageUnder; // 0xe8
	private Image _mhImageIcon; // 0xf0
	private Transform _pluginRoot; // 0xf8
	private Boolean m_isEnabled; // 0x100
	private Vector3 m_originLocalPosition; // 0x104
	private RectTransform m_rectTransform; // 0x110
	private CanvasGroup[] m_canvasGroup; // 0x118
	private const Single SELECTED_ALPHA; // 0x0
	private Animator m_comboImageUnderAnimator; // 0x120
	private List`1 m_plugin; // 0x128
	private Animator m_comboImageIconAnimator; // 0x130
	private Card <card>k__BackingField; // 0x138
	private Int32 <currentPointerId>k__BackingField; // 0x140
	private Int32 <index>k__BackingField; // 0x144
	private UICardList <cardList>k__BackingField; // 0x148
	private UICardEffectHolder <effectHolder>k__BackingField; // 0x150
	private Sequence m_tweenSeq; // 0x158
	private Single m_localPositionY; // 0x160
	private static DelegateBridge __Hotfix0_get_comboImageUnderAnimator; // 0x0
	private static DelegateBridge __Hotfix0_get_comboImageIconAnimator; // 0x8
	private static DelegateBridge __Hotfix0_get_card; // 0x10
	private static DelegateBridge __Hotfix0_set_card; // 0x18
	private static DelegateBridge __Hotfix0_get_isEnabled; // 0x20
	private static DelegateBridge __Hotfix0_set_isEnabled; // 0x28
	private static DelegateBridge __Hotfix0_get_isOn; // 0x30
	private static DelegateBridge __Hotfix0_set_isOn; // 0x38
	private static DelegateBridge __Hotfix0_get_rectTransform; // 0x40
	private static DelegateBridge __Hotfix0_get_currentPointerId; // 0x48
	private static DelegateBridge __Hotfix0_set_currentPointerId; // 0x50
	private static DelegateBridge __Hotfix0_get_index; // 0x58
	private static DelegateBridge __Hotfix0_set_index; // 0x60
	private static DelegateBridge __Hotfix0_get_cardList; // 0x68
	private static DelegateBridge __Hotfix0_set_cardList; // 0x70
	private static DelegateBridge __Hotfix0_get_effectHolder; // 0x78
	private static DelegateBridge __Hotfix0_set_effectHolder; // 0x80
	private static DelegateBridge __Hotfix0_get_localPositionY; // 0x88
	private static DelegateBridge __Hotfix0_set_localPositionY; // 0x90
	private static DelegateBridge __Hotfix0_SetToggleGroup; // 0x98
	private static DelegateBridge __Hotfix0_SetData; // 0xa0
	private static DelegateBridge __Hotfix0_RefreshCardAppearanceE; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshEffect; // 0xb0
	private static DelegateBridge __Hotfix0_ShowCardSelectForLegion; // 0xb8
	private static DelegateBridge __Hotfix0_RefreshCost; // 0xc0
	private static DelegateBridge __Hotfix0_RefreshRespawnTime; // 0xc8
	private static DelegateBridge __Hotfix0_OnDrag; // 0xd0
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0xd8
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0xe0
	private static DelegateBridge __Hotfix0_OnToggled; // 0xe8
	private static DelegateBridge __Hotfix0_OnHover; // 0xf0
	private static DelegateBridge __Hotfix0_OnBlink; // 0xf8
	private static DelegateBridge __Hotfix0__UpdateComboState; // 0x100
	private static DelegateBridge __Hotfix0__UpdateMhwrbgState; // 0x108
	private static DelegateBridge __Hotfix0__SetRarityRank; // 0x110
	private static DelegateBridge __Hotfix0__SetProfession; // 0x118
	private static DelegateBridge __Hotfix0__SetEvolvePhase; // 0x120
	private static DelegateBridge __Hotfix0__SetEnabled; // 0x128
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0x130
	private static DelegateBridge __Hotfix0_AttachPluginIfNot; // 0x138
	private static DelegateBridge __Hotfix1_AttachPluginIfNot; // 0x140
	private static DelegateBridge __Hotfix0_Update; // 0x148
	private static DelegateBridge __Hotfix0_Awake; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	private Animator comboImageUnderAnimator { get; }
	private Animator comboImageIconAnimator { get; }
	public Card card { get; set; }
	public Boolean isEnabled { get; set; }
	public Boolean isOn { get; set; }
	public RectTransform rectTransform { get; }
	public Int32 currentPointerId { get; set; }
	protected Int32 index { get; set; }
	protected UICardList cardList { get; set; }
	protected UICardEffectHolder effectHolder { get; set; }
	public Single localPositionY { get; set; }

	// RVA: 0x202ab74 VA: 0x7594642b74
	private Animator get_comboImageUnderAnimator() { }
	// RVA: 0x202ac54 VA: 0x7594642c54
	private Animator get_comboImageIconAnimator() { }
	// RVA: 0x202ad34 VA: 0x7594642d34
	public Card get_card() { }
	// RVA: 0x202ad9c VA: 0x7594642d9c
	private Void set_card(Card value) { }
	// RVA: 0x202ae20 VA: 0x7594642e20
	public Boolean get_isEnabled() { }
	// RVA: 0x202ae88 VA: 0x7594642e88
	private Void set_isEnabled(Boolean value) { }
	// RVA: 0x202b15c VA: 0x759464315c
	public Boolean get_isOn() { }
	// RVA: 0x202b1d0 VA: 0x75946431d0
	public Void set_isOn(Boolean value) { }
	// RVA: 0x202b25c VA: 0x759464325c
	public RectTransform get_rectTransform() { }
	// RVA: 0x202b334 VA: 0x7594643334
	public Int32 get_currentPointerId() { }
	// RVA: 0x202b39c VA: 0x759464339c
	public Void set_currentPointerId(Int32 value) { }
	// RVA: 0x202b418 VA: 0x7594643418
	protected Int32 get_index() { }
	// RVA: 0x202b480 VA: 0x7594643480
	private Void set_index(Int32 value) { }
	// RVA: 0x202b4fc VA: 0x75946434fc
	protected UICardList get_cardList() { }
	// RVA: 0x202b564 VA: 0x7594643564
	private Void set_cardList(UICardList value) { }
	// RVA: 0x202b5e8 VA: 0x75946435e8
	protected UICardEffectHolder get_effectHolder() { }
	// RVA: 0x202b650 VA: 0x7594643650
	private Void set_effectHolder(UICardEffectHolder value) { }
	// RVA: 0x202b6d4 VA: 0x75946436d4
	public Single get_localPositionY() { }
	// RVA: 0x202b73c VA: 0x759464373c
	public Void set_localPositionY(Single value) { }
	// RVA: 0x202b7b8 VA: 0x75946437b8
	public Void SetToggleGroup(Boolean isEnabled) { }
	// RVA: 0x202b8d0 VA: 0x75946438d0
	public Void SetData(Card card, Int32 index, UICardList cardList, UICardEffectHolder cardEffectHolder) { }
	// RVA: 0x202ba28 VA: 0x7594643a28
	public Void RefreshCardAppearanceE(Card card) { }
	// RVA: 0x202cafc VA: 0x7594644afc
	public Void RefreshEffect(Card card) { }
	// RVA: 0x202cb88 VA: 0x7594644b88
	public Void ShowCardSelectForLegion(Boolean isSelect) { }
	// RVA: 0x202cd00 VA: 0x7594644d00
	public Void RefreshCost(Card card) { }
	// RVA: 0x202cde4 VA: 0x7594644de4
	public Void RefreshRespawnTime(Card card) { }
	// RVA: 0x202cec0 VA: 0x7594644ec0
	public Void OnDrag(BaseEventData eventData) { }
	// RVA: 0x202d034 VA: 0x7594645034
	public Void OnBeginDrag(BaseEventData eventData) { }
	// RVA: 0x202d248 VA: 0x7594645248
	public Void OnEndDrag(BaseEventData eventData) { }
	// RVA: 0x202d3e8 VA: 0x75946453e8
	public Void OnToggled() { }
	// RVA: 0x202d898 VA: 0x7594645898
	public Void OnHover(Boolean isHover) { }
	// RVA: 0x202da18 VA: 0x7594645a18
	public Void OnBlink() { }
	// RVA: 0x202c8d8 VA: 0x75946448d8
	private Void _UpdateComboState() { }
	// RVA: 0x202ca3c VA: 0x7594644a3c
	private Void _UpdateMhwrbgState() { }
	// RVA: 0x202c6ec VA: 0x75946446ec
	private Void _SetRarityRank(RarityRank rarity) { }
	// RVA: 0x202c5c8 VA: 0x75946445c8
	private Void _SetProfession(ProfessionCategory profession) { }
	// RVA: 0x202c794 VA: 0x7594644794
	private Void _SetEvolvePhase(EvolvePhase evolvePhase) { }
	// RVA: 0x202af0c VA: 0x7594642f0c
	private Void _SetEnabled(Boolean value, Boolean force) { }
	// RVA: 0x202be14 VA: 0x7594643e14
	private Void _UpdateStatus(Boolean force) { }
	// RVA: 0x202dc74 VA: 0x7594645c74
	public Void AttachPluginIfNot(UICardPlugin plugin) { }
	// RVA: 0x202df88 VA: 0x7594645f88
	public Void AttachPluginIfNot(IEnumerable`1 plugins) { }
	// RVA: 0x202e29c VA: 0x759464629c
	private Void Update() { }
	// RVA: 0x202e308 VA: 0x7594646308
	private Void Awake() { }
	// RVA: 0x202e3fc VA: 0x75946463fc
	public Void .ctor() { }
}
```