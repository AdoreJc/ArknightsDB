# CarvingSlotCardListView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingSlotCardViewHolder _slotCardViewPrefab`

- `UIAnimationLocation _sampleCurve`

- `Single _alignDuration`

- `EaseType _alignEase`

- `Single _showDuration`

- `EaseType _showEase`

- `CarvingCardListViewModel m_cachedCardListViewModel`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `String m_cachedProcessCardId`

- `Boolean m_inited`

- `DragHandler <dragHandler>k__BackingField`


## Properties

- `DragHandler dragHandler`


## Methods

- `DragHandler get_dragHandler()`

- `Void set_dragHandler(DragHandler)`

- `Void _InitIfNot()`

- `Void Render(CarvingMainViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingSlotCardListView : UICustomAdapterLayout`2
{
	private CarvingSlotCardViewHolder _slotCardViewPrefab; // 0x78
	private UIAnimationLocation _sampleCurve; // 0x80
	private Single[] _samplePosList; // 0x90
	private Single _alignDuration; // 0x98
	private EaseType _alignEase; // 0x9c
	private Single _showDuration; // 0xa0
	private EaseType _showEase; // 0xa4
	private CarvingCardListViewModel m_cachedCardListViewModel; // 0xa8
	private InnerLayouter m_layouter; // 0xb0
	private InnerAdapter m_adapter; // 0xb8
	private String m_cachedProcessCardId; // 0xc0
	private Boolean m_inited; // 0xc8
	private DragHandler <dragHandler>k__BackingField; // 0xd0
	private static DelegateBridge __Hotfix0_get_dragHandler; // 0x0
	private static DelegateBridge __Hotfix0_set_dragHandler; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private DragHandler dragHandler { get; set; }

	// RVA: 0x2d9d694 VA: 0x75953b5694
	private DragHandler get_dragHandler() { }
	// RVA: 0x2d9c5cc VA: 0x75953b45cc
	public Void set_dragHandler(DragHandler value) { }
	// RVA: 0x2d9d6fc VA: 0x75953b56fc
	private Void _InitIfNot() { }
	// RVA: 0x2d9c9ac VA: 0x75953b49ac
	public Void Render(CarvingMainViewModel model) { }
	// RVA: 0x2d9da7c VA: 0x75953b5a7c
	public Void .ctor() { }
}
```