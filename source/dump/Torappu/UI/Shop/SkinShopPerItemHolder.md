# SkinShopPerItemHolder

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Transform _container`

- `GameObject _button`

- `UIStringEvent clickEvent`

- `Boolean m_hasInited`

- `SkinShopPerItemView m_itemView`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(SkinShopViewModel)`

- `Void RenderButton()`

- `Void GoToWardrobe()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SkinShopPerItemHolder : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private GameObject _button; // 0x20
	public UIStringEvent clickEvent; // 0x28
	private Boolean m_hasInited; // 0x30
	private SkinShopPerItemView m_itemView; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_RenderButton; // 0x10
	private static DelegateBridge __Hotfix0_GoToWardrobe; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x246acc0 VA: 0x7594a82cc0
	private Void _InitIfNot() { }
	// RVA: 0x246a940 VA: 0x7594a82940
	public Void Render(SkinShopViewModel viewModel) { }
	// RVA: 0x246aa58 VA: 0x7594a82a58
	public Void RenderButton() { }
	// RVA: 0x246b8dc VA: 0x7594a838dc
	public Void GoToWardrobe() { }
	// RVA: 0x246b960 VA: 0x7594a83960
	public Void .ctor() { }
}
```