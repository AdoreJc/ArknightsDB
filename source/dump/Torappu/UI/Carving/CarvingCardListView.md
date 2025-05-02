# CarvingCardListView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingCardViewHolder _viewHolderPrefab`

- `Single _fullCardCnt`

- `Single _scaleNotSelected`

- `UIAnimationLocation _sampleCurve`

- `Single _alignDuration`

- `EaseType _alignEase`

- `Single _showDuration`

- `EaseType _showEase`

- `CarvingMainViewModel m_cachedCarvingViewModel`

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
public class CarvingCardListView : UICustomAdapterLayout`2
{
	private CarvingCardViewHolder _viewHolderPrefab; // 0x78
	private Single _fullCardCnt; // 0x80
	private Single _scaleNotSelected; // 0x84
	private UIAnimationLocation _sampleCurve; // 0x88
	private Single _alignDuration; // 0x98
	private EaseType _alignEase; // 0x9c
	private Single _showDuration; // 0xa0
	private EaseType _showEase; // 0xa4
	private CarvingMainViewModel m_cachedCarvingViewModel; // 0xa8
	private CarvingCardListViewModel m_cachedCardListViewModel; // 0xb0
	private InnerLayouter m_layouter; // 0xb8
	private InnerAdapter m_adapter; // 0xc0
	private String m_cachedProcessCardId; // 0xc8
	private Boolean m_inited; // 0xd0
	private DragHandler <dragHandler>k__BackingField; // 0xd8
	private static DelegateBridge __Hotfix0_get_dragHandler; // 0x0
	private static DelegateBridge __Hotfix0_set_dragHandler; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private DragHandler dragHandler { get; set; }

	// RVA: 0x2da2958 VA: 0x75953ba958
	private DragHandler get_dragHandler() { }
	// RVA: 0x2da0de8 VA: 0x75953b8de8
	public Void set_dragHandler(DragHandler value) { }
	// RVA: 0x2da29c0 VA: 0x75953ba9c0
	private Void _InitIfNot() { }
	// RVA: 0x2da1144 VA: 0x75953b9144
	public Void Render(CarvingMainViewModel carvingMainViewModel) { }
	// RVA: 0x2da2d40 VA: 0x75953bad40
	public Void .ctor() { }
}
```