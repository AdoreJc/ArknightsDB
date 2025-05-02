# CarvingAVGAdapter

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIPageFinder m_pageFinder`


## Methods

- `Boolean _OnFocusBuyCard(Command)`

- `Boolean _OnSelectHandCard(Command)`

- `Boolean _OnSelectCardSlot(Command)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingAVGAdapter : ExecutorComponent, IHotfixable
{
	private const String PARAM_FOCUS_BUY_CARD_POSITION; // 0x0
	private const String PARAM_SELECT_HAND_CARD_ID; // 0x0
	private UIPageFinder m_pageFinder; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x8
	private static DelegateBridge __Hotfix0__OnFocusBuyCard; // 0x10
	private static DelegateBridge __Hotfix0__OnSelectHandCard; // 0x18
	private static DelegateBridge __Hotfix0__OnSelectCardSlot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d96f78 VA: 0x75953aef78
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2d971dc VA: 0x75953af1dc
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2d97240 VA: 0x75953af240
	private Boolean _OnFocusBuyCard(Command command) { }
	// RVA: 0x2d97380 VA: 0x75953af380
	private Boolean _OnSelectHandCard(Command command) { }
	// RVA: 0x2d974c0 VA: 0x75953af4c0
	private Boolean _OnSelectCardSlot(Command command) { }
	// RVA: 0x2d97574 VA: 0x75953af574
	public Void .ctor() { }
}
```