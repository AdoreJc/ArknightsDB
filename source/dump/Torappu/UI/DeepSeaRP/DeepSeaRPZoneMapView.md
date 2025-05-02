# DeepSeaRPZoneMapView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `RectTransform _cursorContainer`

- `RectTransform _contentRt`

- `ScrollRect _mapScroll`

- `Single _mapPadding`

- `Single _contentWidthLimit`

- `Single _focusDuration`

- `RectTransform _slideBgRt`

- `DeepSeaRPZoneMapContainer m_mapContainer`

- `GameObject m_cursorGo`

- `Tween m_posTween`

- `Single m_cacheWidth`

- `Single m_maxContentWidth`

- `Boolean m_notFirstScroll`

- `Boolean <isMapLock>k__BackingField`


## Properties

- `Boolean isMapLock`


## Methods

- `Boolean get_isMapLock()`

- `Void set_isMapLock(Boolean)`

- `Void set_onNodeClick(Action`2)`

- `Void set_onPlaceDiscover(Action`1)`

- `Void Render(DeepSeaRPModel, DeepSeaRPZoneMapContainer, DeepSeaRPPlaceView, GameObject)`

- `Void AdjustMapView()`

- `Void _UpdateMapHint()`

- `Void _UpdateSlideBgPos()`

- `Void FocusOnPlace(String)`

- `Void TryScrollToEnd(DeepSeaRPModel)`

- `Void _ScrollTo(Single)`

- `Void OnScroll(Vector2)`

- `Single <_ScrollTo>b__33_0()`

- `Void <_ScrollTo>b__33_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPZoneMapView : MonoBehaviour, IHotfixable
{
	private DeepSeaRPPlaceHolder[] _placeHolderList; // 0x18
	private RectTransform _cursorContainer; // 0x20
	private RectTransform _contentRt; // 0x28
	private ScrollRect _mapScroll; // 0x30
	private Single _mapPadding; // 0x38
	private Single _contentWidthLimit; // 0x3c
	private Single _focusDuration; // 0x40
	private RectTransform _slideBgRt; // 0x48
	private List`1 m_trackPointPlaceList; // 0x50
	private DeepSeaRPZoneMapContainer m_mapContainer; // 0x58
	private GameObject m_cursorGo; // 0x60
	private Tween m_posTween; // 0x68
	private Single m_cacheWidth; // 0x70
	private Single m_maxContentWidth; // 0x74
	private Boolean m_notFirstScroll; // 0x78
	private Boolean <isMapLock>k__BackingField; // 0x79
	private Action`2 <onNodeClick>k__BackingField; // 0x80
	private Action`1 <onPlaceDiscover>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_isMapLock; // 0x0
	private static DelegateBridge __Hotfix0_set_isMapLock; // 0x8
	private static DelegateBridge __Hotfix0_get_onNodeClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onNodeClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onPlaceDiscover; // 0x20
	private static DelegateBridge __Hotfix0_set_onPlaceDiscover; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_AdjustMapView; // 0x38
	private static DelegateBridge __Hotfix0__UpdateMapHint; // 0x40
	private static DelegateBridge __Hotfix0__UpdateSlideBgPos; // 0x48
	private static DelegateBridge __Hotfix0_FocusOnPlace; // 0x50
	private static DelegateBridge __Hotfix0_TryScrollToEnd; // 0x58
	private static DelegateBridge __Hotfix0__ScrollTo; // 0x60
	private static DelegateBridge __Hotfix0_OnScroll; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean isMapLock { get; set; }
	public Action`2 onNodeClick { get; set; }
	public Action`1 onPlaceDiscover { get; set; }

	// RVA: 0x29cff40 VA: 0x7594fe7f40
	public Boolean get_isMapLock() { }
	// RVA: 0x29ca7c8 VA: 0x7594fe27c8
	public Void set_isMapLock(Boolean value) { }
	// RVA: 0x29d0884 VA: 0x7594fe8884
	public Action`2 get_onNodeClick() { }
	// RVA: 0x29d0324 VA: 0x7594fe8324
	public Void set_onNodeClick(Action`2 value) { }
	// RVA: 0x29d08ec VA: 0x7594fe88ec
	public Action`1 get_onPlaceDiscover() { }
	// RVA: 0x29d03a8 VA: 0x7594fe83a8
	public Void set_onPlaceDiscover(Action`1 value) { }
	// RVA: 0x29cf5e0 VA: 0x7594fe75e0
	public Void Render(DeepSeaRPModel deepSeaModel, DeepSeaRPZoneMapContainer mapContainer, DeepSeaRPPlaceView placeTemplate, GameObject cursorTemplate) { }
	// RVA: 0x29cf9f4 VA: 0x7594fe79f4
	public Void AdjustMapView() { }
	// RVA: 0x29d0954 VA: 0x7594fe8954
	private Void _UpdateMapHint() { }
	// RVA: 0x29d0b48 VA: 0x7594fe8b48
	private Void _UpdateSlideBgPos() { }
	// RVA: 0x29d0500 VA: 0x7594fe8500
	public Void FocusOnPlace(String placeId) { }
	// RVA: 0x29cfcc0 VA: 0x7594fe7cc0
	public Void TryScrollToEnd(DeepSeaRPModel deepSeaModel) { }
	// RVA: 0x29d0cd4 VA: 0x7594fe8cd4
	private Void _ScrollTo(Single normalizedVal) { }
	// RVA: 0x29d0e64 VA: 0x7594fe8e64
	public Void OnScroll(Vector2 _) { }
	// RVA: 0x29d0ef0 VA: 0x7594fe8ef0
	public Void .ctor() { }
	// RVA: 0x29d0fc8 VA: 0x7594fe8fc8
	private Single <_ScrollTo>b__33_0() { }
	// RVA: 0x29d0fe4 VA: 0x7594fe8fe4
	private Void <_ScrollTo>b__33_1(Single val) { }
}
```