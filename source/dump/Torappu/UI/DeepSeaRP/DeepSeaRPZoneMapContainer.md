# DeepSeaRPZoneMapContainer

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `RectTransform _mapRoot`

- `DeepSeaRPPlaceView _placeTemplate`

- `GameObject _cursorTemplate`

- `GameObject _leftHintGo`

- `GameObject _rightHintGo`

- `Single _visibleOffset`

- `Single _unknownOffset`

- `Single _greyOffset`

- `String m_currentZoneId`

- `DeepSeaRPZoneMapView m_mapView`

- `UIPageFinder m_pageFinder`


## Properties

- `Single visibleOffset`

- `Single unknownOffset`

- `Single greyOffset`


## Methods

- `Single get_visibleOffset()`

- `Single get_unknownOffset()`

- `Single get_greyOffset()`

- `Void set_onNodeClick(Action`2)`

- `Void set_onPlaceDiscover(Action`1)`

- `Void SetMapLock()`

- `Boolean IsMapLock()`

- `Void SetHintVisible(Boolean, Boolean)`

- `Boolean _SetupZoneMapIfNeeded(DeepSeaRPModel)`

- `String _GetZoneMapAssetPath(String)`

- `Void FocusOnPlace(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPZoneMapContainer : DataBinder`1
{
	private RectTransform _mapRoot; // 0x20
	private DeepSeaRPPlaceView _placeTemplate; // 0x28
	private GameObject _cursorTemplate; // 0x30
	private GameObject _leftHintGo; // 0x38
	private GameObject _rightHintGo; // 0x40
	private Single _visibleOffset; // 0x48
	private Single _unknownOffset; // 0x4c
	private Single _greyOffset; // 0x50
	private String m_currentZoneId; // 0x58
	private DeepSeaRPZoneMapView m_mapView; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private Action`2 <onNodeClick>k__BackingField; // 0x78
	private Action`1 <onPlaceDiscover>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_visibleOffset; // 0x0
	private static DelegateBridge __Hotfix0_get_unknownOffset; // 0x8
	private static DelegateBridge __Hotfix0_get_greyOffset; // 0x10
	private static DelegateBridge __Hotfix0_get_onNodeClick; // 0x18
	private static DelegateBridge __Hotfix0_set_onNodeClick; // 0x20
	private static DelegateBridge __Hotfix0_get_onPlaceDiscover; // 0x28
	private static DelegateBridge __Hotfix0_set_onPlaceDiscover; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0_SetMapLock; // 0x40
	private static DelegateBridge __Hotfix0_IsMapLock; // 0x48
	private static DelegateBridge __Hotfix0_SetHintVisible; // 0x50
	private static DelegateBridge __Hotfix0__SetupZoneMapIfNeeded; // 0x58
	private static DelegateBridge __Hotfix0__GetZoneMapAssetPath; // 0x60
	private static DelegateBridge __Hotfix0_FocusOnPlace; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Single visibleOffset { get; }
	public Single unknownOffset { get; }
	public Single greyOffset { get; }
	private Action`2 onNodeClick { get; set; }
	private Action`1 onPlaceDiscover { get; set; }

	// RVA: 0x29cefb4 VA: 0x7594fe6fb4
	public Single get_visibleOffset() { }
	// RVA: 0x29cf01c VA: 0x7594fe701c
	public Single get_unknownOffset() { }
	// RVA: 0x29cf084 VA: 0x7594fe7084
	public Single get_greyOffset() { }
	// RVA: 0x29cf0ec VA: 0x7594fe70ec
	private Action`2 get_onNodeClick() { }
	// RVA: 0x29cf154 VA: 0x7594fe7154
	public Void set_onNodeClick(Action`2 value) { }
	// RVA: 0x29cf1d8 VA: 0x7594fe71d8
	private Action`1 get_onPlaceDiscover() { }
	// RVA: 0x29cf240 VA: 0x7594fe7240
	public Void set_onPlaceDiscover(Action`1 value) { }
	// RVA: 0x29cf2c4 VA: 0x7594fe72c4
	public override Void OnValueChanged(DeepSeaRPProperty property) { }
	// RVA: 0x29cfdc8 VA: 0x7594fe7dc8
	public Void SetMapLock() { }
	// RVA: 0x29cfe84 VA: 0x7594fe7e84
	public Boolean IsMapLock() { }
	// RVA: 0x29cffa8 VA: 0x7594fe7fa8
	public Void SetHintVisible(Boolean isLeft, Boolean isShow) { }
	// RVA: 0x29cf3f0 VA: 0x7594fe73f0
	private Boolean _SetupZoneMapIfNeeded(DeepSeaRPModel deepSeaModel) { }
	// RVA: 0x29d0040 VA: 0x7594fe8040
	private String _GetZoneMapAssetPath(String zoneId) { }
	// RVA: 0x29d042c VA: 0x7594fe842c
	public Void FocusOnPlace(String placeId) { }
	// RVA: 0x29d0758 VA: 0x7594fe8758
	public Void .ctor() { }
}
```