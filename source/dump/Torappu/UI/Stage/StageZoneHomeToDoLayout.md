# StageZoneHomeToDoLayout

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _bound`

- `StageZoneHomeToDoItem _itemPrefab`

- `GameObject _panelEmpty`

- `Vector2 _gridSize`

- `Rect _padding`

- `Vector2 _spacing`

- `ZoneHomeToDoGroupModel m_groupModel`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `RenderOptions m_options`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(ZoneHomeToDoGroupModel, RenderOptions)`

- `Void _OnToDoItemClicked(ZoneHomeToDoItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeToDoLayout : UICustomAdapterLayout`2
{
	private RectTransform _bound; // 0x78
	private StageZoneHomeToDoItem _itemPrefab; // 0x80
	private GameObject _panelEmpty; // 0x88
	private Vector2 _gridSize; // 0x90
	private Rect _padding; // 0x98
	private Vector2 _spacing; // 0xa8
	private ZoneHomeToDoGroupModel m_groupModel; // 0xb0
	private InnerLayouter m_layouter; // 0xb8
	private InnerAdapter m_adapter; // 0xc0
	private RenderOptions m_options; // 0xc8
	private Boolean m_isInited; // 0xd0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnToDoItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f05690 VA: 0x759551d690
	private Void _InitIfNot() { }
	// RVA: 0x2f046bc VA: 0x759551c6bc
	public Void Render(ZoneHomeToDoGroupModel groupModel, RenderOptions options) { }
	// RVA: 0x2f05814 VA: 0x759551d814
	private Void _OnToDoItemClicked(ZoneHomeToDoItemModel viewModel) { }
	// RVA: 0x2f058b4 VA: 0x759551d8b4
	public Void .ctor() { }
}
```