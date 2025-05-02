# UIHomeThemeTrackPoint

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _trackPointPrefab`

- `Transform _pointContainer`

- `Boolean m_isInited`

- `GameObject m_trackPoint`

- `GameObject m_injectTrackPoint`

- `Boolean m_useInjectTrackPoint`

- `Boolean m_cacheState`

- `ITrackPointModel m_model`


## Properties

- `GameObject trackPoint`


## Methods

- `GameObject get_trackPoint()`

- `Void SetTrackpoint(GameObject)`

- `Void _InitDefaultTrackPoint()`

- `Void _Render(ITrackPointModel)`

- `Void OnStateChangd(ITrackPointStatus)`

- `Void _Set(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIHomeThemeTrackPoint : DataBinder`1
{
	private GameObject _trackPointPrefab; // 0x20
	private Transform _pointContainer; // 0x28
	private Boolean m_isInited; // 0x30
	private GameObject m_trackPoint; // 0x38
	private GameObject m_injectTrackPoint; // 0x40
	private Boolean m_useInjectTrackPoint; // 0x48
	private Boolean m_cacheState; // 0x49
	private ITrackPointModel m_model; // 0x50
	private static DelegateBridge __Hotfix0_get_trackPoint; // 0x0
	private static DelegateBridge __Hotfix0_SetTrackpoint; // 0x8
	private static DelegateBridge __Hotfix0__InitDefaultTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0_OnStateChangd; // 0x28
	private static DelegateBridge __Hotfix0__Set; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	protected GameObject trackPoint { get; }

	// RVA: 0x226e3ac VA: 0x75948863ac
	protected GameObject get_trackPoint() { }
	// RVA: 0x226e424 VA: 0x7594886424
	public Void SetTrackpoint(GameObject trackPoint) { }
	// RVA: 0x226e740 VA: 0x7594886740
	private Void _InitDefaultTrackPoint() { }
	// RVA: 0x226e878 VA: 0x7594886878
	public override Void OnValueChanged(TrackPointViewProperty property) { }
	// RVA: 0x226e638 VA: 0x7594886638
	private Void _Render(ITrackPointModel viewModel) { }
	// RVA: 0x226e9b0 VA: 0x75948869b0
	public Void OnStateChangd(ITrackPointStatus status) { }
	// RVA: 0x226e550 VA: 0x7594886550
	private Void _Set(Boolean show) { }
	// RVA: 0x226eaa4 VA: 0x7594886aa4
	public Void .ctor() { }
}
```