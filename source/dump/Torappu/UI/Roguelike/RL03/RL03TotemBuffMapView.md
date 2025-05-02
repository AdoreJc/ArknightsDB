# RL03TotemBuffMapView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RectTransform _layerPrefab`

- `RectTransform _layerContainer`

- `RL03TotemBuffMapNodeView _nodeViewPrefab`

- `Int32 m_curZoneIndex`

- `RL03TotemBuffMapViewModel m_cachedViewModel`


## Methods

- `Void set_OnNodeClick(Action`2)`

- `Void _CreateZone(RL03TotemBuffMapViewModel)`

- `Void _RenderZone(RL03TotemBuffMapViewModel)`

- `Void _OnMapNodeClick(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffMapView : DataBinder`1
{
	private RectTransform _layerPrefab; // 0x20
	private RectTransform _layerContainer; // 0x28
	private RL03TotemBuffMapNodeView _nodeViewPrefab; // 0x30
	private Action`2 <OnNodeClick>k__BackingField; // 0x38
	private Int32 m_curZoneIndex; // 0x40
	private RL03TotemBuffMapViewModel m_cachedViewModel; // 0x48
	private Dictionary`2 m_nodeViews; // 0x50
	private static DelegateBridge __Hotfix0_get_OnNodeClick; // 0x0
	private static DelegateBridge __Hotfix0_set_OnNodeClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__CreateZone; // 0x18
	private static DelegateBridge __Hotfix0__RenderZone; // 0x20
	private static DelegateBridge __Hotfix0__OnMapNodeClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`2 OnNodeClick { get; set; }

	// RVA: 0x2ba9c00 VA: 0x75951c1c00
	private Action`2 get_OnNodeClick() { }
	// RVA: 0x2ba9c68 VA: 0x75951c1c68
	public Void set_OnNodeClick(Action`2 value) { }
	// RVA: 0x2ba9cec VA: 0x75951c1cec
	public override Void OnValueChanged(RL03TotemMapViewProperty property) { }
	// RVA: 0x2ba9dd4 VA: 0x75951c1dd4
	private Void _CreateZone(RL03TotemBuffMapViewModel viewModel) { }
	// RVA: 0x2baa13c VA: 0x75951c213c
	private Void _RenderZone(RL03TotemBuffMapViewModel viewModel) { }
	// RVA: 0x2baa780 VA: 0x75951c2780
	private Void _OnMapNodeClick(Int32 depth, Int32 index) { }
	// RVA: 0x2baa844 VA: 0x75951c2844
	public Void .ctor() { }
}
```