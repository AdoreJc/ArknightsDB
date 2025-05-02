# SimpleActivityStageButtonOnMap

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIColorGraphic _selectionGraphic`

- `Color _selectedColor`

- `Color _codeTextColor`

- `StageRankView _stageRankView`

- `SimpleActivityStageButtonOnMapPlugin m_plugin`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder, StageViewModel, ZoneViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SimpleActivityStageButtonOnMap : StageButtonOnMap, IHotfixable
{
	private UIColorGraphic _selectionGraphic; // 0xd8
	private Color _selectedColor; // 0xe0
	private Color _codeTextColor; // 0xf0
	private StageRankView _stageRankView; // 0x100
	private SimpleActivityStageButtonOnMapPlugin m_plugin; // 0x108
	private Boolean m_inited; // 0x110
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderStage; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ef36f0 VA: 0x759550b6f0
	private Void _InitIfNot() { }
	// RVA: 0x2ef379c VA: 0x759550b79c
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x2ef3a98 VA: 0x759550ba98
	public Void .ctor() { }
	// RVA: 0x2ef3b10 VA: 0x759550bb10
	private Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder P0, StageViewModel P1, ZoneViewModel P2, Boolean P3) { }
}
```