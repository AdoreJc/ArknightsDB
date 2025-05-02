# CarvingBoardView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `RectTransform _tokenContainer`

- `CarvingTokenViewHolder _prefabToken`

- `CarvingCardListView _cardListView`

- `CanvasGroup _pnlHandArea`

- `Text _textHandAreaTip`

- `CanvasGroup _pnlHandAreaBkg`

- `CarvingMainViewModel m_cachedViewModel`

- `UIPageFinder m_pageFinder`

- `Boolean m_inited`

- `CarvingDragContext m_dragContext`

- `UISwitchTween m_handAreaTipShowTween`

- `UISwitchTween m_handAreaTipBkgShowTween`


## Properties

- `DragHandler dragHandler`


## Methods

- `DragHandler get_dragHandler()`

- `Void _InitIfNot()`

- `Void RegisterSlotViewListToDragHandler(List`1)`

- `Void Update()`

- `Void _OnHandCardDragOut(String)`

- `Void _OnSlotCardDragOut(String)`

- `Void _OnDragCancelToHandCard(String)`

- `Void _OnDragCancelToSlotCard(String, Int32)`

- `Void _OnTokenHoverSlotChanged(String, Int32)`

- `Void _OnTokenHoverInHandAreaChanged(String, Boolean)`

- `Void _OnStartDragBlocker()`

- `Void _OnEndDragBlocker()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingBoardView : DataBinder`1
{
	private RectTransform _tokenContainer; // 0x20
	private CarvingTokenViewHolder _prefabToken; // 0x28
	private CarvingCardListView _cardListView; // 0x30
	private CanvasGroup _pnlHandArea; // 0x38
	private Text _textHandAreaTip; // 0x40
	private CanvasGroup _pnlHandAreaBkg; // 0x48
	private CarvingMainViewModel m_cachedViewModel; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private Boolean m_inited; // 0x68
	private DragHandler`1 m_dragHandler; // 0x70
	private CarvingDragContext m_dragContext; // 0x78
	private UISwitchTween m_handAreaTipShowTween; // 0x80
	private UISwitchTween m_handAreaTipBkgShowTween; // 0x88
	private static DelegateBridge __Hotfix0_get_dragHandler; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_RegisterSlotViewListToDragHandler; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0__OnHandCardDragOut; // 0x28
	private static DelegateBridge __Hotfix0__OnSlotCardDragOut; // 0x30
	private static DelegateBridge __Hotfix0__OnDragCancelToHandCard; // 0x38
	private static DelegateBridge __Hotfix0__OnDragCancelToSlotCard; // 0x40
	private static DelegateBridge __Hotfix0__OnTokenHoverSlotChanged; // 0x48
	private static DelegateBridge __Hotfix0__OnTokenHoverInHandAreaChanged; // 0x50
	private static DelegateBridge __Hotfix0__OnStartDragBlocker; // 0x58
	private static DelegateBridge __Hotfix0__OnEndDragBlocker; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public DragHandler dragHandler { get; }

	// RVA: 0x2da0a0c VA: 0x75953b8a0c
	public DragHandler get_dragHandler() { }
	// RVA: 0x2da0a74 VA: 0x75953b8a74
	private Void _InitIfNot() { }
	// RVA: 0x2da0e6c VA: 0x75953b8e6c
	public Void RegisterSlotViewListToDragHandler(List`1 carvingSlots) { }
	// RVA: 0x2da0f80 VA: 0x75953b8f80
	public override Void OnValueChanged(CarvingMainProperty property) { }
	// RVA: 0x2da123c VA: 0x75953b923c
	private Void Update() { }
	// RVA: 0x2da12b8 VA: 0x75953b92b8
	private Void _OnHandCardDragOut(String cardId) { }
	// RVA: 0x2da13c4 VA: 0x75953b93c4
	private Void _OnSlotCardDragOut(String cardId) { }
	// RVA: 0x2da14d0 VA: 0x75953b94d0
	private Void _OnDragCancelToHandCard(String cardId) { }
	// RVA: 0x2da15dc VA: 0x75953b95dc
	private Void _OnDragCancelToSlotCard(String cardId, Int32 slotIdx) { }
	// RVA: 0x2da16dc VA: 0x75953b96dc
	private Void _OnTokenHoverSlotChanged(String cardId, Int32 slotIdx) { }
	// RVA: 0x2da17dc VA: 0x75953b97dc
	private Void _OnTokenHoverInHandAreaChanged(String cardId, Boolean inHandArea) { }
	// RVA: 0x2da18dc VA: 0x75953b98dc
	private Void _OnStartDragBlocker() { }
	// RVA: 0x2da1990 VA: 0x75953b9990
	private Void _OnEndDragBlocker() { }
	// RVA: 0x2da1a44 VA: 0x75953b9a44
	public Void .ctor() { }
}
```