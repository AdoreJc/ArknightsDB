# DeepSeaRPPlaceHolder

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `RectTransform _placeParent`

- `String _placeId`

- `DeepSeaRPPlaceView m_viewInstance`

- `DeepSeaRPPlaceModel m_placeModel`


## Properties

- `String placeId`

- `Boolean isActive`

- `PlaceStatus placeStatus`


## Methods

- `String get_placeId()`

- `Boolean get_isActive()`

- `PlaceStatus get_placeStatus()`

- `Boolean IsGrey()`

- `Boolean HasTrackPoint()`

- `Void Render(DeepSeaRPPlaceModel, DeepSeaRPZoneMapView, DeepSeaRPPlaceView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPPlaceHolder : MonoBehaviour, IHotfixable
{
	private RectTransform _placeParent; // 0x18
	private String _placeId; // 0x20
	private DeepSeaRPPlaceView m_viewInstance; // 0x28
	private DeepSeaRPPlaceModel m_placeModel; // 0x30
	private static DelegateBridge __Hotfix0_get_placeId; // 0x0
	private static DelegateBridge __Hotfix0_get_isActive; // 0x8
	private static DelegateBridge __Hotfix0_get_placeStatus; // 0x10
	private static DelegateBridge __Hotfix0_IsGrey; // 0x18
	private static DelegateBridge __Hotfix0_HasTrackPoint; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String placeId { get; }
	public Boolean isActive { get; }
	public PlaceStatus placeStatus { get; }

	// RVA: 0x29c7b74 VA: 0x7594fdfb74
	public String get_placeId() { }
	// RVA: 0x29c7bdc VA: 0x7594fdfbdc
	public Boolean get_isActive() { }
	// RVA: 0x29c7c58 VA: 0x7594fdfc58
	public PlaceStatus get_placeStatus() { }
	// RVA: 0x29c7cd4 VA: 0x7594fdfcd4
	public Boolean IsGrey() { }
	// RVA: 0x29c7d64 VA: 0x7594fdfd64
	public Boolean HasTrackPoint() { }
	// RVA: 0x29c7e24 VA: 0x7594fdfe24
	public Void Render(DeepSeaRPPlaceModel placeModel, DeepSeaRPZoneMapView mapView, DeepSeaRPPlaceView placeViewTemplate) { }
	// RVA: 0x29c8330 VA: 0x7594fe0330
	public Void .ctor() { }
}
```