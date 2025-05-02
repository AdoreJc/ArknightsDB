# RL04GoodsObjFragmentIconView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _iconImage`

- `Text _weightText`

- `SimpleLayoutContent _valueContent`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `Int32 m_cachedValue`


## Methods

- `Void _RenderAsBuy(RoguelikeFragmentData)`

- `Void _RenderAsSell(RoguelikeGoodsViewModel)`

- `Void _UpdateValue(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04GoodsObjFragmentIconView : RoguelikeGoodsObjIconView
{
	private Image _iconImage; // 0x18
	private Text _weightText; // 0x20
	private SimpleLayoutContent _valueContent; // 0x28
	private List`1 _typePanels; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private Boolean m_isInited; // 0x48
	private Adapter m_adapter; // 0x50
	private Int32 m_cachedValue; // 0x58
	private static DelegateBridge __Hotfix0_NeedShowPlugin; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderAsBuy; // 0x10
	private static DelegateBridge __Hotfix0__RenderAsSell; // 0x18
	private static DelegateBridge __Hotfix0__UpdateValue; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2b53420 VA: 0x759516b420
	public override Boolean NeedShowPlugin(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2b534b0 VA: 0x759516b4b0
	public override Void Render(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2b538f8 VA: 0x759516b8f8
	private Void _RenderAsBuy(RoguelikeFragmentData fragmentData) { }
	// RVA: 0x2b537ec VA: 0x759516b7ec
	private Void _RenderAsSell(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2b539ac VA: 0x759516b9ac
	private Void _UpdateValue(Int32 value) { }
	// RVA: 0x2b5371c VA: 0x759516b71c
	private Void _InitIfNot() { }
	// RVA: 0x2b53aec VA: 0x759516baec
	public Void .ctor() { }
}
```