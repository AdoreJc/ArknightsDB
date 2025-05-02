# CarvingSlotCardViewHolder

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainCardView _prefabCard`

- `RectTransform _cardContainer`

- `UIAnimationLocation _showAnim`

- `UIColorGraphic _colorGraphic`

- `CanvasGroup _bornTypeHandler`

- `Boolean m_inited`

- `Single m_showPos`

- `CarvingMainCardView m_cardView`

- `UIPageFinder m_pageFinder`

- `String m_cachedCardId`

- `CarvingDragParam m_dragParam`

- `Single <samplePos>k__BackingField`

- `DragHandler <dragHandler>k__BackingField`

- `String <cardId>k__BackingField`


## Properties

- `Single samplePos`

- `Single showPos`

- `DragHandler dragHandler`

- `String cardId`


## Methods

- `Single get_samplePos()`

- `Void set_samplePos(Single)`

- `Single get_showPos()`

- `DragHandler get_dragHandler()`

- `Void set_dragHandler(DragHandler)`

- `String get_cardId()`

- `Void set_cardId(String)`

- `Void _InitIfNot()`

- `Void SetShowPos(Single)`

- `Void Render(CarvingMainCardViewModel, CarvingCardListViewModel, Boolean)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void OnCardClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingSlotCardViewHolder : MonoBehaviour, ICustomAnimDrivenLayoutElement, IBeginDragHandler, IEventSystemHandler, IDragHandler, IEndDragHandler, IHotfixable
{
	public static readonly Single SLOT_CARD_SCALE; // 0x0
	private CarvingMainCardView _prefabCard; // 0x18
	private RectTransform _cardContainer; // 0x20
	private UIAnimationLocation _showAnim; // 0x28
	private UIColorGraphic _colorGraphic; // 0x38
	private CanvasGroup _bornTypeHandler; // 0x40
	private Boolean m_inited; // 0x48
	private Single m_showPos; // 0x4c
	private CarvingMainCardView m_cardView; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private String m_cachedCardId; // 0x68
	private CarvingDragParam m_dragParam; // 0x70
	private Single <samplePos>k__BackingField; // 0x78
	private DragHandler <dragHandler>k__BackingField; // 0x80
	private String <cardId>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_samplePos; // 0x8
	private static DelegateBridge __Hotfix0_set_samplePos; // 0x10
	private static DelegateBridge __Hotfix0_get_showPos; // 0x18
	private static DelegateBridge __Hotfix0_get_dragHandler; // 0x20
	private static DelegateBridge __Hotfix0_set_dragHandler; // 0x28
	private static DelegateBridge __Hotfix0_get_cardId; // 0x30
	private static DelegateBridge __Hotfix0_set_cardId; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_SetShowPos; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x50
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x58
	private static DelegateBridge __Hotfix0_OnDrag; // 0x60
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x68
	private static DelegateBridge __Hotfix0_OnCardClicked; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Single samplePos { get; set; }
	public Single showPos { get; }
	private DragHandler dragHandler { get; set; }
	public String cardId { get; set; }

	// RVA: 0x2d9ec5c VA: 0x75953b6c5c
	public Single get_samplePos() { }
	// RVA: 0x2d9ecd4 VA: 0x75953b6cd4
	public Void set_samplePos(Single value) { }
	// RVA: 0x2d9e824 VA: 0x75953b6824
	public Single get_showPos() { }
	// RVA: 0x2d9ed60 VA: 0x75953b6d60
	private DragHandler get_dragHandler() { }
	// RVA: 0x2d9e088 VA: 0x75953b6088
	public Void set_dragHandler(DragHandler value) { }
	// RVA: 0x2d9df18 VA: 0x75953b5f18
	public String get_cardId() { }
	// RVA: 0x2d9de84 VA: 0x75953b5e84
	public Void set_cardId(String value) { }
	// RVA: 0x2d9edd8 VA: 0x75953b6dd8
	private Void _InitIfNot() { }
	// RVA: 0x2d9e89c VA: 0x75953b689c
	public Void SetShowPos(Single showPos) { }
	// RVA: 0x2d9e11c VA: 0x75953b611c
	public Void Render(CarvingMainCardViewModel viewModel, CarvingCardListViewModel cardListViewModel, Boolean isProcessed) { }
	// RVA: 0x2d9ef34 VA: 0x75953b6f34
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x2d9f098 VA: 0x75953b7098
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x2d9f120 VA: 0x75953b7120
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2d9f1a8 VA: 0x75953b71a8
	public Void OnCardClicked() { }
	// RVA: 0x2d9f2c0 VA: 0x75953b72c0
	public Void .ctor() { }
	// RVA: 0x2d9f388 VA: 0x75953b7388
	private static Void .cctor() { }
}
```