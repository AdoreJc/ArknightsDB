# SiracusaMapZoneMapHolder

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `RectTransform _bigMapContainer`

- `RectTransform _smallMapContainer`

- `SiracusaMapBigMapView _bigMapPrefab`

- `SiracusaMapSmallMapView _smallMapPrefab`

- `SiracusaMapBigMapView m_bigMapView`

- `SiracusaMapSmallMapView m_smallMapView`

- `SiracusaMapController m_closure`

- `Action <onBigMapBlankClicked>k__BackingField`


## Properties

- `Action onBigMapBlankClicked`


## Methods

- `Void set_onNodeClicked(Action`1)`

- `Action get_onBigMapBlankClicked()`

- `Void set_onBigMapBlankClicked(Action)`

- `Void Init(SiracusaMapController)`

- `Void _OnFogClicked()`

- `Void _OnNodeClick(SiracusaMapMapNodeViewModel)`

- `Void _OnBigMapBlankClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapZoneMapHolder : MonoBehaviour, IHotfixable
{
	private RectTransform _bigMapContainer; // 0x18
	private RectTransform _smallMapContainer; // 0x20
	private SiracusaMapBigMapView _bigMapPrefab; // 0x28
	private SiracusaMapSmallMapView _smallMapPrefab; // 0x30
	private SiracusaMapBigMapView m_bigMapView; // 0x38
	private SiracusaMapSmallMapView m_smallMapView; // 0x40
	private SiracusaMapController m_closure; // 0x48
	private Action`1 <onNodeClicked>k__BackingField; // 0x50
	private Action <onBigMapBlankClicked>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onNodeClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNodeClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onBigMapBlankClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onBigMapBlankClicked; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0__OnFogClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnNodeClick; // 0x30
	private static DelegateBridge __Hotfix0__OnBigMapBlankClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action`1 onNodeClicked { get; set; }
	private Action onBigMapBlankClicked { get; set; }

	// RVA: 0x2414350 VA: 0x7594a2c350
	private Action`1 get_onNodeClicked() { }
	// RVA: 0x24143b8 VA: 0x7594a2c3b8
	public Void set_onNodeClicked(Action`1 value) { }
	// RVA: 0x241443c VA: 0x7594a2c43c
	private Action get_onBigMapBlankClicked() { }
	// RVA: 0x24144a4 VA: 0x7594a2c4a4
	public Void set_onBigMapBlankClicked(Action value) { }
	// RVA: 0x2414528 VA: 0x7594a2c528
	public Void Init(SiracusaMapController mapController) { }
	// RVA: 0x24148e0 VA: 0x7594a2c8e0
	private Void _OnFogClicked() { }
	// RVA: 0x24149d0 VA: 0x7594a2c9d0
	private Void _OnNodeClick(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x2414a88 VA: 0x7594a2ca88
	private Void _OnBigMapBlankClicked() { }
	// RVA: 0x2414b24 VA: 0x7594a2cb24
	public Void .ctor() { }
}
```