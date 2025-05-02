# CarvingCardListViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingCardSelectStatus selectedCardStatus`

- `CarvingCardTokenStatus tokenStatus`

- `Int32 activeSlotCount`


## Methods

- `Void UpdateData(String, Boolean)`

- `Boolean SelectCard(String)`

- `Boolean ClearSelect()`

- `Boolean DragOutCard(String, CarvingCardPosition)`

- `Boolean DragCancelToHandCard(String)`

- `Boolean DragCancelToSlotCard(String, Int32)`

- `Boolean AddSelectedHandToSlot()`

- `Boolean SetTokenHoveringSlot(String, Int32)`

- `Boolean OnTokenMovedIntoSlot(String)`

- `Boolean SetTokenHoveringInHandArea(String, Boolean)`

- `Boolean HasEmptySlot()`

- `Boolean HasEmptySlotBefore(Int32)`

- `CarvingMainCardViewModel GetSelectedCardViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingCardListViewModel : IHotfixable
{
	public ListDict`2 cardList; // 0x10
	public ListDict`2 slotCardList; // 0x18
	public CarvingCardSelectStatus selectedCardStatus; // 0x20
	public CarvingCardTokenStatus tokenStatus; // 0x30
	public Int32 activeSlotCount; // 0x48
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0_SelectCard; // 0x8
	private static DelegateBridge __Hotfix0_ClearSelect; // 0x10
	private static DelegateBridge __Hotfix0_DragOutCard; // 0x18
	private static DelegateBridge __Hotfix0_DragCancelToHandCard; // 0x20
	private static DelegateBridge __Hotfix0_DragCancelToSlotCard; // 0x28
	private static DelegateBridge __Hotfix0_AddSelectedHandToSlot; // 0x30
	private static DelegateBridge __Hotfix0_SetTokenHoveringSlot; // 0x38
	private static DelegateBridge __Hotfix0_OnTokenMovedIntoSlot; // 0x40
	private static DelegateBridge __Hotfix0_SetTokenHoveringInHandArea; // 0x48
	private static DelegateBridge __Hotfix0_HasEmptySlot; // 0x50
	private static DelegateBridge __Hotfix0_HasEmptySlotBefore; // 0x58
	private static DelegateBridge __Hotfix0_GetSelectedCardViewModel; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2da8050 VA: 0x75953c0050
	public Void UpdateData(String actId, Boolean noNeedReloadCard) { }
	// RVA: 0x2da880c VA: 0x75953c080c
	public Boolean SelectCard(String cardId) { }
	// RVA: 0x2da89d8 VA: 0x75953c09d8
	public Boolean ClearSelect() { }
	// RVA: 0x2da8a80 VA: 0x75953c0a80
	public Boolean DragOutCard(String cardId, CarvingCardPosition position) { }
	// RVA: 0x2da8c30 VA: 0x75953c0c30
	public Boolean DragCancelToHandCard(String cardId) { }
	// RVA: 0x2da8f48 VA: 0x75953c0f48
	public Boolean DragCancelToSlotCard(String cardId, Int32 slotIdx) { }
	// RVA: 0x2da9324 VA: 0x75953c1324
	public Boolean AddSelectedHandToSlot() { }
	// RVA: 0x2da94d8 VA: 0x75953c14d8
	public Boolean SetTokenHoveringSlot(String cardId, Int32 slotIdx) { }
	// RVA: 0x2da95dc VA: 0x75953c15dc
	public Boolean OnTokenMovedIntoSlot(String cardId) { }
	// RVA: 0x2da96ac VA: 0x75953c16ac
	public Boolean SetTokenHoveringInHandArea(String cardId, Boolean inHandArea) { }
	// RVA: 0x2da91f4 VA: 0x75953c11f4
	public Boolean HasEmptySlot() { }
	// RVA: 0x2da9284 VA: 0x75953c1284
	public Boolean HasEmptySlotBefore(Int32 slotIdx) { }
	// RVA: 0x2da97c4 VA: 0x75953c17c4
	public CarvingMainCardViewModel GetSelectedCardViewModel() { }
	// RVA: 0x2da9888 VA: 0x75953c1888
	public Void .ctor() { }
}
```