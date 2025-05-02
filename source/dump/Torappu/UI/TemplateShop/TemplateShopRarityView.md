# TemplateShopRarityView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `SimpleLayoutContent _content`

- `GameObject _lockedPart`

- `Text _lockedString`

- `GridLayoutGroup _layOutGroup`

- `ContentSizeFitter _sizeFitter`

- `Image _rarityBg`

- `GameObject _rarityDotGo`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `IEnumerator OnRefreshContent()`

- `Void Render(TemplateShopRarityViewModel, Int32, TemplateShopResHolder)`

- `Void _RenderCustomBg(String)`

- `Void _RenderRarityBg(Int32, TemplateShopResHolder)`

- `Sprite _GetRarityBg(TemplateShopResHolder, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopRarityView : MonoBehaviour, IHotfixable
{
	private const Int32 RARITY_LEVELS; // 0x0
	private SimpleLayoutContent _content; // 0x18
	private GameObject _lockedPart; // 0x20
	private Text _lockedString; // 0x28
	private GridLayoutGroup _layOutGroup; // 0x30
	private ContentSizeFitter _sizeFitter; // 0x38
	private Image _rarityBg; // 0x40
	private GameObject _rarityDotGo; // 0x48
	private Adapter m_adapter; // 0x50
	private Boolean m_isInited; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRefreshContent; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderCustomBg; // 0x18
	private static DelegateBridge __Hotfix0__RenderRarityBg; // 0x20
	private static DelegateBridge __Hotfix0__GetRarityBg; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x235f3dc VA: 0x75949773dc
	public Void _InitIfNot() { }
	// RVA: 0x235f558 VA: 0x7594977558
	public IEnumerator OnRefreshContent() { }
	// RVA: 0x235f244 VA: 0x7594977244
	public Void Render(TemplateShopRarityViewModel groupViewModel, Int32 index, TemplateShopResHolder resHolder) { }
	// RVA: 0x235f62c VA: 0x759497762c
	private Void _RenderCustomBg(String bkgPath) { }
	// RVA: 0x235f704 VA: 0x7594977704
	private Void _RenderRarityBg(Int32 index, TemplateShopResHolder resHolder) { }
	// RVA: 0x235f7d0 VA: 0x75949777d0
	private Sprite _GetRarityBg(TemplateShopResHolder resHolder, Int32 index) { }
	// RVA: 0x235f97c VA: 0x759497797c
	public Void .ctor() { }
}
```