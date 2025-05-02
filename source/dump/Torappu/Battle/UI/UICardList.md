# UICardList

**Namespace:** `Torappu.Battle.UI`


## Fields

- `EasyInstancePool _instancePool`

- `ToggleGroup _toggleGroup`

- `LayoutGroup _layoutGroup`

- `UIFollower _cardHighlighter`

- `ScrollRect _scrollRect`

- `Vector2 _cardWidthRange`

- `EasyInstancePool _cardEffectHolderPool`

- `RectTransform m_layoutRectTransform`

- `UICard m_activeCard`

- `UICard m_hoverCard`

- `CardListTweener m_cardTweener`


## Properties

- `Int32 cardCnt`

- `UICard activeCard`

- `ToggleGroup toggleGroup`

- `UIFollower cardHighlighter`

- `RectTransform layoutRectTransform`


## Methods

- `Int32 get_cardCnt()`

- `UICard get_activeCard()`

- `ToggleGroup get_toggleGroup()`

- `UIFollower get_cardHighlighter()`

- `RectTransform get_layoutRectTransform()`

- `Boolean TryGetCardScreenPos(Int32, out)`

- `Void OnDrag(UICard, PointerEventData)`

- `Void OnBeginDrag(UICard, PointerEventData)`

- `Void OnEndDrag(UICard, PointerEventData)`

- `Void OnCardToggled(UICard)`

- `Void OnCardSelected(UICard)`

- `Void OnCardHover(UICard, Boolean)`

- `Void UpdateToggleGroup(Boolean)`

- `Void UnSelectActiveCard()`

- `Void OnUpdate()`

- `Void AttachPlugin(UICardPlugin)`

- `Void _RefreshCardList(IList`1)`

- `Void _RefreshCardTweener(Boolean, Boolean)`

- `Int32 GetMaxVisibleCnt()`

- `Void _RefreshCardCost(Card)`

- `Void _RefreshCardEffect(Card)`

- `Void _RefreshCardAppearanceE(Card)`

- `Void _UpdateRectTransform()`

- `Void _OnBlinkCard(Object)`

- `Void _OnDeckCreated(Object)`

- `Void _BindDeckEvents(Deck)`

- `Void _ClearDeckEvents(Deck)`

- `Void <>xLuaBaseProxy_OnCanvasHierarchyChanged()`

- `Void <>xLuaBaseProxy_OnRectTransformDimensionsChange()`

- `Void <>xLuaBaseProxy_OnTransformParentChanged()`

- `Void <>xLuaBaseProxy_Start()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICardList : UIBehaviour, IHotfixable
{
	private EasyInstancePool _instancePool; // 0x18
	private ToggleGroup _toggleGroup; // 0x20
	private LayoutGroup _layoutGroup; // 0x28
	private UIFollower _cardHighlighter; // 0x30
	private ScrollRect _scrollRect; // 0x38
	private Vector2 _cardWidthRange; // 0x40
	private EasyInstancePool _cardEffectHolderPool; // 0x48
	private RectTransform m_layoutRectTransform; // 0x50
	private UICard m_activeCard; // 0x58
	private UICard m_hoverCard; // 0x60
	private CardListTweener m_cardTweener; // 0x68
	private List`1 m_plugin; // 0x70
	private List`1 m_uiCards; // 0x78
	private const Single CARD_TOGGLE_WIDTH; // 0x0
	private static DelegateBridge __Hotfix0_get_cardCnt; // 0x0
	private static DelegateBridge __Hotfix0_get_activeCard; // 0x8
	private static DelegateBridge __Hotfix0_get_toggleGroup; // 0x10
	private static DelegateBridge __Hotfix0_get_cardHighlighter; // 0x18
	private static DelegateBridge __Hotfix0_get_layoutRectTransform; // 0x20
	private static DelegateBridge __Hotfix0_TryGetCardScreenPos; // 0x28
	private static DelegateBridge __Hotfix0_OnDrag; // 0x30
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x38
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x40
	private static DelegateBridge __Hotfix0_OnCardToggled; // 0x48
	private static DelegateBridge __Hotfix0_OnCardSelected; // 0x50
	private static DelegateBridge __Hotfix0_OnCardHover; // 0x58
	private static DelegateBridge __Hotfix0_UpdateToggleGroup; // 0x60
	private static DelegateBridge __Hotfix0_UnSelectActiveCard; // 0x68
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x70
	private static DelegateBridge __Hotfix0_AttachPlugin; // 0x78
	private static DelegateBridge __Hotfix0__RefreshCardList; // 0x80
	private static DelegateBridge __Hotfix0__RefreshCardTweener; // 0x88
	private static DelegateBridge __Hotfix0_GetMaxVisibleCnt; // 0x90
	private static DelegateBridge __Hotfix0__RefreshCardCost; // 0x98
	private static DelegateBridge __Hotfix0__RefreshCardEffect; // 0xa0
	private static DelegateBridge __Hotfix0__RefreshCardAppearanceE; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateRectTransform; // 0xb0
	private static DelegateBridge __Hotfix0__OnBlinkCard; // 0xb8
	private static DelegateBridge __Hotfix0_OnCanvasHierarchyChanged; // 0xc0
	private static DelegateBridge __Hotfix0_OnRectTransformDimensionsChange; // 0xc8
	private static DelegateBridge __Hotfix0_OnTransformParentChanged; // 0xd0
	private static DelegateBridge __Hotfix0_Start; // 0xd8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe0
	private static DelegateBridge __Hotfix0__OnDeckCreated; // 0xe8
	private static DelegateBridge __Hotfix0__BindDeckEvents; // 0xf0
	private static DelegateBridge __Hotfix0__ClearDeckEvents; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	public Int32 cardCnt { get; }
	public UICard activeCard { get; }
	public ToggleGroup toggleGroup { get; }
	public UIFollower cardHighlighter { get; }
	protected RectTransform layoutRectTransform { get; }

	// RVA: 0x202f558 VA: 0x7594647558
	public Int32 get_cardCnt() { }
	// RVA: 0x202f5d8 VA: 0x75946475d8
	public UICard get_activeCard() { }
	// RVA: 0x202b868 VA: 0x7594643868
	public ToggleGroup get_toggleGroup() { }
	// RVA: 0x202d638 VA: 0x7594645638
	public UIFollower get_cardHighlighter() { }
	// RVA: 0x202f640 VA: 0x7594647640
	protected RectTransform get_layoutRectTransform() { }
	// RVA: 0x202f720 VA: 0x7594647720
	public Boolean TryGetCardScreenPos(Int32 index, out Vector3 pos) { }
	// RVA: 0x202cf98 VA: 0x7594644f98
	public Void OnDrag(UICard uiCard, PointerEventData eventData) { }
	// RVA: 0x202d160 VA: 0x7594645160
	public Void OnBeginDrag(UICard uiCard, PointerEventData eventData) { }
	// RVA: 0x202d320 VA: 0x7594645320
	public Void OnEndDrag(UICard uiCard, PointerEventData eventData) { }
	// RVA: 0x202d75c VA: 0x759464575c
	public Void OnCardToggled(UICard uiCard) { }
	// RVA: 0x202d6a0 VA: 0x75946456a0
	public Void OnCardSelected(UICard uiCard) { }
	// RVA: 0x202d928 VA: 0x7594645928
	public Void OnCardHover(UICard uiCard, Boolean isHover) { }
	// RVA: 0x202fa54 VA: 0x7594647a54
	public Void UpdateToggleGroup(Boolean isEnabled) { }
	// RVA: 0x202fbe4 VA: 0x7594647be4
	public Void UnSelectActiveCard() { }
	// RVA: 0x202fca0 VA: 0x7594647ca0
	public Void OnUpdate() { }
	// RVA: 0x202fe94 VA: 0x7594647e94
	public Void AttachPlugin(UICardPlugin pluginPrefabRef) { }
	// RVA: 0x203011c VA: 0x759464811c
	private Void _RefreshCardList(IList`1 cards) { }
	// RVA: 0x202f990 VA: 0x7594647990
	private Void _RefreshCardTweener(Boolean forceRebuild, Boolean isRefreshList) { }
	// RVA: 0x2030a40 VA: 0x7594648a40
	public Int32 GetMaxVisibleCnt() { }
	// RVA: 0x2030b04 VA: 0x7594648b04
	private Void _RefreshCardCost(Card card) { }
	// RVA: 0x2030bf0 VA: 0x7594648bf0
	private Void _RefreshCardEffect(Card card) { }
	// RVA: 0x2030cdc VA: 0x7594648cdc
	private Void _RefreshCardAppearanceE(Card card) { }
	// RVA: 0x2030dc8 VA: 0x7594648dc8
	private Void _UpdateRectTransform() { }
	// RVA: 0x2030f04 VA: 0x7594648f04
	private Void _OnBlinkCard(Object arg) { }
	// RVA: 0x203111c VA: 0x759464911c
	protected override Void OnCanvasHierarchyChanged() { }
	// RVA: 0x2031190 VA: 0x7594649190
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x2031204 VA: 0x7594649204
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x2031278 VA: 0x7594649278
	protected override Void Start() { }
	// RVA: 0x20318e4 VA: 0x75946498e4
	protected override Void OnDestroy() { }
	// RVA: 0x2031cc8 VA: 0x7594649cc8
	private Void _OnDeckCreated(Object arg) { }
	// RVA: 0x20315c0 VA: 0x75946495c0
	private Void _BindDeckEvents(Deck deck) { }
	// RVA: 0x20319bc VA: 0x75946499bc
	private Void _ClearDeckEvents(Deck deck) { }
	// RVA: 0x2031eb4 VA: 0x7594649eb4
	public Void .ctor() { }
	// RVA: 0x2031fc8 VA: 0x7594649fc8
	private Void <>xLuaBaseProxy_OnCanvasHierarchyChanged() { }
	// RVA: 0x2031fd0 VA: 0x7594649fd0
	private Void <>xLuaBaseProxy_OnRectTransformDimensionsChange() { }
	// RVA: 0x2031fd8 VA: 0x7594649fd8
	private Void <>xLuaBaseProxy_OnTransformParentChanged() { }
	// RVA: 0x2031fe0 VA: 0x7594649fe0
	private Void <>xLuaBaseProxy_Start() { }
	// RVA: 0x2031fe8 VA: 0x7594649fe8
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```