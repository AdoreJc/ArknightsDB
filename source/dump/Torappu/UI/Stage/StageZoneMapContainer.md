# StageZoneMapContainer

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageClickEvent _onStageClicked`

- `RectTransform _mapPositionHandler`

- `RectTransform _mapParent`

- `RectTransform _stageHotspot`

- `UIStringEvent _eventMapNotFound`

- `UIStringEvent _eventMapLoadFinish`

- `String m_zoneMapAssetPathCache`

- `String m_selectedStageIdCache`

- `String m_focusStageIdCache`

- `StageZoneMap m_zoneMap`

- `Vector2 m_originMapPos`

- `Bounds m_stageHotspotBound`

- `Tween m_mapTweener`


## Methods

- `Void _MoveMapWithTween(Vector2)`

- `Vector2 _GetMapPos()`

- `Void _FocusOnSelectedStage(String)`

- `Void Start()`

- `Void OnDestroy()`

- `Void _OnStageSelected(String)`

- `Void _ClearCachedMap()`

- `Void _ClearUpdateCache()`

- `Boolean _LoadZoneMap(ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneMapContainer : DataBinder`1
{
	private StageClickEvent _onStageClicked; // 0x20
	private RectTransform _mapPositionHandler; // 0x28
	private RectTransform _mapParent; // 0x30
	private RectTransform _stageHotspot; // 0x38
	private UIStringEvent _eventMapNotFound; // 0x40
	private UIStringEvent _eventMapLoadFinish; // 0x48
	private String m_zoneMapAssetPathCache; // 0x50
	private String m_selectedStageIdCache; // 0x58
	private String m_focusStageIdCache; // 0x60
	private StageZoneMap m_zoneMap; // 0x68
	private const Single ANIM_DURATION; // 0x0
	private Vector2 m_originMapPos; // 0x70
	private Bounds m_stageHotspotBound; // 0x78
	private Tween m_mapTweener; // 0x90
	private static DelegateBridge __Hotfix0__MoveMapWithTween; // 0x0
	private static DelegateBridge __Hotfix0__GetMapPos; // 0x8
	private static DelegateBridge __Hotfix0__FocusOnSelectedStage; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__OnStageSelected; // 0x30
	private static DelegateBridge __Hotfix0__ClearCachedMap; // 0x38
	private static DelegateBridge __Hotfix0__ClearUpdateCache; // 0x40
	private static DelegateBridge __Hotfix0__LoadZoneMap; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2faf2ec VA: 0x75955c72ec
	private Void _MoveMapWithTween(Vector2 targetAnchorPos) { }
	// RVA: 0x2faf488 VA: 0x75955c7488
	private Vector2 _GetMapPos() { }
	// RVA: 0x2faf4fc VA: 0x75955c74fc
	private Void _FocusOnSelectedStage(String focusStageId) { }
	// RVA: 0x2faf6f4 VA: 0x75955c76f4
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2fafce4 VA: 0x75955c7ce4
	private Void Start() { }
	// RVA: 0x2fafdc0 VA: 0x75955c7dc0
	private Void OnDestroy() { }
	// RVA: 0x2fafe28 VA: 0x75955c7e28
	private Void _OnStageSelected(String stageId) { }
	// RVA: 0x2faf984 VA: 0x75955c7984
	private Void _ClearCachedMap() { }
	// RVA: 0x2fafa00 VA: 0x75955c7a00
	private Void _ClearUpdateCache() { }
	// RVA: 0x2fafaa4 VA: 0x75955c7aa4
	private Boolean _LoadZoneMap(ZoneViewModel zoneModel) { }
	// RVA: 0x2faff78 VA: 0x75955c7f78
	public Void .ctor() { }
}
```