# CarvingCardViewHolder

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainCardView _prefabCard`

- `RectTransform _cardContainer`

- `UIAnimationLocation _showAnim`

- `UIColorGraphic _colorGraphic`

- `Boolean m_inited`

- `Single m_showPos`

- `CarvingMainCardView m_cardView`

- `UIPageFinder m_pageFinder`

- `String m_cachedCardId`

- `CarvingDragParam m_dragParam`

- `Int32 <sortId>k__BackingField`

- `Single <samplePos>k__BackingField`

- `DragHandler <dragHandler>k__BackingField`


## Properties

- `Int32 sortId`

- `Single samplePos`

- `Single showPos`

- `DragHandler dragHandler`


## Methods

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Single get_samplePos()`

- `Void set_samplePos(Single)`

- `Single get_showPos()`

- `DragHandler get_dragHandler()`

- `Void set_dragHandler(DragHandler)`

- `Void _InitIfNot()`

- `Void SetShowPos(Single)`

- `Void Render(CarvingMainCardViewModel, CarvingMainViewModel, Boolean)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void OnCardClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingCardViewHolder : MonoBehaviour, ICustomAnimDrivenLayoutElement, IBeginDragHandler, IEventSystemHandler, IDragHandler, IEndDragHandler, IHotfixable
{
	private CarvingMainCardView _prefabCard; // 0x18
	private RectTransform _cardContainer; // 0x20
	private UIAnimationLocation _showAnim; // 0x28
	private UIColorGraphic _colorGraphic; // 0x38
	private Boolean m_inited; // 0x40
	private Single m_showPos; // 0x44
	private CarvingMainCardView m_cardView; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private String m_cachedCardId; // 0x60
	private CarvingDragParam m_dragParam; // 0x68
	private Int32 <sortId>k__BackingField; // 0x70
	private Single <samplePos>k__BackingField; // 0x74
	private DragHandler <dragHandler>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_sortId; // 0x0
	private static DelegateBridge __Hotfix0_set_sortId; // 0x8
	private static DelegateBridge __Hotfix0_get_samplePos; // 0x10
	private static DelegateBridge __Hotfix0_set_samplePos; // 0x18
	private static DelegateBridge __Hotfix0_get_showPos; // 0x20
	private static DelegateBridge __Hotfix0_get_dragHandler; // 0x28
	private static DelegateBridge __Hotfix0_set_dragHandler; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_SetShowPos; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x48
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x50
	private static DelegateBridge __Hotfix0_OnDrag; // 0x58
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x60
	private static DelegateBridge __Hotfix0_OnCardClicked; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Int32 sortId { get; set; }
	public Single samplePos { get; set; }
	public Single showPos { get; }
	private DragHandler dragHandler { get; set; }

	// RVA: 0x2da318c VA: 0x75953bb18c
	public Int32 get_sortId() { }
	// RVA: 0x2da3110 VA: 0x75953bb110
	public Void set_sortId(Int32 value) { }
	// RVA: 0x2da4014 VA: 0x75953bc014
	public Single get_samplePos() { }
	// RVA: 0x2da407c VA: 0x75953bc07c
	public Void set_samplePos(Single value) { }
	// RVA: 0x2da3af4 VA: 0x75953bbaf4
	public Single get_showPos() { }
	// RVA: 0x2da40f8 VA: 0x75953bc0f8
	private DragHandler get_dragHandler() { }
	// RVA: 0x2da32ec VA: 0x75953bb2ec
	public Void set_dragHandler(DragHandler value) { }
	// RVA: 0x2da4160 VA: 0x75953bc160
	private Void _InitIfNot() { }
	// RVA: 0x2da3b5c VA: 0x75953bbb5c
	public Void SetShowPos(Single showPos) { }
	// RVA: 0x2da3370 VA: 0x75953bb370
	public Void Render(CarvingMainCardViewModel viewModel, CarvingMainViewModel carvingViewModel, Boolean isProcessed) { }
	// RVA: 0x2da4290 VA: 0x75953bc290
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x2da43cc VA: 0x75953bc3cc
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x2da4444 VA: 0x75953bc444
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2da44bc VA: 0x75953bc4bc
	public Void OnCardClicked() { }
	// RVA: 0x2da45c4 VA: 0x75953bc5c4
	public Void .ctor() { }
}
```