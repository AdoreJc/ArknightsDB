# StageZoneHomeEntryLayout

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneHomeEntryItemBase _entryItemPrefab`

- `LayoutConfig _layoutConfig`

- `ZoneHomeEntryGroupModel m_groupModel`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `RenderOptions m_options`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(ZoneHomeEntryGroupModel, RenderOptions)`

- `Void _OnEntryItemClicked(ZoneHomeEntryItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeEntryLayout : UICustomAdapterLayout`2
{
	private StageZoneHomeEntryItemBase _entryItemPrefab; // 0x78
	private LayoutConfig _layoutConfig; // 0x80
	private ZoneHomeEntryGroupModel m_groupModel; // 0x88
	private InnerLayouter m_layouter; // 0x90
	private InnerAdapter m_adapter; // 0x98
	private RenderOptions m_options; // 0xa0
	private Boolean m_isInited; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnEntryItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2efd858 VA: 0x7595515858
	private Void _InitIfNot() { }
	// RVA: 0x2efc314 VA: 0x7595514314
	public Void Render(ZoneHomeEntryGroupModel groupModel, RenderOptions options) { }
	// RVA: 0x2efdbb4 VA: 0x7595515bb4
	private Void _OnEntryItemClicked(ZoneHomeEntryItemModel itemModel) { }
	// RVA: 0x2efdc54 VA: 0x7595515c54
	public Void .ctor() { }
}
```