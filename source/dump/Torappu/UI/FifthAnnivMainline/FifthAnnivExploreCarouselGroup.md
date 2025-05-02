# FifthAnnivExploreCarouselGroup

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreCarouselItem _item`

- `UICommonCarousel _group`

- `Single _speed`

- `FifthAnnivExploreCarouselViewModel m_viewModel`

- `Boolean m_isInited`

- `Boolean <hasAvailRender>k__BackingField`


## Properties

- `Boolean hasAvailRender`


## Methods

- `Boolean get_hasAvailRender()`

- `Void set_hasAvailRender(Boolean)`

- `Void _InitIfNot()`

- `Void Refresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreCarouselGroup : MonoBehaviour, IHotfixable
{
	private FifthAnnivExploreCarouselItem _item; // 0x18
	private UICommonCarousel _group; // 0x20
	private Single _speed; // 0x28
	private FifthAnnivExploreCarouselViewModel m_viewModel; // 0x30
	private List`1 m_itemList; // 0x38
	private Boolean m_isInited; // 0x40
	public const Int32 MAX_COUNT; // 0x0
	private Boolean <hasAvailRender>k__BackingField; // 0x41
	private static DelegateBridge __Hotfix0_get_hasAvailRender; // 0x0
	private static DelegateBridge __Hotfix0_set_hasAvailRender; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Refresh; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean hasAvailRender { get; set; }

	// RVA: 0x290a0a4 VA: 0x7594f220a4
	public Boolean get_hasAvailRender() { }
	// RVA: 0x290a10c VA: 0x7594f2210c
	private Void set_hasAvailRender(Boolean value) { }
	// RVA: 0x290a18c VA: 0x7594f2218c
	private Void _InitIfNot() { }
	// RVA: 0x290a3d0 VA: 0x7594f223d0
	public Void Refresh() { }
	// RVA: 0x290a9ec VA: 0x7594f229ec
	public Void .ctor() { }
}
```