# ShopGPTabItemView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Color _textOffColor`

- `Color _textOnColor`

- `TwoStateToggle _selectedToggle`

- `Text _tabNameText`

- `Image _tabIcon`

- `Image _markerIcon`

- `String m_cachedTabId`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(ShopGPTabItemModel, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPTabItemView : MonoBehaviour, IHotfixable
{
	private Color _textOffColor; // 0x18
	private Color _textOnColor; // 0x28
	private TwoStateToggle _selectedToggle; // 0x38
	private Text _tabNameText; // 0x40
	private Image _tabIcon; // 0x48
	private Image _markerIcon; // 0x50
	private String m_cachedTabId; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private UIStateFinder m_stateFinder; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x244b0dc VA: 0x7594a630dc
	public Void Render(ShopGPTabItemModel itemModel, String selectedTabId) { }
	// RVA: 0x244b328 VA: 0x7594a63328
	public Void OnClick() { }
	// RVA: 0x244b434 VA: 0x7594a63434
	public Void .ctor() { }
}
```