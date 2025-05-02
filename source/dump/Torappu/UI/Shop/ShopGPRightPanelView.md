# ShopGPRightPanelView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `RectTransform _panelContainer`

- `Boolean m_isInited`

- `Int32 m_cachedFastSeq`

- `String m_cachedSelectedId`

- `UIPageFinder m_pageFinder`

- `ShopGPCommonSortPanel m_allPanel`


## Methods

- `Void _InitIfNot()`

- `T _CreatePanel(ShopGPPanelType)`

- `Void _CreatePanelIfNecessary(ShopGPViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPRightPanelView : DataBinder`1, IHotfixable
{
	private RectTransform _panelContainer; // 0x20
	private Boolean m_isInited; // 0x28
	private Int32 m_cachedFastSeq; // 0x2c
	private String m_cachedSelectedId; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private ShopGPCommonSortPanel m_allPanel; // 0x48
	private Dictionary`2 m_createdPanelDict; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__CreatePanel; // 0x10
	private static DelegateBridge __Hotfix0__CreatePanelIfNecessary; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24410b0 VA: 0x7594a590b0
	private Void _InitIfNot() { }
	// RVA: 0x2441160 VA: 0x7594a59160
	public override Void OnValueChanged(ShopGPProperty property) { }
	// RVA: 0x VA: 0x0
	private T _CreatePanel(ShopGPPanelType type) { }
	// RVA: 0x244150c VA: 0x7594a5950c
	private Void _CreatePanelIfNecessary(ShopGPViewModel viewModel) { }
	// RVA: 0x2441920 VA: 0x7594a59920
	public Void .ctor() { }
}
```