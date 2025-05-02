# RL04AlchemySlotFragmentItemCard

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _imgIcon`

- `SimpleLayoutContent _content`

- `UIColorGraphic _graphic`

- `Single _scale`

- `UIScaler _scaler`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Int32 m_cachedValue`

- `UIPageFinder m_pageFinder`


## Properties

- `Graphic graphic`


## Methods

- `Graphic get_graphic()`

- `Void Render(IRoguelikeFragmentItemModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemySlotFragmentItemCard : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private UIColorGraphic _graphic; // 0x28
	private Single _scale; // 0x30
	private UIScaler _scaler; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_adapter; // 0x48
	private Int32 m_cachedValue; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private static DelegateBridge __Hotfix0_get_graphic; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Graphic graphic { get; }

	// RVA: 0x2b0c81c VA: 0x759512481c
	public Graphic get_graphic() { }
	// RVA: 0x2b0c884 VA: 0x7595124884
	public Void Render(IRoguelikeFragmentItemModel viewModel) { }
	// RVA: 0x2b0cae8 VA: 0x7595124ae8
	private Void _InitIfNot() { }
	// RVA: 0x2b0cc4c VA: 0x7595124c4c
	public Void .ctor() { }
}
```